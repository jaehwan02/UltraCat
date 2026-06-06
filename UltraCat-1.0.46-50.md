<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
UltraCat 1.0.46

- Bundles the ccusage token scanner so token usage works without requiring a separate ccusage, npx, or Homebrew installation.
- Scans the same local token usage sources supported by ccusage instead of limiting collection to Claude and Codex logs.
- Shows clear unavailable states when the bundled scanner is missing, cannot read usage, or no local usage records exist.
- Signs the bundled scanner as part of the Developer ID release build.
