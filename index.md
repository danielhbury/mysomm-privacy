# MySomm Privacy Policy

**Effective Date:** April 19, 2026
**Last Updated:** May 2, 2026

MySomm ("we," "our," or "the app") is an AI-powered sommelier app that pairs wine and cocktails with your meals. This Privacy Policy explains what information we handle when you use MySomm, how it is used, and who it is shared with.

We've written this policy to be as plain-English as possible. If anything is unclear, contact us at the address at the bottom of this page.

## Who We Are

MySomm is an independently developed mobile application.

- Contact: danielhbury@gmail.com

## Summary (Read This First)

- MySomm does **not require an account** and does **not collect your name, email, contacts, location, or any other identifying information**.
- To generate a pairing, the meal text or menu photo you submit is sent to our AI provider (Anthropic) for processing.
- Your device's IP address is used transiently for rate limiting and is not retained.
- We do not sell, rent, or share your data with advertisers.

## Information We Process

### 1. Meal Input You Provide

When you request a pairing — by typing a dish, pasting a recipe, or photographing a menu — that text or image is sent to our backend server and then forwarded to our AI partner, **Anthropic**, to generate a recommendation. This is the core function of the app.

- **What:** the dish name, recipe text, or photograph you submit.
- **Why:** to produce a pairing suggestion.
- **Retained:** no. We do not store the content of your requests after the pairing is returned.
- **Shared with:** Anthropic (our AI provider). Anthropic's data handling is described at https://www.anthropic.com/legal/privacy.

### 2. IP Address

Our backend uses your device's IP address temporarily to enforce monthly rate limits on the free tier.

- **What:** the IP address of the device making the request.
- **Why:** to count pairings per device per month and prevent abuse.
- **Retained:** no. The IP is used in-memory to check the counter and is not written to persistent storage.
- **Shared with:** no one.

### 3. Anonymous Usage Counter

Your device stores — **locally on your device only** — the number of pairings you have generated in the current month. This is used to show you your remaining free pairings and is never transmitted to us.

### 4. Diagnostic Logs and Error Reporting

Our backend logs server-side errors (e.g. timeouts, failed database queries, unhandled exceptions) to help us keep the service running. To assist with diagnosing crashes and performance issues, error reports are also sent to **Sentry**, a third-party error-monitoring service.

- **What:** the type of error, the URL path that triggered it, the stack trace, and basic system information (server environment, app version).
- **What we exclude:** the text of your meal request, the contents of any photo you submit, your device or user identifiers, and any other personally identifying information. These fields are stripped before the report is sent to Sentry.
- **Why:** to identify and fix bugs and outages quickly.
- **Retained:** error reports are retained by Sentry for 30 days and then automatically deleted.
- **Shared with:** Sentry (sentry.io). Sentry's privacy policy is at https://sentry.io/privacy/.

## What We Do NOT Collect

- Your name, email, phone number, or login credentials
- Your precise or approximate location
- Your contacts, photos library, calendar, or other device data
- Your health, financial, or biometric information
- Tracking identifiers shared with advertisers
- Data from other apps on your device

## Camera and Photo Library

MySomm requests **Camera** and **Photo Library** access so you can photograph or select a restaurant menu, recipe, or dish for pairing. Photos are used only to generate a pairing and are not uploaded anywhere else, saved to our servers, or shared with anyone other than our AI provider (as described above).

You can revoke these permissions at any time in your device settings; core typed-pairing functionality will continue to work.

## Third-Party Services

MySomm uses the following service providers to operate the app:

| Provider | Purpose | Data Processed |
|----------|---------|----------------|
| **Anthropic** | AI pairing engine | Meal text and images you submit |
| **Railway** | Backend hosting | Requests in transit; IP for rate limit |
| **Sentry** | Backend error monitoring | Error type, stack traces, server-side metadata. Excludes meal requests, photos, identifiers. |
| **Apple / Google** | App distribution | Install metrics provided by the platform |

We do not currently use third-party analytics, advertising SDKs, or tracking frameworks.

## Children

MySomm is intended for users **21 years of age or older** because it makes recommendations involving alcoholic beverages. We do not knowingly collect information from anyone under 21. If you believe a minor has used the app, contact us and we will take appropriate action.

## Your Rights

Because MySomm does not retain personal information tied to you, there is generally no stored record to access, correct, or delete. If you have questions about your rights under laws such as the GDPR, CCPA, or similar regulations, contact us and we will respond within 30 days.

You can clear the on-device usage counter at any time by deleting and reinstalling the app.

## Data Security

Requests between the app and our servers are encrypted in transit using HTTPS/TLS. We use industry-standard practices to protect our backend infrastructure. No system is perfectly secure; we encourage you to report any vulnerability you discover to the contact address below.

## Changes to This Policy

If we make material changes to this policy we will update the "Last Updated" date above and, where appropriate, notify users through the app. Your continued use of MySomm after a change indicates you accept the updated policy.

## Contact

Questions, requests, or concerns:

**Email:** danielhbury@gmail.com

---
