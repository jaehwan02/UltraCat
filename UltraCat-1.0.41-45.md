<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.41

- Fixes fan curve control occasionally rolling back when the physical fan RPM is slow to report a change.
- Prevents fan curve retries from causing brief stop, full-speed spike, then normal recovery patterns.
- Keeps direct fixed-RPM manual controls verified while allowing fan curves to remain stable.
