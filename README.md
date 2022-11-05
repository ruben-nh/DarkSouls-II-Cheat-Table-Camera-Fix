# Fix for Camera Control Script on Dark Souls II - SOFTS Cheat Table

Cheat Table derived from [Atvaark's](https://gist.github.com/Atvaark/f308e1d8e00e07106452)


Game version: 1.03
Calibration: 2.02

## Usage for Freecam
* Toggle `Camera Control`
* Right click X/Y/Z and Select Change Hotkeys (or Ctrl+H)
* Click `create hotkey`, select desired hotkey and select `increase/decrease value with:` on the dropdown. Add an int value (e.g. 1), decimal values (e.g. 0.1) give errors when numbers are negative. Hit apply.
* Repeat for all X/Y/Z and increase and decrease value.
* If the camera movement feels mechanical try decreasing the keypoll interval and delay on `Edit>Settings>Hotkeys`. I use 10 Keypoll interval and 15 Delay. Delay should be greater or equal to poll interval. 

## Changes
For anyone interested, the address of the camera position has changed, all I did was find the new one and update it.

Camera Control Script: AOB Scan

Original: `66 0F 7F 49 30 C3 CC CC CC CC CC CC CC CC CC CC CC CC CC 48`
Updated: `66 0F 7F 49 30 C3 90 8B C2 24 07 3C 02 75 71 41 2C 79 D0 48`

## Known Bugs
### NOTE: The testing has been very limited and there may be bugs I am not aware of. Use with caution.
* Sometimes the Camera jumps back to a previous location.
* Disabling the script brings back the camera to its intended place, but enabling the script again sometimes jumps to the location before disabling it.
* Camera position values sometimes change on their own.

## Acknowledgement
[ES] Esto solo lo hice para que Gabrien_ pudiese usarlo en su loregameplay. Vayan a verle es una maravilla [https://www.twitch.tv/gabrien_](https://www.twitch.tv/gabrien_).
