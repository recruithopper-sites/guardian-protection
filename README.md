# Guardian Protection Website

Recruiting website for Guardian Protection (Sales). Live at https://guardian-protection.sites.recruithopper.com (GitHub Pages). Created with Recruit Hopper on November 25, 2026.

## Editing without a computer setup

Everything can be edited right on GitHub:

1. Open a file (e.g. `index.html`) and click the pencil icon.
2. Make your change and click **Commit changes**.
3. The live site updates automatically in about a minute.

## Common edits

| What | Where |
|---|---|
| Legal name, email, phone, address | `script.js`, the `SITE` block at the top, **and** the same text in `index.html`, `privacy.html` and `terms.html` |
| Page text | `index.html` |
| Colors, fonts, spacing | `styles.css` |
| Logo | `assets/logo.webp` (replace with a file of the same name) |

## 10DLC / A2P SMS compliance

The site includes what carriers and The Campaign Registry check for:

- **Opt-in on the contact form**: two separate, optional, unchecked checkboxes (recruiting/account texts and job alerts/promotional texts) with brand name, frequency, "Msg & data rates may apply", HELP/STOP, and a "not a condition of service" note.
- **Privacy Policy** (`privacy.html`) with the required "no mobile information will be shared with third parties" language.
- **SMS Terms & Conditions** (`terms.html`) with program description, frequency, rates, STOP/HELP, carrier disclaimer and contact info.
- **Business contact info** in the contact section and on both legal pages.

The legal name must match your registered brand exactly: **Guardian Protection LLC**.

Campaign fields you can paste into Telnyx:

- **Website**: https://guardian-protection.sites.recruithopper.com
- **Privacy Policy URL**: https://guardian-protection.sites.recruithopper.com/privacy.html
- **Terms URL**: https://guardian-protection.sites.recruithopper.com/terms.html
- **Opt-in workflow**: Users opt in via the contact form at https://guardian-protection.sites.recruithopper.com/#contact by checking an optional, unchecked SMS consent checkbox and providing their mobile number. Disclosures include brand name, message frequency, msg &amp; data rates, HELP/STOP, and links to the Privacy Policy (https://guardian-protection.sites.recruithopper.com/privacy.html) and Terms (https://guardian-protection.sites.recruithopper.com/terms.html).
- **Sample message 1**: Guardian Protection: Hi {name}, your interview with {company} is confirmed for {date} at {time}. Reply STOP to opt out.
- **Sample message 2**: Guardian Protection: New sales role in {city}: {title}. Interested? Reply YES and we will reach out. Reply STOP to opt out, HELP for help.
- **HELP reply**: Guardian Protection: For help, email mwilson.trfs@gmail.com or call (770) 301-0711. Msg &amp; data rates may apply. Reply STOP to opt out.
- **STOP reply**: Guardian Protection: You have been unsubscribed and will receive no further messages. Reply START to resubscribe.
- **Opt-in confirmation**: Guardian Protection: Thanks for subscribing to recruiting updates. Msg frequency may vary. Msg &amp; data rates may apply. Consent is not a condition of purchase. Reply HELP for help, STOP to opt out.
