<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.48

- Restores fan control compatibility on Macs where fan target RPM keys only accept writes after manual mode is enabled.
- Keeps fan target RPM write caching, but falls back to one-time type discovery when the cached format is missing or rejected.
- Prevents a failed pre-manual target seed from blocking fan control entirely.
- Avoids showing a battery charging destination with an unknown "-" watt value when macOS does not expose a reliable charging watt reading.
