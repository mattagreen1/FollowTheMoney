# Follow the Money — Privacy Policy

**Last updated:** May 2026

## Summary

Follow the Money is a community currency-tracking app. To make cross-user tracking work, the app shares the metadata of each bill you log with other users via Google's Firebase platform. **This sharing is intrinsic to how the app works — it isn't optional.** We collect only what we need to power the app's features and never share your photos, address, or personal information beyond what's described below.

## What we collect

To create and manage your account:

- **Email address** — used as your sign-in identifier and for password resets. Visible only to you.
- **Password (for email sign-up only)** — never stored by us. Hashed and managed by Firebase Authentication.
- **Apple Authentication identifier (for Sign in with Apple users)** — handled by Apple. We never see your real Apple ID.
- **Username** — a unique, user-chosen public handle (e.g. "matt99"). Visible to other users.
- **Display name** — what you'd like other users to see (e.g. "Matt G."). You can change this any time.
- **A random anonymous user ID** — assigned by Firebase. Used to attribute bills you log to your account.

When you log a bill:

- **Bill identifiers** — denomination, serial number, series year
- **Location** — the ZIP code, latitude, and longitude of the place you picked
- **Date and time** the bill was logged
- **Optional note** you typed (kept private — see below)
- **Optional photo** you took (kept private — see below)

## What we never collect

- Your real name, mailing address, phone number, or contacts
- Your GPS location automatically — you choose what address to enter
- Any data from third-party advertising or analytics SDKs (we don't use any)

## What stays on your device

Some data lives only on your phone and never leaves it:

- The photos you take of bills
- The optional notes you add to a bill
- Your specific street address (only the ZIP and the picked place's coordinates are shared, not the unit number / building name in your friendly display)

## Where your data is stored

User accounts and bill data are stored in **Google Firebase** (Firebase Authentication, Cloud Firestore), hosted in Google's data centers in the United States. Google processes this data on our behalf as a service provider. Their infrastructure security and data-handling practices are governed by Google's privacy and security commitments.

## Who sees what

- **Other users of the app** can see: bill metadata you log (denomination, serial, year, ZIP, latitude/longitude, date), and your username and display name. This is what powers the cross-user matching and Analytics features.
- **You alone** see: your email, your photos, your notes, your specific street-level address.
- **We (the developer)** can technically access all data stored in Firebase to operate and debug the app. We do not sell, share, or use it for advertising.

## Sharing your data

We do not share your data with third parties for advertising, analytics, or marketing. Your data is processed by Google Firebase as our backend infrastructure provider only.

## Your choices

Sharing is a core feature of the app, so it can't be turned off. But you can:

- Choose your username (must be unique; can't be changed once set)
- Edit your display name any time in About → Sharing
- Decide which bills to log — you have to actively log a bill for it to be shared
- Delete any bill at any time from the My Bills tab — that removes it from Firebase
- Sign out at any time from About → Sign out
- Revoke camera or notification permission at any time in iOS Settings
- Request account deletion (which removes all your data) by emailing us — see Contact below

## Children

The app is not intended for children under 13. We do not knowingly collect data from anyone in that age group. If you believe a child has created an account, contact us and we'll delete it.

## Changes

If we materially change this policy we will update the "Last updated" date and notify you in the app on next launch.

## Contact

Questions, concerns, or want your data deleted? Reach out at [mattagreen@gmail.com](mailto:mattagreen@gmail.com) or via our [Support page](https://mattagreen1.github.io/FollowTheMoney/support).
