# CleverTap Field Guide No.14 - Bulletins Gallery

Single self-contained `index.html` plus a small deploy bundle. All CSS and JS inline. Google Fonts is the only external load. The favicon is embedded (canonical family mark from the AMP Email gallery).

## Deploy (GitHub Pages)
1. Create a repo named `ct-bulletins-gallery` under the `shijunneo-bot` account.
2. Add every file from this bundle to the repo root on the `main` branch.
3. Settings > Pages > Deploy from branch > `main` / root.
4. Live at: https://shijunneo-bot.github.io/ct-bulletins-gallery/

## Bundle
| File | Purpose |
|---|---|
| index.html | The gallery (self-contained; favicon inline) |
| og-image.png | 1200x630 social share card |
| robots.txt | Allows all crawlers incl. AI bots; points to sitemap |
| llms.txt | Plain-text summary for answer engines |
| sitemap.xml | Single-URL sitemap |
| README.md | This file |

## What is inside
- 90 business-event use cases across 15 verticals, six each.
- Each use case: copyable trigger.json payload, 5W1H, and Rich Push, Email, and SMS executions as wireframe and mockup.
- Each card previews its best-fit hero channel (25 push, 32 email, 33 SMS); filter the gallery by channel, vertical, or pattern.
- Grounded mechanics, differentiation, three build-vs-buy lanes, a decision table, measurement, and a 20-question FAQ.

## Grounded vs illustrative
- Product mechanics are grounded in CleverTap docs or flagged "verify with PM".
- Channels (Rich Push, Email, SMS) confirmed via CleverTap's Bulletins product page.
- Every KPI on the page is illustrative. Every brand is fictional. Payload values are strings, per the string-only rule.

## The CleverTap Field Guide Network
- [01 AMP Email](https://shijunneo-bot.github.io/amp-email-gallery/)
- [02 Rich Push](https://shijunneo-bot.github.io/rich-push-gallery/)
- [03 SMS](https://shijunneo-bot.github.io/ct-sms-field-guide/)
- [04 WhatsApp](https://shijunneo-bot.github.io/whatsapp-addon-gallery/)
- [05 Custom HTML In-App](https://shijunneo-bot.github.io/ct-template-gallery/)
- [06 Linked Content](https://shijunneo-bot.github.io/ct-linked-content-gallery/)
- [07 Recommendations](https://shijunneo-bot.github.io/ct-recommendations-gallery/)
- [08 Geofencing](https://shijunneo-bot.github.io/ct-geofencing-gallery/)
- [09 Reminders](https://shijunneo-bot.github.io/ct-reminders-gallery/)
- [10 Promos](https://shijunneo-bot.github.io/ct-promos-gallery/)
- [11 Native Display](https://shijunneo-bot.github.io/ct-native-display-gallery/)
- [12 Product Experiences](https://shijunneo-bot.github.io/ct-product-experiences-gallery/)
- [13 App + Web Inbox](https://shijunneo-bot.github.io/ct-inbox-gallery/)
- [14 Bulletins](https://shijunneo-bot.github.io/ct-bulletins-gallery/)

## Verify-with-PM flags
- Plan and packaging entitlement (the product-release page says Advanced; the features and pricing pages say Content Personalization add-on).
- Whether Liquid Tags, Catalogs, Catalog STP, or Recommendations compile inside the Bulletin body, especially for email.
- Whether a business event can serve as a Journey entry trigger.
- Full analytics depth: revenue, funnel, control-group lift, and the exact conversion attribution window.
- Interplay with global frequency caps, DND hours, and cross-campaign dedupe.
- Whether NextGen Segment Builder support has shipped since the docs' planned note.
- Whether RenderMax applies to Bulletin-dispatched push.

## Open item
The project's hub index.html (root page listing every gallery) is maintained separately; add the Bulletins entry there, and add a Bulletins pill to the family band on the other thirteen galleries (a per-repo edit this bundle does not touch).
