# Firmware

Klipper machine configuration and G-code macros for the CNC system. Firmware source code and compiled binaries have not been added yet.

## Configuration Files

| File | Purpose |
| --- | --- |
| [config/printer.cfg](config/printer.cfg) | Five-axis machine configuration with stepper settings, homing macros, valve control, and fan control. Includes `mainsail.cfg`. |
| [config/mainsail.cfg](config/mainsail.cfg) | Mainsail client macros for pause, resume, cancellation, and related functions. |
| [config/bio-ejector-5x-cnc-klipper.cfg](config/bio-ejector-5x-cnc-klipper.cfg) | Example CNC and air ejector configuration with an `EJECT` macro. |
| [config/Enderv3_modification.cfg](config/Enderv3_modification.cfg) | Separate Creality Ender 3 configuration. |

Keep `printer.cfg` and `mainsail.cfg` together when copying them to the Klipper configuration directory so that `[include mainsail.cfg]` resolves correctly. The other configuration files are separate configurations, not additional includes for `printer.cfg`.

Configuration values and macros are preserved from the original repository. Machine setup and validation instructions have not been added yet.
