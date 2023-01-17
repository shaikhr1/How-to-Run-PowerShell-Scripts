# How-to-Run-PowerShell-Scripts
To run a PowerShell script, follow these steps:

    Open PowerShell. You can do this by searching for "PowerShell" in the Start menu or by using the Run command (Windows + R) and typing "powershell".

    Change to the directory where the script is saved. Use the cd command to navigate to the directory where the script is located. For example: cd C:\Scripts.

    Run the script by typing the name of the script file followed by any necessary arguments and pressing Enter. For example: .\myscript.ps1 -arg1 value1 -arg2 value2.

Note that PowerShell scripts have a .ps1 file extension. If you are running a script from a remote location, you may need to use the Invoke-Command cmdlet to run the script on a remote computer.

You can also run a script by right-clicking on the script file and selecting "Run with PowerShell" from the context menu. This will open a PowerShell window and run the script.

If the script is located in a path with spaces, you will need to enclose the path in quotes. For example: "C:\My Scripts\myscript.ps1".

Keep in mind that some scripts may require administrator privileges to run. In this case, you will need to start PowerShell as an administrator. To do this, right-click on the PowerShell icon and select "Run as administrator" from the context menu.
