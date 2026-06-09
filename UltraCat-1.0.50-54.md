<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.50

- Improves fan target type detection for Macs where SMC target RPM values cannot be read directly.
- Shows fan control failure details in the panel instead of silently resetting the controls.
- Verifies fan curve changes with actual RPM response checks so unsupported fan writes are surfaced.
