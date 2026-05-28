<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.26

- Fixes fan curve temperature labeling so the displayed source matches the actual control temperature.
- Reduces duplicate battery telemetry polling and prevents stale power readings from overwriting newer values.
- Avoids repeated permission refreshes during fan control status updates.
- Improves fallback behavior for app metadata, Activity Monitor launch, and the menu bar icon.
