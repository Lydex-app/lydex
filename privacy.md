# Lydex Privacy Policy

_Last updated: 2026-04-15_

This Privacy Policy explains what information the Lydex Android application ("**Lydex**", "**the app**", "**we**", "**our**") handles, and how. Lydex is designed to work primarily offline and to keep your personal data on your own device.

## Summary

- **We do not collect personal data.** Lydex has no analytics, no telemetry, no advertising, and no user accounts.
- **Your library, credentials, and settings stay on your device.** Music metadata, Last.fm tokens, SMB/FTP/WebDAV credentials, and all preferences are stored locally in the app's private storage and are removed when you uninstall the app.
- **Network traffic only happens when you enable a network feature.** The app does not "phone home."

## What Lydex stores on your device

- Scanned music library index and artwork cache.
- Playlists, favorites, playback position, and user preferences.
- Credentials for any remote sources (SMB / FTP / WebDAV) you configure. These are stored in the app's private data directory. They are not transmitted anywhere except directly to the server you configured.
- Last.fm session token (if you signed in to Last.fm). Stored in the app's private data directory.

All of the above is deleted when you uninstall the app or clear the app's data from Android Settings.

## What leaves your device, and when

Lydex only communicates with the network when you deliberately use a feature that requires it:

| Feature | Data sent | Recipient |
|---|---|---|
| Remote library (SMB / FTP / WebDAV) | Authentication and file read requests for your own server | The server you configured |
| Last.fm scrobbling (opt-in) | Track title / artist / album / timestamp for songs you play | Last.fm ([privacy policy](https://www.last.fm/legal/privacy)) |
| Google Play Integrity (Play Store builds only) | Device and app integrity attestation | Google ([privacy policy](https://policies.google.com/privacy)) |
| "Send feedback" / "Send log" in Settings → Support | The message, optional log excerpt, and basic device info (manufacturer / model / Android version / app version). Only sent when you tap the button and confirm in your email app. | Your chosen email app, delivered to `lydex.support@gmail.com` |

We do **not** include any file contents, file paths outside of the app, contact information, location, advertising identifiers, or unique device identifiers in the feedback / log feature. You can review and edit the email body before sending.

## Third-party services

Lydex uses the following third-party services when the corresponding feature is enabled:

- **Last.fm** — for scrobbling, when you sign in. See [Last.fm Privacy Policy](https://www.last.fm/legal/privacy).
- **Google Play Integrity API** — in Google Play Store builds, used solely for anti-tamper and license verification. See [Google Privacy Policy](https://policies.google.com/privacy).

Disabling or not using these features prevents any data from being shared with the corresponding third party.

## Permissions

Lydex requests Android permissions only for the features they enable:

- **Storage / Media access** — to read your music files.
- **Notifications** — to show playback and scan progress notifications.
- **Foreground service** — to keep playback running reliably.
- **Internet** — to reach remote libraries, Last.fm, and (Play build) Google Play Integrity.
- **USB** — to open your USB DAC in exclusive mode.

Lydex does not request location, contacts, camera, microphone, call logs, SMS, or advertising identifiers.

## Children's privacy

Lydex is not directed to children under 13 and does not knowingly collect information from them. Because Lydex does not collect personal data at all, it complies with the U.S. Children's Online Privacy Protection Act (COPPA) and equivalent regulations.

## Data retention

- On-device data is retained until you delete it (by clearing the app's data or uninstalling Lydex).
- Emails you send via "Send feedback" or "Send log" are retained in the support inbox (`lydex.support@gmail.com`) only for as long as needed to respond to your request, typically no more than 12 months, then deleted.

## Your rights

Because Lydex does not maintain any server-side user database, most "data subject" rights (access, deletion, portability) are satisfied simply by uninstalling the app or clearing its data. For information you sent to the support inbox, you may request deletion by emailing `lydex.support@gmail.com`.

## Changes to this policy

If this Privacy Policy changes, the updated version will be published at the same URL with a new "Last updated" date. Material changes will be highlighted in the app's release notes.

## Contact

Questions or concerns about privacy:

**Email:** [lydex.support@gmail.com](mailto:lydex.support@gmail.com)
