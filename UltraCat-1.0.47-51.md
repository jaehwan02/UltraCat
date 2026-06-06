<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.47

- Improves fan curve application so UltraCat seeds the target RPM before switching a fan into manual control, reducing brief full-speed spikes.
- Reuses the detected fan target write format for each fan instead of probing multiple formats on every change.
- Rolls all fans back together if a fan curve update cannot be applied cleanly, avoiding one-sided manual fan states.
- Keeps transient fan readings stable while fan control is active so temporary SMC read glitches do not show as sudden 0 RPM states.
