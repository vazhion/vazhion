# Vazhion Privacy Notice

This notice describes how the Vazhion desktop application and optional Vazhion account services handle data. Publish this text at https://vazhion.com/legal/privacy before public sale. This is not legal advice.

**Controller:** Vazhion (replace with your legal entity name and address before public sale).

**Contact:** privacy@vazhion.com

## Desktop data (local)

Vazhion is primarily a local desktop app. It does not upload crash dumps. Crash markers stay on disk.

Typical data stored under your user profile:

| Platform | Location |
|----------|----------|
| Windows | `%APPDATA%\Vazhion` and crash markers in `%LOCALAPPDATA%\Vazhion\crashes` |
| Linux | `$XDG_CONFIG_HOME/vazhion` or `~/.config/vazhion` |
| macOS | `$XDG_CONFIG_HOME/vazhion` or `~/.config/vazhion` |

That folder may contain SSH profiles, optional vault-encrypted secrets, Kubernetes/Docker metadata, editor state, AI history (if used), and cached entitlement snapshots.

## Account services (optional)

If you create a Vazhion account (required for Pro), we process:

- Email address, name, password hash (Argon2id) or magic-link tokens
- Subscription and entitlement status (including Dodo Payments customer/subscription IDs)
- Device fingerprints and device names you activate
- Privacy export/delete request records and consent events
- Optional coarse analytics events only if you consent

We do **not** store payment card numbers. Dodo Payments is Merchant of Record for paid subscriptions.

## What leaves your computer

- Account API calls (auth, entitlements, devices) when you sign in
- AI provider traffic only after you opt in and configure a provider (BYOK)
- SSH/K8s/Docker/VNC connections only to servers you choose

There is no advertising identifier. Optional product analytics are opt-in (especially in the EU).

## Your rights

From the account portal you can export or delete account data. EU/EEA/UK requests target 30 days; CCPA 45 days. See https://vazhion.com/security for subprocessors and security measures.

## Contact

privacy@vazhion.com · security@vazhion.com
