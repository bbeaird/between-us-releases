<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# Between Us 0.6.0-beta.1.1 — corrected manual bridge

Build 3 fixes the startup failure in beta.1: the app now resolves its embedded Sparkle update framework from the correct folder. Requires Apple silicon and macOS 14 or newer.

Install this bridge manually by opening the DMG and dragging Between Us to Applications. Older versions have no updater, and the broken beta.1 cannot start. After this corrected bridge is installed, later signed betas can be found through Between Us → Check for Updates.

Messages and Contacts remain local. Optional cloud AI requires explicit provider setup and consent. This update does not download a model or enable cloud AI or backups. Automatic update downloads remain off by default.

The app and DMG are Developer ID signed, notarized and stapled. Release checks include exact framework loading, nested signatures, synthetic startup, single-instance ownership and archive parity. The first real bridge-to-follow-up updater exercise is tracked separately from these packaging checks.
