# Aqua Restaurant Group — WhatsApp Guest Communication Proposal

A 16-slide, static HTML presentation prepared by BDGOAL for Aqua Restaurant Group (November 2026).

## Publishing V7 to GitHub Pages

1. Download the `Aqua_WhatsApp_Proposal_Polished_v7_GitHub.zip` file and extract it.
2. Upload the three files (`index.html`, `aqua-whatsapp-v7.html`, `README.md`) to the root of your existing GitHub Pages repository. Replace the previous `index.html`.
3. Confirm that **Settings → Pages** is deploying from the correct branch and root folder.
4. Visit `https://YOUR-USERNAME.github.io/YOUR-REPO/aqua-whatsapp-v7.html` to open the uniquely named V7 version. This provides a clean URL when your existing `index.html` has been cached.
5. You may link clients to the main repository URL once the latest deployment is live.

### V7 update — Blue Tick pricing

- Updated the Blue Tick slide, pricing slide and commercial clarifications to state that verification application support is **included in the package at no additional charge for eligible merchants**.
- Blue Tick eligibility assessment and Meta final approval are still required. The platform subscription is a separate commitment and remains payable regardless of Blue Tick outcome.

### V6 improvements

- **Slide 15 / pricing:** Added an explicit equivalency of **approximately HK$856 per channel per month**, calculated as HK$71,880 / 12 / 7, with HK$5,990/month shown as the group-wide monthly average. The quote remains an **annual commitment**, not a monthly payment offer. Tested the rate breakdown at desktop, short-height laptop, and mobile widths.

### V5 improvements (retained)

- **Slide 06:** Right-side WhatsApp phone is now height-constrained on desktop, leaving room below the frame rule for all on-slide copy; the five interactive guest scenarios and chat scrolling are retained.
- **Slide 11:** API/Webhook cards are height-managed within the slide; the lower beige technical disclaimer is placed underneath the cards without overlapping their borders or captions.
- **Slide 13:** Removed the Chinese subtitle and redesigned the eligibility content with an editorial heading, seven-checkpoint indicator, two clearly labeled groups, and a separate approval disclaimer. Eligibility conditions and Meta-approval caveat remain unchanged.
- **Slide 16:** Decorative circles use truly concentric, anchored rings behind the right-hand panel rather than overflowing the slide frame.
- **Mobile:** Removed pseudo-page rules and absolute decorative footer labels that could intersect long, scrollable content; the persistent navigation bar still indicates slide numbers. Reflowed the slide 03 `07 / 14` statistics and feature separators into clean phone-width layouts.
- **Retained from V4:** The dynamically explained Group-wide / Restaurant Inbox views, responsive automation panels, five guest-response demos, and future reservation system API/Webhook comparison.

### If an old release appears

Use `aqua-whatsapp-v7.html`, or append `?v=20261102-v6` before any `#slide-06` fragment in your page URL. Confirm GitHub Pages has deployed the newest commit. Browser and CDN caches can briefly retain an older index page.

**Important:** A GitHub Pages URL is normally publicly accessible even if the repository is private. Do not upload confidential commercial proposals to a public site without the customer's permission. For restricted client distribution, use a separately authenticated host or an access-controlled sharing service.

## Presentation controls

- Use right/left arrow keys, Page Down/Up, Home/End or bottom navigation buttons.
- On touch devices, swipe horizontally to move between slides.
- Open **Contents** to jump to a slide.
- On slide 6, select any of five guest-response scenarios to watch an illustrative WhatsApp-style exchange with staged messages, a typing indicator and delivery/read marks. Scroll **inside the phone** to review the entire chat; use **↓ Latest** to jump back down. Use **↻ Reset** to clear the scenario.
- On slide 7, switch **Group-wide Inbox** (guest messages across several restaurant numbers) and **Restaurant Inbox** (guest messages filtered to one restaurant). The demo is an illustrative interface, not a live WATI screenshot.
- On slide 10, switch between **Today** and **Future integration** to compare the manual and potential API/Webhook workflows.
- Browser print (`Ctrl/Cmd + P`) uses a slide-by-slide print stylesheet. A desktop browser set to landscape works best.

## Scope and commercial safeguards

The deck is a *proposed* solution and includes HK$71,880/year for year one, seven WhatsApp numbers and fourteen users as supplied by BDGOAL. It does not represent a signed agreement. Usage fees, extras, technical integration and renewal are separate or subject to agreement. Its Blue Tick wording intentionally distinguishes merchant prequalification and submission support from Meta's independent approval decision.

## Critical BDGOAL checks before sending

1. Obtain **written confirmation from WATI** that the quoted 7-number / 14-user arrangement is available at the quoted rate. WATI's public September 2026 help article says additional numbers under one account are only supported on **Business**, not **Pro**; BDGOAL's supplied vendor quote says Pro plus 6 additional numbers.
2. Obtain **written Blue Tick eligibility and guarantee terms** that name the merchant entity/brand/WhatsApp number(s) and address Meta refusal, remedies, and cost responsibility. Public WATI guidance says qualification does **not** guarantee Meta approval.
3. Verify each existing phone number's migration path, chat-history requirements, ownership, display names, contact permissions and staff access requirements.
4. Verify the exact guest WhatsApp opt-in capture and privacy policy for bookings from OpenRice / website.
5. Agree a written statement of work for custom reservation system API/Webhook automation and separate fees; published API availability is not an included integration deliverable.
6. Confirm tax treatment, payment schedule, included setup/support, annual renewal and overage rates in the client quotation / agreement.

## Primary supporting material

- User-provided `Wati Intro & Use Cases.pdf`: collaborative inbox, automation and AI handoff examples (slides 17–22); hospitality journeys (slides 51–59).
- User-provided `20261102_Wati Quote_BDGOAL_Pro Yearly Plan.pdf`: proposed vendor pricing and limits, 7 numbers / 14 users, 20,000 monthly active contacts and 2,000 monthly automation triggers.
- WATI API reference: https://docs.wati.io/reference/introduction
- WATI webhooks introduction: https://docs.wati.io/reference/introduction-1
- WATI multi-number guidance: https://support.wati.io/en/articles/11561205-manage-multiple-whatsapp-numbers-in-a-single-wati-account
- WATI OBA / Blue Tick eligibility guidance: https://support.wati.io/en/articles/11463201-how-to-apply-for-an-official-business-account-blue-tick-on-whatsapp
- Meta WhatsApp Business Messaging Policy: https://whatsappbusiness.com/policy/

## Notes

- The deck contains no external CDNs, proprietary font files or remote image dependencies. All visual mockups are coded in HTML/CSS/SVG.
- Example chats, restaurant labels, typing indicators, delivery/read marks and interfaces are conceptual simulations, not screenshots of an Aqua or WATI live system. Interactivity occurs only in the web presentation; it does not send WhatsApp messages.
- This proposal is intended as a business presentation; have BDGOAL's commercial/legal team review the terms before client use.
