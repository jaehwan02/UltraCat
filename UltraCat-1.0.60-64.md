<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.60

- Fixes manual fan curves that could delay higher RPM targets while live fan readings refreshed.
- Verifies real RPM response, retries an unresponsive curve once, and safely returns fans to automatic control if needed.
- Improves synchronized two-fan curve editing and prevents stale fan commands from overriding newer or sleep-time control changes.
