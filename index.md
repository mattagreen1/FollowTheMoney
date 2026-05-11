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

When you use the social features:

- **Follow relationships** — which users you follow and who follows you (visible to other users on profile pages)
- **Chase list serial numbers** — the bills you've added to your wishlist (used to notify you when one is logged; the serials themselves are stored alongside your account)
- **Direct messages** — the text content of messages you send to other users, plus the timestamp and conversation participants. Messages are private between the two users in the conversation.
- **Profile privacy preference** — whether your profile is set to public or private
- **Block list** — uids you've blocked. Visible only to you.
- **Reports you submit** — visible only to you and our moderation team.

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

- **Other users of the app** can see: bill metadata you log (denomination, serial, year, ZIP, latitude/longitude, date), your username and display name (unless your profile is set to private — in which case bills you log are attributed to "Anonymous"), your followers/following counts, and direct messages you send to them.
- **You alone** see: your email, your photos, your notes, your specific street-level address, your chase list, your block list, and reports you submit.
- **We (the developer)** can technically access all data stored in Firebase to operate the app, investigate moderation reports, and debug issues. We do not sell, share, or use any data for advertising.

## Sharing your data

We do not share your data with third parties for advertising, analytics, or marketing. Your data is processed by Google Firebase as our backend infrastructure provider only.

## Your choices

Sharing is a core feature of the app, so it can't be turned off. But you can:

- Choose your username (must be unique; can't be changed once set)
- Edit your display name any time in About → Sharing
- Set your profile to private (About → Account → "Private profile") to hide your bills' attribution and remove yourself from user search
- Decide which bills to log — you have to actively log a bill for it to be shared
- Delete any bill at any time from the My Bills tab — that removes it from Firebase
- Block any user (from their profile or the conversation menu) to prevent them from messaging you
- Report any user or message that violates our rules
- Sign out at any time from About → Sign out
- Revoke camera or notification permission at any time in iOS Settings
- Request account deletion (which removes all your data) by emailing us — see Contact below

## Messaging

Direct messages are stored on Firebase and visible to:
- The two users participating in the conversation
- The app developer (Matthew Green) only when investigating a moderation report

We don't read messages otherwise. We don't use messages for advertising or analytics. Don't share sensitive personal information (passwords, financial details, government ID numbers) over direct messages. The app warns recipients when an incoming message contains an email address or phone number, since those are common scam vectors.

## Stamp orders

The app offers an optional custom rubber stamp for purchase. When you tap "Order yours" the app opens **Stripe's hosted checkout page** in your browser. The Follow the Money app itself never collects, sees, or stores your payment information.

What Stripe collects from you at checkout:
- Your name
- Your email address
- Your shipping address
- Your payment card details (handled and stored only by Stripe per their PCI-compliant infrastructure)
- The username you'd like engraved on the stamp (entered as a custom field on the checkout page)

What we (the developer) receive after a successful order:
- Your name, email, and shipping address — used solely to ship the stamp to you
- The username you provided — used solely to personalize the engraving
- The amount paid and the order ID

We do not receive or store your payment card number, CVC, or expiration date. Stripe processes the charge on our behalf; their handling of your data is governed by [Stripe's Privacy Policy](https://stripe.com/privacy). Your shipping address and email are kept only as long as needed to fulfill your order, after which they're retained in Stripe's records for the standard period required by tax and accounting regulations.

We don't use stamp-order data for marketing or share it with anyone else.

## Children

The app is not intended for children under 13. We do not knowingly collect data from anyone in that age group. If you believe a child has created an account, contact us and we'll delete it.

## Changes

If we materially change this policy we will update the "Last updated" date and notify you in the app on next launch.

## Contact

Questions, concerns, or want your data deleted? Reach out at [followthemoney.support@gmail.com](mailto:followthemoney.support@gmail.com) or via our [Support page](https://mattagreen1.github.io/FollowTheMoney/support).
