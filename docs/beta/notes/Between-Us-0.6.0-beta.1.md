<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# Between Us 0.6.0 beta 1

This bridge release adds secure in-app updates through Sparkle 2. Existing installations must install this version manually before later releases can update automatically.

- Update checks are optional and use Sparkle's consent prompt.
- Automatic downloads remain off by default.
- Update archives and the appcast are cryptographically signed.
- Messages, Contacts, API keys, model data, and analytics are never included in update requests.
- Requires macOS 14 or later on Apple silicon.
