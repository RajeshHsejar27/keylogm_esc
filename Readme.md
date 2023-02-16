1.Extract the code into your Notepad.
2.Paste ur credentials in the required places.
3.Open CMD and use pip install to install secure-smtplib, ssl, pynput.
Prior to this you should have installed python in ur machine.
4.The password for sender's mail will not work initially.
For the sender's password:
Go to google account settings->
::Go to Security tab and find App passwords
::Add "mail" app in the app list and select "windows computer" from device's list.
::Copy the generated password and paste it in the sender's password part.
5.Save the file with .py extension. MINIMIZE the NOTEPAD.
6.Go to CMD and pip install "pyinstaller".
7.Open Powershell in the saved .py file's directory 
|| Or || 
you can just open Powershell and cd to the .py file's directory->
::Type the following command:

pyinstaller --onefile -w 'filename.py'

::At the place of filename, give the filename which u used.
::Press Enter.
::It will build the package in the same directory.
8.You will now see the folder: "build" ,file: "filename.spec",exe file: filename.exe
::Run the exe file and it will start to record the keystrokes until Esc key is pressed.
::After the Esc key event, you will get the keylog mail in the recipient's mail.

Note::
It is highly likeable that the exe file will get blocked by the system's antivirus.
So, the antivirus protection should be disabled incase it does block and u can,
::either redo the steps from starting on creating a new exe file or,
::just go to antivirus settings and remove the exe file from quarantined threats, also during this,
if you didnt find the exe file to be restored, just open the minimized notepad and "ctrl+s" to make the file appear and convert it to exe.

Additional::
This is for the sole purpose of testing out the keylogger and its concept working.
You can even make modifications to the code to change how it works,like :
::Instead of Esc key you can use anyother to exit the program
::Make some modifications in the format of how the key log should appear
::Format of the keys pressed like enter,shift,capslock can be changed to view better.
::Also a timer can run around which would record the keystrokes for that time being.
