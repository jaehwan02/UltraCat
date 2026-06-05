<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.43

- Clarifies the power distribution view when macOS reports adapter input and system load that do not balance cleanly.
- Shows an unknown power path instead of implying the remaining adapter power is battery charging.
- Keeps battery charging watts limited to directly measured battery power rather than estimating it from adapter minus system load.
- Fixes a lock-screen lid-close case where display blanking could keep the Mac awake.
- Makes lock screen sleep take priority over stay-awake lid behavior.
