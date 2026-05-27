<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.22

- Added a repair flow that recreates the fan helper Background Items registration when macOS leaves it disabled.
- Waits for the fan helper to settle after permission repair before showing Background Items guidance again.
- Applies the same repair flow when fan control itself detects a missing or approval-blocked helper.
- Moves the release fan helper to a new Background Items identifier to bypass stale disabled macOS records.
