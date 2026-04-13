# Privacy Policy for Nebula
Effective Date: January 22, 2026 / Last Updated: April 13, 2026

## Hey. We Don't Collect Anything.

Nebula ("we," "our," or "the Extension") is committed to protecting user privacy. This Privacy Policy explains how we handle information when you use the Nebula Chrome Extension.

1. Information Collection
Nebula is a visual customization tool for Dream Journey AI. It modifies how the interface looks for you, nothing more.
- No personal data collected: We do not collect, store, or transmit any personally identifiable information: no name, email, location, or account data of any kind.
- No external transmission: Your skins, colors, fonts, and settings never leave your device. There is no Nebula server receiving your preferences.
- No analytics or tracking: The extension contains no analytics scripts, ad networks, crash reporters, or telemetry of any kind.
Everything you create in Nebula stays on your device. We never see your customizations, your settings, or anything about how you use the extension.

2. Permissions Explained
Chrome requires that extensions declare every permission they use. Here is exactly what each one does:

`storage`
Uses chrome.storage.local to save your skin configurations, color choices, glow settings, and feature toggles locally in your browser. This data never leaves your device.

`activeTab`
Grants temporary access to the currently visible tab when you click the extension icon. Used only to send your skin settings to the active Dream Journey AI page. Does not grant access to any other tab or to browsing history.

`tabs`
Used for two specific things: finding the active Dream Journey tab to apply your skin to it, and opening Google Fonts in a new tab when you click Browse on a font field. Not used to monitor, read, or record your browsing.

`dreamjourneyai.com`
Allows the extension to inject custom CSS and UI features into the Dream Journey AI interface. Nebula does not read your chat content, your account information, or any data on the page, it only writes visual styles to it.

`api.github.com` & `raw.githubusercontent.com`
Used by the Preset Skins browser to fetch a list of curated skin files from a public GitHub repository. Only public data is accessed. No user data is sent in these requests.

`fonts.googleapis.com` & `fonts.gstatic.com`
When you choose a Google Font, the extension loads the font stylesheet from Google's CDN and the font files from gstatic.com. This is a standard web font request. Google's own privacy policy governs these requests.

3. Third-Party Sharing
We do not sell, trade, share, or transfer any user information to third parties, because we don't have any user information to share.
The only third-party network requests Nebula makes are the ones described above: loading Google Fonts you've chosen, and fetching public skin files from GitHub. No user data is included in either.

4. Your Data, Your Control
All Nebula data is stored locally in your browser using Chrome's secure storage API. You have complete control:
- Export any skin to a .json file at any time from the extension popup
- Delete individual skins from the preset dropdown
- All data is removed when you uninstall the extension
- No account required, no sign-in, no cloud sync
Uninstalling the extension removes all stored data permanently. There is no backup on any external server. Yippie.

5. Changes to This Policy
If this policy changes, the updated version will be posted at this URL with a new Last Updated date. Significant changes will be noted in the Chrome Web Store update notes.
We encourage you to review this page periodically, though we expect changes to be rare given the minimal data footprint of this extension.

6. Contact
If something here is unclear, reach out and we'll clarify it. Contact us!
Daniel Lau — seudan.dev@gmail.com
