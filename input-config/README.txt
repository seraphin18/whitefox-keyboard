All credit to
https://github.com/boyvanamstel/Whitefox-keyboard-macOS-configuration
https://posts.boy.sh/matt3os-whitefox-keyboard-was-worth-the-wait
https://input.club/configurator-whitefox/

Steps:
0. plug in the keyboard
1. download the zip file
2. Follow instruction to flush firmware:
https://input.club/configurator-setup/
3. For MAC, install home-brew first:
https://brew.sh/
4. install utils
brew install dfu-util
5. Press the flash button (orange led will turn on)
For white fox, hole at the back is the one to use.
Once pressed, backlit led will turn off and keyboard will not be usable.
6. flush firmware(.bin is in the .zip file)
dfu-util -D kiibohd.dfu.bin 
7. Success log looks like firmware-upgrade.log
8. once upgrade is done, led will come back online and keyboard will be responding with new key settings.

Note:
Current bin uses key mapping shown in whitefox-keymap.jpg
If need to change the mapping, use
https://input.club/configurator-whitefox/

