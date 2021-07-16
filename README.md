# nikon-nis-startup-macro
A Nikon NIS start-up macro that checks some hardware settings.

## Disclaimer
This start-up macro was developed for Nikon Ti2 inverted microscopes.

Other microscope models may require adjustments.

May serve as template for further checks.

Check & test the macro on a microscope without sample / stage inset.

Is only executed on selected and configured alias/shortcut (see usage for details).

## Purpose
When starting the NIS acquisition software a macro that checks sets following settings:
1. Checks if the manual optical zoom has been switched to 1.5x and pops a warning message if so.
2. Lowers the objecte turret to a low stating height
3. Switches to the lowest magnification objective (objective position 0)

## Usage
The start up macro can be configured to be executed across different NIS users and Windows users.
1. Place the macro into the default NIS macro folder, usually: `C:\Program Files\NIS-Elements\Macros`
2. Specify a NIS alias/shortcut to execute the macro. Do this on one in the `Public Desktop` folder for multiple Windows user accounts.
  * In the alias shortcut: `"path_to_nis_ar.exe" -mw "relative_path_to_macro.mac"`
  * Default path example: `"C:\Program Files\NIS-Elements\nis_ar.exe" -mw "Macros\NIS_StartUpMacro.mac"`

