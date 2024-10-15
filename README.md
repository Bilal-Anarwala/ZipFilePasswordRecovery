# ZipFilePasswordRecovery

In this assignment, I was tasked with assisting a consulting firm investigating a suspicious email intercepted from one of their IT staff members. The email, sent to an external address, contained a ZIP file attachment called "JustStuff.zip", raising concerns about its contents.

The goal of this project was to analyze the ZIP file to determine the type and nature of the file contained within, ensuring it did not contain illegal or objectionable material.

# Methodology

To achieve this, I utilized Python and the following techniques:

To crack the password of a ZIP file, I used a brute-force approach with the following key components:

*Python & zipfile module: The Python zipfile module was used to handle the ZIP file, enabling password-protected extraction attempts.*

*tqdm: I integrated the tqdm module to provide a progress bar, offering a visual representation of the cracking process.*

*Wordlist Attack: The script reads a wordlist file (rockyou.txt), which contains a large set of potential passwords. Each password from the wordlist is tried sequentially.*

*Error Handling: If a password fails, the script continues to the next word. Upon finding the correct password, the script outputs the successful password and exits.*

*Efficiency: The script counts and prints the total number of words in the wordlist beforehand, providing insight into the scope of the password cracking task.*

I have uploaded the script and the locked zip file
