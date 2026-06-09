# Privacy Policy — Structune

*Last updated: 2026-06-09*

---

## Overview

Structune is a Chrome extension that helps you structure prompts using Google's Gemini API. This policy explains what data is handled and how.

---

## Data Collected

Structune does **not** collect, transmit, or store any user data on external servers.

All data is stored **locally in your browser** using `chrome.storage.local`:

| Data | Purpose |
|------|---------|
| Gemini API key | Authenticate requests to the Gemini API |
| Saved prompts (Library) | Persist your saved specs locally |
| Draft input/result | Restore your last session on popup reopen |
| UI settings (language, sort) | Remember your preferences |
| Daily request count | Display the approximate usage badge |

None of this data is transmitted to any server other than Google's Gemini API (see below).

---

## Third-Party API

When you click **Generate**, Structune sends your typed input to:

```
https://generativelanguage.googleapis.com/v1beta/models/gemini-3.1-flash-lite:generateContent
```

This request is made directly from your browser to Google using your own API key. It is subject to [Google's Privacy Policy](https://policies.google.com/privacy) and [Gemini API Terms of Service](https://ai.google.dev/terms).

Structune has no visibility into this request beyond what is returned to your browser.

---

## No Tracking

- No analytics or telemetry
- No crash reporting
- No usage data sent to the extension developer
- No third-party SDKs or scripts

---

## Data Deletion

All locally stored data can be removed at any time by:
- Deleting your API key via Settings → Delete
- Uninstalling the extension (clears all `chrome.storage.local` data)

---

## Contact

If you have questions about this policy, please contact: [niztodream@gmail.com](mailto:niztodream@gmail.com)
