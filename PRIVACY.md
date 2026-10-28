# Privacy and local storage

This notice describes the supplied offline GEMSLAYER game, not a hosting provider's policies. It is a technical description, not a legal-compliance certification.

## What the game stores

GEMSLAYER saves a chosen avatar/pseudonym, game scores, progress, inventory, preferences, daily reward dates and lesson completion in this browser's localStorage under `gemBlastSaga_v2`. Choose a nickname rather than a legal name. Do not put sensitive information into the nickname or save file.

The supplied game has no account/login, analytics, advertising tracker, cloud save, upload endpoint, photo submission or payment processing. Its runtime artwork is embedded. Save import reads a file locally; save export downloads a local JSON file. Neither action uploads progress to a game server. Optional device/browser sharing, if chosen, is controlled by the browser/operating system and the recipient you select.

## Retention and your controls

Progress stays on this device/browser profile and origin until you reset it, clear browser/site data, or the browser removes it. Private-browsing sessions and restricted storage may not retain progress. Settings provides save export, validated import and deliberate reset controls. Keep exported progress separately from a project ZIP. A corrupted or unsupported stored save is quarantined from use and normal autosaves; recovery controls can preserve the raw data before you deliberately start clean or replace it with a valid import.

Storage is **not encrypted by the game**. Anyone or any extension with access to your browser profile, device or exported JSON may be able to read or alter it. Scores are local game data, not tamper-proof records. Export files can contain your nickname and play history; share them deliberately.

## If someone hosts the game

A public host/CDN can receive ordinary HTTP request information such as IP address, browser headers and requested URLs and may retain access logs. That host's privacy, retention, HTTPS and access-control configuration is separate from this offline code. The supplied loopback development server is local HTTP, not a public HTTPS deployment. Review a host's policies before publishing or visiting a hosted copy.

No universal GDPR, CCPA, COPPA, age-rating or other legal-compliance claim is made. No compulsory age gate or collection of birth dates is added simply to play offline. A publisher must assess its actual audience, jurisdiction, hosting and any future data collection before release; adding accounts, analytics, payments, photos or uploads changes these assumptions.
