<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.55

- Smooths fan curve ramp-ups so brief low-temperature spikes no longer jump straight to high fan speeds.
- Avoids unsafe first writes to fan target RPM until the SMC target data type has been verified.
- Remembers rejected fan target data types across helper restarts to prevent repeated bad SMC writes.
- Keeps manual fan control active while RPM response is settling instead of immediately reverting.
