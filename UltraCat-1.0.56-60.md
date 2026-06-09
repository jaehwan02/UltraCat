<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.56

- Makes lock screen sleep more reliable when Stay Awake When Closed or idle sleep prevention is enabled.
- Stops UltraCat's display-blanking activity from blocking system sleep while the lid is closed.
- Temporarily restores lid sleep before sleep requests, then restores the user's Stay Awake When Closed setting after wake or unlock.
- Adds lock-state polling and retry logic so a missed lock notification does not leave the Mac awake overnight.
