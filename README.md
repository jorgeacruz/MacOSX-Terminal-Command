# How to enable night shift in terminal.
<br/>
<img src="https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0" />

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
