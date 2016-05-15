# MyASMclass
CET3510 related assignment
Windows version (using Cygwin, Putty, or Virtual Machine). All steps below assume use of the command line:
    1) Create a custom directory for your assignment
    2) Using Github and the "git clone" command, download the "CET3510_Lecture_assignments" repository
    3) Using the nano text editor open the file "ground_control_win.asm"
    4) Edit the message and include your name
    5) Save and close the file
    6) Run the assembler:
        $ nasm -fwin32 ground_control.asm
    7) Run the gcc linker to create an executable:
        $ gcc ground_control.obj -o ground_control
    8) Run the executable. Console output should now show your modified message
        $ ./ground_control
    9) In your assignment report, upload the following to Blackboard:
        a. The URL of your Github repo
        b. Screenshots of your terminal/console output
        c. A list of all terminal commands you used with a brief explanation of each of the commands and any options used within the command


Links and files for reference:
CET3510-assignments/lab11.md
CET3510-assignments/lecture11_exercise_win.png
https://github-windows.s3.amazonaws.com/GitHubSetup.exe
