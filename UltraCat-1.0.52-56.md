<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.52

- Applies fan curve changes in a steadier 7-second batch interval.
- Ignores small fan curve target changes under 250 RPM to reduce rapid fan control updates.
- Helps fan curve control feel less twitchy while still responding to meaningful temperature changes.
