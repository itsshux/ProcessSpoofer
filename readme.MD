# Welcome to the ProcessSpoofer Wiki!

## Support

If you encounter any issues, feel free to ask a question in the [Discord server](https://discord.gg/nfJkdsSpgE) or DM me directly at shux#5351.

### Tutorial Video

[Here's a tutorial video](https://youtu.be/YBM-wFdE068) to help you get started.

Each download will have a hash linked to it (coming soon).

Just a quick note, since I added new features like version checking and the ability to run on startup, ProcessSpoofer is now being flagged by even more antivirus programs. These additional features require ProcessSpoofer to access system processes and memory, which can trigger antivirus software to mistakenly identify it as a potential threat. As with the previous version, it's important to understand that ProcessSpoofer is not actually harmful, and adding it to your antivirus exception list can prevent false positives.

***

# How to Use

To use ProcessSpoofer, you need to run it as an administrator or it won't work! Before running ProcessSpoofer, make sure you create a file named hide.txt in APPDATA. You can do this by pressing Windows key + R and typing `%appdata%`.

Add the processes you want to hide in the hide.txt file. For example:

* notepad.exe
* EpicProgram.exe

Since version 1.2, you can hide process icons from task view by adding a semicolon (;) in front of the process name. Example:

* notepad.exe;

You can add an unlimited number of processes.

ProcessSpoofer has built-in commands that will be displayed once you run the program.

You can hide the ProcessSpoofer window by typing "hide". To show it again, just press INSERT.

In case you can't see the window after pressing INSERT, try killing it using Command Prompt. Make sure you run Command Prompt as an administrator:

`taskkill /IM ProcessHacker.exe /F`

# Antivirus - False Positive

There's a chance that your antivirus might flag ProcessSpoofer as malicious due to its nature. You can add either ProcessSpoofer.exe or its directory to the exception list in your antivirus settings. It's a false positive.

Exceptions in Windows Defender: [click here](https://support.microsoft.com/en-us/windows/add-an-exclusion-to-windows-security-811816c0-4dfd-af4a-47e4-c301afe13b26).

Exclusions in Malwarebytes: [click here](https://support.malwarebytes.com/hc/en-us/articles/360038479234-Exclude-detections-in-Malwarebytes-for-Windows).

***

# Warning

**WARNING:** ProcessSpoofer is a powerful security tool that allows you to hide processes from enumeration. While this can be useful in certain situations, it can also have unintended consequences and potentially interfere with the normal operation of your system or other programs. Please use this tool with caution, and be aware of the potential risks and limitations associated with hiding processes from enumeration.

In particular, please note that certain security or antivirus programs may flag ProcessSpoofer as potentially harmful or malicious. By using ProcessSpoofer, you acknowledge and accept these risks and limitations, and agree to hold the developers harmless for any unintended consequences or damages that may result from its use.

Do not modify ProcessSpoofer in any way, as doing so may cause unexpected behavior or damage to your system. Do not attempt to rename any files or modify any settings without consulting with the developer first. Failure to follow these guidelines may result in unintended consequences or damage to your system.
