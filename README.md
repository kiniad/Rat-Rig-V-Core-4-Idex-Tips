# Beyond Rat-Rig-V-Core-4-Idex
Confuguration upgrades, hints, tricks and experiments for the Rat Rig V-Core4 Idex (400)

INSTALL Orca Slicer-RatRig-V-Core-4-IDEX-Profiles:
1.) Just extract and copy it to your install directory (eg. C:\Program Files\OrcaSlicer) with overwrite the existing files
2.) If you could not choose the IDEX printer, you also have to copy  this files (and overwrite existing) to the configuration folder->system (Help->Show configuration folder)


load_unload_filament.cfg:
- To use with KlipperScreen to load and unload filament.
- Mitigates the "Move out of range" / shutdown issue when loading / unloading the inactive toolhead and the printer is homed.
- Same mitigation if using the unload button from the orbiter filament sensor
- Always uses the active toolhead, if none is specified.

  
