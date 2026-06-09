<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.53

- Improves fan control compatibility on Macs that reject direct fan mode writes.
- Restores sequential fan target write attempts using `flt`, `fpe2`, `ui16`, and `ui32`.
- Avoids repeatedly retrying fan mode keys that the SMC has already rejected during the helper session.
- Reduces unnecessary fan curve writes when the current target is already close to the desired target.
