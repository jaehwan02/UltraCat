<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.20

- Added a repair flow that recreates the fan helper Background Items registration when macOS leaves it disabled.
- Waits for the fan helper to settle after permission repair before showing Background Items guidance again.
- Keeps the permission repair UI visible even when fan discovery is unavailable.
