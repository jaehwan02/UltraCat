<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.68

- Updates the bundled ccusage scanner to 20.0.22 and applies its latest usage and cost calculation rules, including Codex cache-write tokens, GPT-6 Astra fast pricing, GPT Reserve/Luna mapping, and refreshed model pricing data.
- Rolls back the external-display sleep feature and restores the pre-1.0.64 lid/display sleep behavior.
- Fixes severely inflated Codex token and cost totals caused by replayed usage records being counted repeatedly.
- Updates the ccusage open-source link to its current official repository.
- English language mode now shows token costs in USD without the KRW conversion.
- Fixes manual fan control reverting after delayed SMC readback by retrying readback and separating accepted writes from actual RPM response verification.
