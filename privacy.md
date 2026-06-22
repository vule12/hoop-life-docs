---
title: Privacy Policy
---

# Privacy Policy — Hoop Life

**Effective date:** 23 June 2026
**App:** Hoop Life — listed on Google Play as "Basketball Career Sim 2026" (Android package `com.vule12.hooplife`)
**Developer contact:** ivulinec12@gmail.com

This is the privacy policy for the mobile application **Hoop Life** (the "App"). It explains what data the App handles and how. We have written it in plain language; if anything is unclear, email the address above.

## Short version

The App is a single-player, offline basketball career simulator. You do **not** need an account, and your game progress stays on your device. The App is **free and supported by ads** served by Google AdMob — optional **rewarded** ads you choose to watch for bonus rewards, plus an occasional **full-screen ad between games**. Optional **in-app purchases** (gem packs and a one-time Remove Ads) are processed by Google Play Billing and RevenueCat; purchase records (transaction ID and product) are stored on your device and with RevenueCat to deliver your entitlements.

Five background services make limited internet requests, and we have kept the rest as privacy-light as possible:

- **Google AdMob** — to show the ads that fund the free App.
- **Google Play Billing & RevenueCat** — to process optional in-app purchases and remember what you have bought.
- **Expo** — to deliver app updates.
- **Sentry** — to send anonymous crash reports so we can fix bugs.
- **Firebase Analytics (Google)** — to collect anonymous, aggregated usage statistics (such as which screens are opened and how long the App is used) so we can see how the game is played and improve it. **You can turn this off any time in Settings → Usage Analytics.**

Details on all five are below.

## What stays on your device

Everything you do in the App — your player, season progress, stats, achievements, settings — is stored **only on your device** using Android's local storage. It is never uploaded to a server we control. Uninstalling the App removes this data.

## Advertising (Google AdMob)

The App is free and is funded by ads provided by **Google AdMob**, a service operated by Google LLC ("Google"). We show two kinds of ads:

- **Rewarded ads** you choose to watch in exchange for in-game bonuses (extra gems, a training point, an energy refill, or a cap increase). These never play unless you tap to start them.
- **Interstitial (full-screen) ads** shown occasionally when leaving the post-game screen — never during gameplay.

We do **not** show banner ads, and we do **not** show ads when the App opens.

To select, deliver, measure, and limit the frequency of these ads, Google and its advertising partners may collect or receive:

- Your device's **Advertising ID (AAID)** — a resettable identifier Android provides specifically for advertising
- **Device information** — model, operating-system version, language, and similar technical details
- Your **IP address** and the **coarse (country/region) location** derived from it
- **Ad-interaction data** — which ads were shown, viewed, or tapped, plus basic delivery diagnostics

Depending on your consent and region (see the next section), ads are either **personalized** (selected using the data above) or **non-personalized** (served without using your Advertising ID to build a profile, based only on coarse context such as country). This data is processed by Google as an independent advertising provider and may be shared with Google's advertising partners; it may be processed on servers in the United States. Google's handling of advertising data is described at <https://policies.google.com/technologies/partner-sites> and <https://policies.google.com/privacy>.

We have configured AdMob to serve ads at a **maximum content rating of "Teen,"** so ad content stays suitable for a general audience.

## Your privacy choices and consent

We use Google's **User Messaging Platform (UMP)** to ask for the consent your region requires before showing personalized ads:

- **In the EEA, UK, and Switzerland (GDPR):** the first time you open the App, a consent form lets you accept or refuse personalized ads and manage individual purposes. Refusing still lets you play — you simply receive **non-personalized** ads.
- **In applicable US states (for example, California under the CPRA):** you are shown a **"Do Not Sell or Share My Personal Information"** choice. Opting out switches you to non-personalized ads.

You can **change your choice at any time** inside the App at **Settings → Ad Privacy Options → Manage**, which re-opens the same consent / "Do Not Sell or Share" form.

You can also **reset or delete your Advertising ID** at any time from your device's **Settings → Privacy → Ads** (the exact wording varies by Android version), which clears the identifier ad providers see.

## App updates (Expo)

The App uses **Expo Application Services (EAS) Updates** to deliver bug fixes and small improvements without forcing you to download a new version from Google Play. When the App starts, it contacts Expo's update server (`u.expo.dev`) to check whether a new JavaScript bundle is available. As part of any HTTPS request on the open internet, that server may automatically receive:

- Your device's **IP address** (a normal part of every internet connection)
- Your **device model and Android version** (so Expo can deliver the correct build)
- Your **app version** and update channel
- An anonymous **install/device identifier** generated by Expo

This information is processed by Expo Inc. under their privacy policy, available at <https://expo.dev/privacy>. We (the App developer) do not see this information and do not store it. We use it solely so that you receive the correct update for your device. You can disable this by going offline — the App is fully playable without an internet connection.

## Crash and error reporting (Sentry)

To find and fix bugs, the App uses **Sentry**, an error-monitoring service operated by Functional Software, Inc. ("Sentry"). When the App hits an unexpected error or crash, it sends Sentry a diagnostic report containing:

- The **error message and a technical stack trace** (which part of the code failed)
- Your **device model and Android version**
- The **app version and build number**
- A randomly generated event identifier

We have deliberately configured Sentry **not** to collect IP addresses or any other personally identifying information (the `sendDefaultPii` option is disabled). These reports contain no name, email, account, location, or game-save content, and cannot be used to identify you.

Sentry processes this data on our behalf solely so we can diagnose stability problems — never for advertising or behavioral tracking. Reports are retained by Sentry for a limited period (Sentry's default is 90 days) and then deleted automatically. Sentry's own privacy policy is at <https://sentry.io/privacy/>, and data may be processed on servers in the United States. Crash reporting requires an internet connection; while offline, no reports are sent.

## Usage analytics (Firebase / Google Analytics for Firebase)

To understand how the App is used in aggregate — so we can fix rough spots and decide what to improve — the App uses **Firebase Analytics** (also called Google Analytics for Firebase), a service operated by Google LLC ("Google"). It records anonymous usage events such as:

- App opens and **session starts**
- **Screen views** (which screens you visit) and how long the App is in use (**engagement time**)
- Standard technical context: **device model, Android version, app version, language, and coarse region** (country/region, derived from your IP address — Google does not store your IP as a precise location)
- A randomly generated **app-instance identifier** that lets us count unique installs without knowing who you are

These reports are **anonymous and aggregated**. They contain **no** name, email, account, contacts, precise location, or any of your game-save content, and we do not use them to identify you or to build an advertising profile. We do not permit Google to use this **analytics** data to personalise ads, and **Firebase Analytics does not use your device's Advertising ID** — that identifier is used only by the advertising system described in "Advertising" above.

**This is optional and you control it.** Analytics are on by default but can be switched off at any time in **Settings → Usage Analytics**; turning it off stops collection immediately.

Google processes this data on our behalf as a service provider, and data may be processed on servers in the United States. Google's handling of Firebase data is described at <https://firebase.google.com/support/privacy> and <https://policies.google.com/privacy>. Event-level analytics data is retained for a limited period (Firebase's default is up to 2 months for event data, with aggregated reports kept longer) and then deleted. Analytics require an internet connection; while offline, nothing is sent.

## In-app purchases (Google Play Billing & RevenueCat)

The App offers optional in-app purchases — **gem packs** and a one-time **Remove Ads**. Payments are handled entirely by **Google Play Billing**; we never see or receive your payment-card details. To deliver what you bought and to let you restore past purchases (for example after reinstalling), the App uses **RevenueCat**, a purchase-management service operated by RevenueCat, Inc. ("RevenueCat").

When you make or restore a purchase, RevenueCat receives and stores:

- The **product purchased**, **transaction identifier**, **purchase token**, price, currency, and store country reported by Google Play
- An **anonymous app-user identifier** that RevenueCat generates so it can remember your purchases without an account
- Standard technical context — **device model, operating-system version, app version** — and the **IP address** that is part of any HTTPS request (used to infer your store country)

RevenueCat processes this data on our behalf as a service provider, solely to deliver and restore your purchases and to help prevent fraud — never for advertising. We do **not** receive your name, email, or card details. This data may be processed on servers in the United States. RevenueCat's privacy policy is at <https://www.revenuecat.com/privacy/>, and Google Play's handling of purchases is covered by Google's policy at <https://policies.google.com/privacy>.

Gem packs are consumable; Remove Ads is a one-time unlock. You can review your purchase history any time in the **Google Play Store app → Payments & subscriptions → Budget & history**. In-app purchases require an internet connection.

## What we do **not** do

- No social login, no user accounts, no email collection.
- No access to your contacts, calendar, photos, precise location, microphone, camera, or files.
- No background tracking — ads load only while you are actively using the App.
- We do **not** sell your personal data for money. Our advertising provider (Google) and its partners receive the advertising data described in "Advertising" above to show and measure ads; in regions where this counts as "selling" or "sharing," you can opt out as described in "Your privacy choices and consent."

## Permissions used

The App requests only these standard Android permissions:

- **`INTERNET`** — required for ads, in-app purchases, EAS Updates, crash reporting, usage analytics (all above), and for loading bundled images.
- **`com.android.vending.BILLING`** — lets the App offer in-app purchases through Google Play Billing.
- **`ACCESS_NETWORK_STATE`** — used to detect whether you are online before attempting an update check.
- **`AD_ID`** (`com.google.android.gms.permission.AD_ID`) — lets Google AdMob access your device's **Advertising ID** to serve and measure ads. You can reset or limit this in Android **Settings → Privacy → Ads**.
- **`VIBRATE`** — used for in-game haptic feedback when you tap buttons or score key moments.

## Children

The App is suitable for general audiences but is **not directed at children under 13**, and it is an ad-supported game rather than a "Designed for Families" title. Ads are filtered to a **maximum "Teen" content rating**. We do not knowingly collect personal information from children; the crash reports and usage analytics described above are anonymous. If you are a parent and have concerns about the ads or anything else, please contact us.

## Data retention and deletion

Your game data (player, save, settings) lives only on your device — uninstalling the App from Android Settings → Apps removes it.

The anonymous crash reports described above are held by Sentry for a limited time (Sentry's default is 90 days) and then deleted automatically. Anonymous Firebase Analytics events are retained by Google for a limited period (Firebase's default is up to 2 months for event-level data) and then deleted; you can stop all future analytics collection at any time via **Settings → Usage Analytics**. Advertising data handled by Google is retained and deleted according to Google's own policies (linked in "Advertising" above); you can reset the Advertising ID ad providers see at any time in Android **Settings → Privacy → Ads**.

Purchase records held by RevenueCat are kept for as long as needed to honour your purchases (for example, to restore Remove Ads) and to meet tax and accounting obligations. To request deletion of your purchase data, email us at the address below and we will pass the request to RevenueCat. Because none of the reports we receive contain an identifier tied to your real-world identity, we cannot look up or single out an individual person's data. If you have any data question, email us and we will help as best we can.

## Changes to this policy

If we make material changes to how the App handles data, we will update this policy and bump the **Effective date** at the top. We encourage you to review this page periodically.

## Contact

Questions, complaints, or data requests: **ivulinec12@gmail.com**
