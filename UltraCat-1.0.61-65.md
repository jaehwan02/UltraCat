<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.61

- Temporarily returns fans to automatic control while the Mac is locked or asleep, then restores the active fan curve or per-fan manual RPM settings after unlock.
- Handles overlapping lock and sleep transitions without restoring fan control too early or letting stale commands override the restored state.
- Keeps the current fan control state unchanged when closing the lid only blanks the display and the Mac remains awake.
