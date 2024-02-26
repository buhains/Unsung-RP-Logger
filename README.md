# Unsung-RP-Logger

![Original uncleaned log on the lefthand side. New cleaned log on the righthand side.](https://i.imgur.com/ux1SXY5.png)

Hey, this is my first Python code and something I made for a friend's specific use case. It cleans up chat logs exported from Final Fantasy XIV (Gobchat) and exports them in a .docx format, ready to upload direct to Google Docs. 

# Installation

1. Download **logConverter.py**

2. Place in the folder where your RP log is.

3. Install Python's latest version: https://www.python.org/downloads/

4. Install pip: https://pip.pypa.io/en/stable/installation/#get-pip-py

5. Install Python-Docx by entering this into your Command Prompt (make sure to run as admin):

```
pip install python-docx
```

6. Ensure all of the above installations that have been downloaded to a drive directly have their file paths enabled as system environment variables: https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_environment_variables?view=powershell-7.4#saving-environment-variables-with-the-system-control-panel
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
