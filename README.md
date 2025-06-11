Dactyl Manyform ZMK Config

With ZMK Studio support

## How to update

1. Make your changes to the config/dac_man_5x6.keymap file, commit.
2. Let the build process run
3. Grab the firmware.zip in artifacts
4. Plug left keyboard into USB C connected to computer.
5. Double tap the reset button quickly to turn it into bootloader mode.
6. Drag the left .uf2 file onto the drive that now appears
7. Repeat steps 4-6 for right side.
8. It should now be updated. You may need to tap the reset button once on both halves to sync them again.

## ZMK Studio

I am trying to not use ZMK studio for changes so they stay in code, but modifier key + ) will unlock it for the studio.