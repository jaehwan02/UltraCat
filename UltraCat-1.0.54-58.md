<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.54

- Fixes manual fan control on M4 Pro Macs that start in SMC fan mode 3.
- Uses the `Ftst` unlock sequence before retrying rejected fan mode writes.
- Keeps `Ftst` enabled while manual fans are active, then resets it when fan control returns to automatic.
- Increases fan helper response timeout so longer M4 unlock attempts can complete.
