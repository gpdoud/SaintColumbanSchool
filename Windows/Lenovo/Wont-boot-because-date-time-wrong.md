# "Yoga 11e" won't boot because date and time has not been set

## ISSUE

After charging, a boot will show a message that it cannot boot up because the system date and time has not been setup. 

    0271: Check Date and Time settings.
    System CMOS Checksum bad.

    Press Esc to continue or F1 to enter Setup

## RESOLUTION

When the message displays,  press the F1 key. You'll be taken to the BIOS (which is for the setup)

On the second line, you'll see the menu items:

    Main, Config, Date/Time, Security, Startup, Restart

Main will be highlighted. Use the right arrow key to move to the Date/Time item.

It will display System Date and System Time. 

The Month of the System Date will be highlighted. Type two digits to set the month. For example, press 10 for October or 11 for November. If you make a mistake, just press 00 then rekey the two digits.

Press the TAB to move to the Date. Type two digits just like the month.

Press the TAB to move to the Year. Type four digits for the year.

If you have to redo, just hold down the SHIFT key and press the TAB. This will move backwards.

When you're done with the System Date, press the DOWN ARROW to move to the SYSTEM TIME. Enter the HOURS first and you must use the 24 hour number. So if the time is 2:15 pm, the hour should be set to 14. If the time is 7:35 pm, the hour would be 19.

Press the TAB button to move to the minutes. Press two digits for the minutes.

Press the TAB button to move to the seconds. If you don't care about the seconds, you can skip it.

When you're all done, Press F10 to save the SYSTEM DATE and SYSTEM TIME and have the laptop reboot. This should allow a normal boot.