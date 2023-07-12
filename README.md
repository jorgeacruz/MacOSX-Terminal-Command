# If U use terminal and like new command, here it this my list. Enjoy.
<br/>
<img src="https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0" />

# OSX Ventura 

## <span style="color:#FFBD44;">Power Management in macOS Ventura</span>

In Ventura, you have to use the command line to schedule waking, sleeping, rebooting, and shutting down. If you're comfortable using Terminal (/Applications/Utilities/Terminal.app), you can combine various arguments to set a schedule using the "pmset" command.

The pmset command recognizes the day, date, and time, using the MM/DD/YY format for date, and HH:MM:SS for time. So for January 10, 2024 at 7:00am you would use 1/10/24 07:00:00. You can also specify days of the week using the following letters:

Monday is M
Tuesday is T
Wednesday is W
Thursday is R
Friday is F
Saturday is S
Sunday is U
Now let's look at some scheduling options you can use, how to view an active schedule, and how to remove scheduling settings.

## <span style="color:#FFBD44;">Schedule Your Mac to Turn On or Wake From Sleep</span>

To schedule your Mac to wake or boot up each day from Monday to Friday at 7am, you would input:

<h3 style="color:#ff6600;">sudo pmset repeat wakeorpoweron MTWRF 07:00:00</span></b>

## <span style="color:#FFBD44;">Schedule Your Mac to Shut Down</span>

To schedule your Mac to shut down each weekday at 7pm, you would input:

<h3 style="color:#ff6600;">sudo pmset repeat shutdown MTWRF 19:00:00

## <span style="color:#FFBD44;">Schedule Your Mac to Restart</span>

To schedule your Mac to reboot every day of the week at midnight, you would input:

<h3 style="color:#ff6600;">sudo pmset repeat restart MTWRFSU 00:00:00

## <span style="color:#FFBD44;">View the Currently Active Schedule

To view the currently active schedule, you can use the following command (this can also be useful if you just want to double-check a schedule you just set up):

<h3 style="color:#ff6600;">pmset -g sched</h3>

## <span style="color:#FFBD44;">Clear the Currently Active Schedule </span>

If you want to clear the current power management schedule for your Mac, use the following command:

<h3 style="color:#ff6600;">sudo pmset repeat cancel</h3>

<p><hr></p>
<p><hr></p>
<p><hr></p>

# <span style="color:#f00;">OSX Catalina and Others
## Set host on Terminal
### Open Terminal and type this: sudo nano /etc/hosts
### type your password and done.

### If u need enable night shift (night light) on OSX Ternimal,<br/>
open terminal prompt command and type this!

### via Homebrew

brew install smudge/smudge/nightlight

## Manual On/Off:

Turn Night Shift on (until tomorrow/sunrise):

nightlight on
## Turn Night Shift off:

nightlight off
## View current on/off status:

nightlight status
## Toggle on or off based on current status:

nightlight toggle

## Controlling the Temperature:
View current temperature setting:

nightlight temp
## Set color temperature (a number from 0 to 100):

nightlight temp 70

## Scheduling:
View the current schedule:

nightlight schedule
## Start schedule from sunset to sunrise:

nightlight schedule start
## Start a custom schedule (in 12 or 24-hour time format):

nightlight schedule 19:45 6:00
nightlight schedule 7:45pm 6am

## Stop the current schedule:

nightlight schedule off

