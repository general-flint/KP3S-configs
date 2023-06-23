Please note:
    - Bltouch is included in the configs, but disabled by default. Activating requires editing both the steppers and bltouch config files.
    - Filament sensor is included, but disabled by default. Activating requires editing the filament sensor file.
    - The hotend cooling fan is setup to only startup at a hotend temp of 50 degrees celsius in de fan file, however by default it is wired to an always-on fan connecter. 
      The pin in the config is for the second hotend heater connecter, in order to connect it simply cut and strip the wires and place them in the screwdown terminal.
      It will greatly improve your quality of life. 

Also do run a endstop-offset test for all your axis. https://github.com/rootiest/zippy_guides/blob/main/guides/axis_limits.md
Same goes for the bed screws used in BED_SCREWS_ADJUST. https://www.klipper3d.org/Manual_Level.html#adjusting-bed-leveling-screws
Same of running a pid tune for both bed and hotend. https://www.obico.io/blog/klipper-pid-tuning/

Tested on a KP3S, with a Kingroon KP3 V1.3
