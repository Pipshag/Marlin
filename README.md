# Marlin 1.1.0-RCBugFix
Currently based on commit 9b5515926a704bff1edb74772b0800cadf8c323d (14/01 2017)

## E3D Big Box Dual Direct (Titan)
Configured with...
- Auto Bed Leveling Bilinear (14 x 9 point mesh based ABL)
- ABL fade to fade out correction gradually, use w/ M420 Z<height>
- ABL grid subdivision for smoother mesh grid (experimential)
- // Lin Advance (calculated preset for PLA)
- Firmware Retract enabled (use M207 and M208 in startup gcode)
- Nozzle Clean (configured for bucket, use with G12 P1)
- Park Mode (configured for bucket, use with G27)
- PID AutoTune menu option
- Babystepping for on the fly adjustments in Z-height
- Dual Extruders and support for M301 E-X PID-values
- LCD knob optimizations

What you should know...
- Baudrate is lowered to 115200.
- This build is intended for Chase Wickerts Dual Titan Direct Drive carriage with the stock IR-sensor probe mounted on to it.
- It works for me, but might break your machine. You really should go through the config and don't do anything rash.

# DISCLAIMER
Don't blame me if anything goes wrong with your machine. This is for E3D BigBox Hybrid v1.1 with Dual Titan Direct Drive carriage (http://www.thingiverse.com/thing:1554356). The configuration assumes you have the IR-sensor mounted to the back of the carriage. Please, be smart and try it thoroughly before actually printing anything.