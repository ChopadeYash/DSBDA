To directly take the folder from the Main OS to the OS in the VM box, 
we can mount the folder to the VM.

Steps:
1. Open the virtual box and right click on the VM-> Settings.. -> Shared Folders -> Add new folder
    Then add the new folder by browsing the path carefully from the os.

    Click ok and start your VM.

2. Now inside the terminal in the OS of the virtual OS, 
    i. Enable su by simply writting 'su'
    ii. Then enter the password: usually for cloudera its 'cloudera'
    iii. Then write the command:
    'sudo mount -t vboxsf <shared folder name> <Folder loaction to which you want to access it from>'

3. It is interconnected folder in between these two OS.
