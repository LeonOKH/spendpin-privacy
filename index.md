# Spendpin Privacy Policy

**Effective date:** 2026-10-24
**Last updated:** 2026-11-02
**Contact:** leonapp2625@gmail.com

Spendpin ("we", "our", "the app") is a personal expense tracker built for users in Malaysia. This policy explains what data the app handles, why, where it goes, and how to delete it.

> **In the current Google Play version (1.0):** there are no accounts or logins, crash reporting (§2.5) is switched off, and the in-app AI features (§2.3) stay off unless you add your own Google Gemini key. Everything you enter and every captured notification stays on your phone (and in your phone's own end-to-end encrypted Google backup, see §4); none of it is sent to us or to anyone else. The app shows ads from **Google AdMob**, which collects device and usage data to serve ads (§2.6a); AdMob never receives your expenses, amounts, notes or notification content. Other network requests are for public exchange rates and the Bank Negara Malaysia OPR (§2.6). The sections below also describe those optional features so this policy stays accurate if a later version turns them on; we will update the date above when that happens.

Spendpin is an independent app. It is **not affiliated with, endorsed by or connected to** Touch 'n Go, Maybank, CIMB, Grab, Shopee, Boost, Public Bank, Ryt Bank or any bank or e-wallet named in this policy; their names are used only to describe which notifications the app can read.

---

## 1. Who is the data controller

Spendpin is published by an individual developer based in Malaysia. For all data-protection questions, contact: **leonapp2625@gmail.com**.

This policy is written to align with both Google Play's User Data policy and the **Personal Data Protection Act 2010 (Malaysia)**.

---

## 2. What data the app handles

### 2.1 Information you provide directly
- **No account:** Spendpin has no sign-up or login. You use it without giving us a name, email address or password.
- **Financial data you enter:** expenses, income, budgets, savings goals, debts, recurring bills, assets, liabilities, categories and notes. These are stored **only on your device** (see §4).
- **Preferences:** currency, theme, colour, language and similar settings, stored on your device.
- **Profile and goal pictures (optional):** a display name, a profile photo or emoji, and photos you add to savings goals. You choose each photo with your phone's photo picker, which gives the app only that one picture, not your gallery. The app keeps a small resized copy **only on your device** (and in a backup file if you make one); it is never uploaded.

### 2.2 Notification content (Android only, opt-in)
If you agree to the in-app disclosure and then grant Notification Access, the app reads notifications **only** from these payment apps, to suggest expenses:
- TNG eWallet (`my.com.tngdigital.ewallet`)
- MAE by Maybank2u (`com.maybank2u.life`; the older Maybank2u app `my.com.maybank2u.m2umobile` is also recognised)
- CIMB OCTO (`com.cimb.cimbocto`; the older CIMB package id `com.cimbmalaysia` is also recognised)
- Grab (`com.grabtaxi.passenger`)
- Shopee / ShopeePay (`com.shopee.my`)
- Boost (`my.com.myboost`)
- MyPB by Public Bank (`com.pbb.mypb`)
- Ryt Bank (`my.rytbank.app`)

Notifications from any other app are ignored. From a supported app's notification the app reads the title and text and extracts the **amount, merchant and time**. All processing happens **on your device**; notification content is **not uploaded** anywhere and is never included in crash reports. A detected payment is saved on your device as a *pending* item (amount, merchant, time and the notification text it came from) and becomes an expense only after **you confirm it** on the Pending screen. You can dismiss pending items at any time.

### 2.3 AI-assisted features (optional)
These features work only if **you add your own Google Gemini API key** (Settings → *Use your own Gemini*). The app has no AI key of its own. With your key, these features send content over an encrypted connection, directly from your phone to **Google (Gemini API)**, under your own key and Google's terms for it. We never receive your key or this content. On Google's free plan, Google may use what is sent to improve its products.

Your key is stored on your phone encrypted with a key held in the Android Keystore, is never included in any backup, and is deleted when you tap *Remove key* or *Delete My Data*. It is sent only to Google, in a request header.

With your key, these features send:
- **Quick-add parsing:** the text you type or dictate when you choose to parse it with AI.
- **Receipt scan:** the receipt image you choose to scan.
- **Insights / AI coach:** when you open the Insights screen, summarised figures such as spending totals per category and transaction counts are sent to generate the coach summary; questions you type in the AI chat are sent with similar summaries.
- **Category suggestion:** while you type an expense note or merchant, the text may be sent to Gemini to suggest a category, if no on-device rule or earlier suggestion already matches it.

Without your key these features are off. Notification content is never sent to Gemini: the capture feature does not use AI.

### 2.4 "Ask your own AI" (you choose to share)
On the Insights screen you can tap **Ask your own AI**. Spendpin shows you the exact text first: a summary of the last 30 days (totals by category, your top shops, income and spending limit). Nothing is sent unless you tap **Open in AI app** or **Copy**. Spendpin itself sends nothing: the text goes only to the app you pick (for example ChatGPT or Gemini), under that app's own privacy policy and your own account there.

### 2.4 Voice input
Voice quick-add uses your phone's **system speech recogniser** (on most Android phones this is provided by Google). Spendpin receives only the resulting text. The app does not record or store audio and does not hold the microphone permission.

### 2.5 Crash diagnostics
If crash reporting is enabled in the build, crashes and handled errors are sent to **Sentry**: stack trace, device model, OS version, app version, and an installation identifier generated by Sentry, plus a sample of performance data. Sentry does **not** receive your email address, your expenses or any notification text. If a user id is ever attached, it is an opaque id only, never an email.

### 2.6 Other network requests
To show exchange rates and the Bank Negara Malaysia OPR, the app requests public data from `open.er-api.com` and `api.bnm.gov.my`. These requests contain no personal data beyond what any web request carries (such as your IP address).

### 2.6a Advertising (Google AdMob)
Spendpin is free and shows a small number of ads served by **Google AdMob** (banners on some screens, and occasionally a full-screen ad when you leave a tool such as the loan calculator). To deliver and measure ads and prevent fraud, the AdMob SDK collects: your device's **advertising ID** and app set ID, **IP address** (from which a general location may be estimated), **interactions with ads and the app** (such as ad views and taps, app launches), and **diagnostic data** (such as crash logs and performance). This data goes to Google, which acts under its own policies: https://policies.google.com/technologies/ads.

AdMob does **not** receive any of your financial records, captured notifications, notes or settings; ads are never shown on the notification-capture, Pending review or add-expense screens.

You can reset or delete your advertising ID, or opt out of personalised ads, in Android **Settings → Google → Ads** (or Settings → Privacy → Ads).

### 2.7 What we do NOT collect
- No contacts, location, calendar, SMS or call logs.
- No bank passwords, PINs, OTPs or session tokens.
- No ad network other than Google AdMob (§2.6a); no data brokers.

---

## 3. Why we use each type

| Data type | Purpose | Optional? |
|---|---|---|
| Financial data you enter | Core app functionality, on-device | Required to use the feature |
| Notification content (listed apps only) | Suggest expenses, on-device | Optional, off until you agree and grant access |
| AI feature content | Parse entries, scan receipts, suggest categories, insights | Optional, only after you add your own Gemini key and use these features |
| Crash diagnostics | Find and fix crashes | Enabled only in builds with Sentry configured |

---

## 4. Where your data is stored and who can see it

- **On your device:** your financial data, preferences and pending captured items are stored locally (SQLite and app-private storage). Your financial records are **not** synced to our servers. They are included in your phone's own **Google backup** (Android Auto Backup) so they can be restored when you set up a new phone with the same Google account; that backup is end-to-end encrypted with your phone's screen lock, so neither Google nor we can read it, and it only runs if encryption is available. You can turn backup off in Android Settings → Google → Backup.
- **Google (Gemini API):** only the content described in §2.3, when those features are used.
- **Sentry:** crash diagnostics as described in §2.5.
- **Google (AdMob):** the device and usage data described in §2.6a, for advertising.
- **No one else.** We do not sell your data, and your financial records are never shared with advertisers or data brokers.

### Sub-processors
| Processor | Purpose | Privacy policy |
|---|---|---|
| Google LLC (AdMob) | Advertising | https://policies.google.com/technologies/ads |
| Functional Software Inc. (Sentry) | Crash diagnostics | https://sentry.io/privacy |
| Google LLC (Gemini API) | AI parsing, receipt scan, category suggestion, insights | https://ai.google.dev/gemini-api/terms · https://policies.google.com/privacy |

---

## 5. How long we keep your data

- **On-device data:** until you delete it in the app, clear the app's storage, or uninstall the app.
- **Crash reports:** kept by Sentry according to its data-retention settings, then deleted.
- **Gemini requests:** handled under Google's Gemini API terms.

---

## 6. Your rights and choices

You can, at any time:
- **Back up and restore** everything (expenses, income, budgets, goals, debts, groups and captured payments) with Settings → **Back up everything** and **Restore from backup**. The backup is a file saved wherever you choose (for example Google Drive or Downloads); it is not sent to us. It holds your financial records, so keep it private.
- **Export** your expenses and income to CSV from Settings.
- **Correct** any entry by editing it in the app.
- **Delete your data:** Settings → **Delete My Data** erases everything Spendpin stores on your phone: expenses, income, budgets, goals, captured payments and settings. It cannot be undone, so export to CSV first if you want a copy. Uninstalling the app or clearing its storage also removes it. Data already in your phone's Google backup is removed under Google's backup rules, or by turning backup off.
- **Turn off notification capture:** Android Settings → Notifications → Notification access (device access) → switch Spendpin off.

Under Malaysia's PDPA 2010, you also have the right to lodge a complaint with the Department of Personal Data Protection (https://www.pdp.gov.my).

---

## 7. Children

Spendpin is not directed at children under 13. We do not knowingly collect data from children under 13. If you believe we have, contact leonapp2625@gmail.com and we will delete it.

---

## 8. Changes to this policy

If we make material changes we will update the "Last updated" date above.

---

## 9. Contact

**leonapp2625@gmail.com**

We aim to respond to data requests within 7 business days.
