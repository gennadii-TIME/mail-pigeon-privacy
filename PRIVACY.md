# Privacy Policy

**Mail Pigeon** (`com.mailpigeon.mac`)  
Effective date: 29 September 2026  
Last updated: 29 September 2026

This Privacy Policy describes how Mail Pigeon (“the App”, “we”) handles information when you use the macOS menu-bar application. The App is designed to work locally on your Mac.

**Public policy URL (for App Store Connect):**

https://github.com/gennadii-TIME/mail-pigeon-privacy/blob/main/PRIVACY.md

## Summary

Mail Pigeon:

- does **not** ask for email usernames or passwords;
- does **not** open, read, upload, or store email messages, subjects, or bodies;
- does **not** use analytics, advertising SDKs, crash reporters, or tracking;
- does **not** sell or share personal data with third parties for marketing;
- reads only the **numeric unread count** from Apple Mail, with your permission;
- stores ordinary app preferences **locally** on your Mac;
- uses the network only for **Apple App Store / StoreKit** purchase and restore.

## Who we are

Mail Pigeon is developed by Gennadii Stepanov.  
Contact for privacy questions: [gennadiistepanov@gmail.com](mailto:gennadiistepanov@gmail.com)

## Information the App accesses

### Apple Mail unread count (Automation)

With your explicit permission in **System Settings → Privacy & Security → Automation → Mail Pigeon → Mail**, the App may send Apple Events to Apple Mail (`com.apple.mail`) to read the combined **unread message count** of your inboxes.

The App uses that number only to detect when new mail arrives and to play the local delivery animation. It does not inspect message content, senders, recipients, or attachments, and it does not send mail.

You can revoke Automation access at any time in System Settings. Without it, automatic flyby based on new mail will not work; other local features (for example Test delivery) may still work.

### Local preferences

The App stores non-sensitive preferences on your Mac using standard `UserDefaults`, for example:

- sound on/off and volume;
- launch at login preference;
- selected delivery character;
- migration flags for older versions.

These preferences stay on your device. The App does not sync them to our servers (the App has no developer backend).

### Purchases (StoreKit / App Store)

Lifetime unlock and Restore Purchases are handled by **Apple** through StoreKit 2. Payment details, Apple ID, and App Store receipts are processed by Apple under Apple’s privacy policy. The App learns only whether you are entitled to the lifetime product (`com.mailpigeon.mac.lifetime`) so it can unlock automatic flyby. The App does not receive your full payment card details.

Network access (`com.apple.security.network.client`) is used for App Store / StoreKit connectivity, not for uploading mail content.

### System features

If you enable **Launch at Login**, macOS may register the App as a login item via system APIs. That preference is controlled by you in the App and in System Settings.

## Information we do not collect

We do not collect:

- email account credentials;
- email message content, subjects, or attachments;
- contacts, calendars, photos, microphone, or camera data;
- precise location;
- advertising identifiers;
- analytics or usage telemetry sent to us;
- crash logs sent to a third-party service operated by us.

## Data sharing

We do not sell personal information. We do not share personal information with third parties for advertising.

Apple may process purchase-related data as the App Store operator. We do not operate a separate analytics or advertising partner integration in the App.

## Data retention

Local preferences remain on your Mac until you clear the App’s stored preferences. Uninstalling the App may not remove macOS preferences automatically. Entitlement state for purchases is maintained by Apple’s App Store systems according to Apple’s policies.

## Children’s privacy

The App is a general-audience utility and is not directed at children under 13. We do not knowingly collect personal information from children.

## Security

The App runs in the macOS App Sandbox. Automation is limited to Apple Mail. Mail content is not transmitted by the App to developer servers because the App does not operate such servers.

No method of electronic storage or local processing is 100% secure; use your Mac’s system security features (passwords, FileVault, etc.) as appropriate.

## Your choices

- Grant or revoke **Automation** access for Mail in System Settings.
- Change sound, volume, launch-at-login, and related options in the App menu.
- Restore or manage purchases through the App Store / the App’s Restore Purchases action.
- Uninstall the App to stop all local processing.

## International users

The App processes data locally on your device. Purchase processing by Apple may involve Apple entities in other countries under Apple’s terms.

## Changes to this policy

We may update this Privacy Policy when the App’s behavior changes. The “Last updated” date at the top will be revised. Material changes relevant to App Store distribution will be reflected at the public policy URL above.

## Contact

Questions about this Privacy Policy:  
**Gennadii Stepanov** — [gennadiistepanov@gmail.com](mailto:gennadiistepanov@gmail.com)

Public repository: [github.com/gennadii-TIME/mail-pigeon-privacy](https://github.com/gennadii-TIME/mail-pigeon-privacy)
