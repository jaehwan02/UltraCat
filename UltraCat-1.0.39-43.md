<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.39

- Keeps lid-closed display blanking from drifting into the lock screen after idle time.
- Holds an activity assertion while displays are blanked so the Mac stays in the intended closed-lid awake state.
- Avoids treating lid-closed blanking as a user-requested lock-screen sleep.
- Prevents lid-close display blanking from sending the Mac to the lock screen.
- Keeps all connected displays visually blank when the lid is closed and the brightness-to-zero option is enabled.
- Removes the lock-screen stay-awake option so locking the Mac allows it to sleep normally.
- Restores any old display-sleep-disabled setting left by earlier versions.
