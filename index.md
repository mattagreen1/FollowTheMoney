# Follow the Money — Privacy Policy

**Last updated:** June 2026

## Summary

This policy covers two apps from the same developer that share one account and one backend: **Follow the Money** (the community bill tracker) and **Hexpansion** (a location-based territory game). Most of this policy describes the bill tracker; a dedicated section near the end, **"Hexpansion,"** describes the extra data Hexpansion collects (most importantly your device location and in-game chat messages).

**One family of apps.** Follow the Money and Hexpansion are part of the same family of apps — made by the same developer and sharing a single account and one backend. Because they're built to work together, this Privacy Policy (and our Terms of Use) applies equally to both, and to any other apps we may add to this family in the future. In short: anything that applies to one applies to all, and the account you create works across all of them.

Your use of both apps is also governed by our **Terms of Use** (https://followthemoney.money/terms), which include an acceptable-use policy with **zero tolerance for objectionable content and abusive behavior**, and explain the in-app tools to report and block other users.

Follow the Money is a community currency-tracking app. To make cross-user tracking work, the app shares the details of each bill you log — including the place you tag it with and any note you add — with other users via Google's Firebase platform. **This sharing is intrinsic to how the app works — it isn't optional.** We collect only what we need to power the app's features. Your bill photo and your account identity (real name, email) are not published. See below for exactly what other users can and can't see.

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
- **Location** — the place you tag the bill with, including its name (e.g. a street address or business name), its ZIP code, and its latitude and longitude
- **Date and time** the bill was logged
- **Optional note** you typed
- **Optional photo** you took (only the photo's filename is uploaded; the photo itself stays on your device — see below)

Everything in a bill's record except the photo is uploaded and is visible to other users on that bill's public journey (see "Who sees what"). Because of that, avoid tagging bills at sensitive precise locations such as your home, and don't put anything private in a note.

When you use the social features:

- **Follow relationships** — which users you follow and who follows you (visible to other users on profile pages)
- **Chase list serial numbers** — the bills you've added to your wishlist (used to notify you when one is logged; the serials themselves are stored alongside your account)
- **Direct messages** — the text content of messages you send to other users, plus the timestamp and conversation participants. Messages are private between the two users in the conversation.
- **Profile privacy preference** — whether your profile is set to public or private
- **Block list** — uids you've blocked. Visible only to you.
- **Reports you submit** — visible only to you and our moderation team.

## What we never collect

- Your real name, mailing address, phone number, or contacts
- **In the bill tracker:** your GPS location is not read automatically — you choose what address to enter for each bill. (Hexpansion is different: it does use your device location while you play — see the Hexpansion section below.)
- Any data from third-party advertising or analytics SDKs (we don't use any)

## What stays on your device

Some data lives only on your phone and never leaves it:

- The photos you take of bills (only the filename is uploaded with the bill; the image itself never leaves your phone)
- Your recently used and starred locations, which the app remembers locally to pre-fill the log form — this saved list is not uploaded

Note: the location and the note you attach to a bill you log are **not** kept private — they are uploaded with that bill and are visible to other users. See "Who sees what" below.

## Where your data is stored

User accounts and bill data are stored in **Google Firebase** (Firebase Authentication, Cloud Firestore), hosted in Google's data centers in the United States. Google processes this data on our behalf as a service provider. Their infrastructure security and data-handling practices are governed by Google's privacy and security commitments.

## Who sees what

- **Other users of the app** can see everything in a bill's record you log: denomination, serial, year, the place you tagged it with (its name, ZIP, and latitude/longitude), the date, and any note you added. They also see your username and display name (unless your profile is set to private — in which case bills you log are attributed to "Anonymous"), your followers/following counts, and direct messages you send to them.
- **You alone** see: your email, your real name, your bill photos, your chase list, your block list, and reports you submit.
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

## Hexpansion

**Hexpansion** is a separate app, but it signs you in with the *same* account as the bill tracker (the same Sign in with Apple identity or email login) and uses the same Google Firebase backend. Everything above about how we store data, who we share it with (no advertisers, no analytics SDKs), and your right to delete your account applies to Hexpansion too. Hexpansion collects some additional data that the bill tracker does not:

- **Account identity** — Hexpansion reuses your existing account: your sign-in email (or Sign in with Apple identifier), your random user ID, and your **username and display name** (shared from your Follow the Money profile). Your username and display name are shown to other players on the leaderboard and next to your chat messages.
- **Your device location** — this is the big difference from the bill tracker. While you play, Hexpansion reads your phone's location (via GPS, at roughly city-block accuracy) to work out which map areas ("hexes") you're close enough to claim or attack. Your distance to a hex is also checked on our server so the rules can't be faked. We use your location only while the app is in use; Hexpansion does not track your location in the background. You can turn this off in iOS Settings → Privacy & Security → Location Services, but Hexpansion's core map features won't work without it. iOS asks your permission before Hexpansion uses your location for the first time.
- **Game play data** — your coin balance, the hexes you own, your territory, buildings and units, your season stats, and any cosmetic items you've unlocked. Coin balances and territory are calculated and written on our server; your coin balance comes from the bills you've logged in the bill tracker. Other players can see which hexes you own and your stats on the leaderboard.
- **In-game chat messages** — Hexpansion has a shared chat where players can talk and coordinate. The messages you send (their text, your username, and the time sent) are stored in Firebase and are visible to all other players in the chat. **Don't post anything private** (passwords, financial details, government ID numbers, your home address) in chat — it is public to other players, not a private message.

**Keeping chat safe.** Because players can post messages and choose usernames that others see, Hexpansion gives you tools to deal with abuse: you can **report** a message or a player, and you can **block** a player so you no longer see their messages. Reports go to the developer for review, and we may remove content or restrict accounts that break the rules. We have zero tolerance for harassment, threats, hate, sexual content involving minors, or other objectionable content or abusive behavior. Your block list and the reports you submit are visible only to you (and to the developer, for moderation).

**Deleting your account from Hexpansion.** You can delete your account from inside Hexpansion (Profile → Delete account). Because the two apps share one account, deleting from Hexpansion deletes the *same* account used by the bill tracker, and removes the data tied to it. If you signed in with Apple, we also revoke that sign-in token. This is permanent.

## Children

The app is not intended for children under 13. We do not knowingly collect data from anyone in that age group. If you believe a child has created an account, contact us and we'll delete it.

## Changes

If we materially change this policy we will update the "Last updated" date and notify you in the app on next launch.

## Contact

Questions, concerns, or want your data deleted? Reach out at [followthemoney.support@gmail.com](mailto:followthemoney.support@gmail.com) or via our [Support page](https://mattagreen1.github.io/FollowTheMoney/support).
