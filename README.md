# Unsung-RP-Logger

![[Pasted image 20240221231006.png]]

Hey, this is my first Python code and something I made for a friend's specific use case. It cleans up chat logs exported from Final Fantasy XIV (Gobchat) and exports them in a .docx format, ready to upload direct to Google Docs. 

# Installation

1. Download **logConverter.py**

2. Place in the folder where your RP log is.

3. Install Python's latest version: https://www.python.org/downloads/

4. Install Python-Docx by entering this into your Command Prompt (make sure to run as admin):

```
pip install python-docx
```

# Run

1. Open Command Prompt (make sure to run as admin):

2. Write `cd` then the rest of the file path not visible in your command line.
For example, if cmd is showing `C:\Windows\system32`, use these commands:

```
cd .. 
cd ..
cd users/[username]/documents
```

To take you to the Documents folder. (Let me know if you're having trouble.)

3. When in the directory directly where your log and python file are, run this in your command line:

```
python logConverter.py
```

4. Enter the file name with the extension when prompted.

```
sample.txt
```

5. Your file should complete successfully with `-clean.docx` appended at the end.
