# TopCenterStart11
A small utility that moves the start menu to the top-center of the screen in Windows 11.

As of right now, this application can only place the start menu at the top-center of the screen. Screen size is calculated dynamically, but I've only been able to test this on a 1920x1080 screen. I have not found a fix for the desktop switcher yet, but I am still looking into it.

## How to use?
This Utility does not move your taskbar for you. You'll have to do the registry edits yourself (for now).

When your taskbar is top-aligned, you can try out the tool by executing the EXE and pressing the start button to see the start menu centered. This change is not persistent though, so some manual configuration is required to get the tool to run at startup.

1. Download the latest version from the [Releases](https://github.com/Naamloos/TopCenterStart11/releases) page.
2. Place the EXE at any location on your system.
3. Create a shortcut to the EXE, and cut (CTRL+X) it.
4. Use the `Run` dialog (WIN+R) to open the startup folder with `shell:startup`
5. Paste (CTRL+V) the shortcut you created to this folder

Now, the application should run at startup.

## Q&A
### My taskbar is left/right aligned!
As of right now, this tool only places the start menu at the top of the screen. Adding support for other positions is planned, but as of right now only top-taskbar is supported.

### My start button is left-aligned!
Then you don't really need this tool, as this matches the default behavior of the start menu

### The animation has the wrong direction!
I don't think I can actually fix that, but feel free to [prove me wrong](https://github.com/Naamloos/TopCenterStart11/pulls)!

### I want to stop using the application!
Remove the shortcut from your `shell:startup` folder and restart explorer. The change will revert and it will not be reflected on reboot.

## Screenshot
![](https://i.imgur.com/Ud0IKO2.png)