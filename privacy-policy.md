Privacy Policy — CSProfile
Last updated: May 2026
Overview
CSProfile is a browser extension that reads public Steam profile data and sends it to a user-configured Discord webhook. We are committed to protecting your privacy.
Data We Collect
CSProfile does not collect, store, transmit or share any personal data with the extension developer or any third party.
The only data stored by the extension is:

Your Discord webhook URL — stored locally in your browser using chrome.storage.local. It never leaves your device except when used to send a message to your own Discord server.
Your extension preferences (which fields to include in the embed) — stored locally in your browser.

Data We Access
The extension reads publicly available information from Steam profile pages you visit:

Display name
Avatar image
SteamID64
CS2 statistics (hours played, kills, K/D, headshot %)
Currently playing game

This data is only used to build the Discord embed at the moment you click "Send". It is never stored or transmitted elsewhere.
Third-Party Services
When you load a Steam profile, the extension contacts the following services:

Cloudflare Workers (workers.dev) — a relay used to fetch CS2 stats, FACEIT and Premier rank from Steam and FACEIT APIs. No personally identifiable information is sent; only the SteamID64 or vanity URL of the profile being viewed.
Steam API — to retrieve public player stats.
FACEIT API — to retrieve public FACEIT rank data.
Discord — only when you click "Send to Discord", the embed payload is sent directly to the webhook URL you configured.

Permissions Justification
PermissionReasonactiveTabTo read the Steam profile page currently openstorageTo save your webhook URL and preferences locallyscriptingTo inject the stats panel into Steam profile pagestabsTo detect whether the active tab is a Steam profile
Children's Privacy
This extension is not directed at children under 13. We do not knowingly collect data from children.
Changes to This Policy
If this policy changes, the updated version will be published at this same URL with a new date.
Contact
If you have any questions, open an issue at the extension's repository or contact the developer directly.
