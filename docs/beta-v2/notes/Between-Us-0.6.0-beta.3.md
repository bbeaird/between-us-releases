<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# Between Us 0.6.0-beta.3 — usability and reliability beta

**Manual installation required for beta.2 and earlier:** download this DMG, quit Between Us, and replace the copy in Applications once. This bridge establishes a new updater signing key and separate signed feed. The old signed feed stays unchanged; Check for Updates in older versions will not offer this bridge. Future releases can update the new bridge through its new feed.

Native window controls now follow Mac conventions: Command-H hides, Command-W and the red button close the window, Command-Q quits, and reopening restores the same window and session after close, hide, or minimize.

Build 5 includes the latest integrated interface and AI-provider improvements: larger, more readable typography; responsive question layouts; copy actions for AI answers and transcripts; Enter to submit and Shift-Enter for a newline; and provider/model selection for Local Gemma, OpenAI, Anthropic, and xAI/Grok, including custom model IDs.

It also adds visible installation and Full Disk Access instructions, clearer local-model and cloud-account requirements, continuous conversation search, keyboard-accessible conversation rows, and drafts that survive changing views. Privacy mode also masks drafts and name searches.

Refresh, provider changes, and model removal remain disabled until an active AI task has finished stopping. Oversized cloud prompts are rejected before transmission and provider errors give recovery instructions. The release publisher checks the public build number and launches the exact mounted candidate using synthetic data before upload.

Requires Apple silicon and macOS 14 or newer. Install the DMG by dragging Between Us into Applications, enable Full Disk Access, quit and reopen, then Connect Messages. Metrics work without an account or model download. Local AI needs at least 32 GB memory (64 GB recommended), an 18.4 GB download, and 22 GB free disk space for setup. Optional cloud questions require your own paid API account and explicit consent.

Messages analysis stays local. Cloud processing is off by default. This update does not enable cloud AI, download a model, or change backup settings. Older versions without a working updater need a manual DMG installation.
