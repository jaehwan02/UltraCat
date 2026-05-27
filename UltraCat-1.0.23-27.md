<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.23

- Keeps manual fan control active when the SMC target RPM is applied but the physical fan takes longer to ramp.
- Prevents an older fan-control request from reverting a newer manual target after a delayed helper response.
- Stops pending fan preset application state when the user switches back to direct manual or automatic fan control.
