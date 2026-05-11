# Privacy Policy — RaceWeek Companion

**Last updated: 2026-05-12**

RaceWeek Companion does not collect, transmit, or share any personal data with any third party, except as described below.

## Data Stored on Your Device

The following preferences are saved locally using Chrome's `storage` API and never leave your device:

| Data             | Purpose                                                                     |
| ---------------- | --------------------------------------------------------------------------- |
| `notifyBefore`   | Alert timing preference (Off / 10 min / 1 hour, multi-select)               |
| `notifySessions` | Per-category alert toggles (Race / Qualifying / Sprint / Practice)          |
| `badgeMode`      | Badge series preference (Soonest / F1 / WEC / MotoGP / Formula E / IndyCar) |
| `badgeSeries`    | Last detected soonest series (used to restore tab on popup open)            |
| `licenseKey`     | Premium license key stored locally for activation status                                     |

## License Verification

When a user manually enters a Premium license key and activates it, the extension sends a verification request to Gumroad's license API.

* Endpoint: `https://api.gumroad.com/v2/licenses/verify`
* Purpose: Verify Premium license validity
* Data sent: License key and product identifier
* No personal information is intentionally collected or stored by the extension during this process

License verification only occurs when the user manually activates a license key.

## What This Extension Does NOT Do

* Collect or transmit personal information
* Access browsing history or browser activity
* Connect to advertising, analytics, or tracking services
* Use third-party libraries or remotely hosted scripts

## Permissions Used

| Permission      | Reason                                                        |
| --------------- | ------------------------------------------------------------- |
| `storage`       | Saves settings and license information locally on your device |
| `alarms`        | Refreshes the D-day badge and schedules notification checks   |
| `notifications` | Displays pre-session alerts when enabled by the user          |

## Changes to This Policy

If this policy is updated, the "Last updated" date above will be revised. Continued use of the extension after any changes constitutes acceptance of the updated policy.
