# Prep checklist, in order of importance

Note: you wrote "tomorrow is October 13." The session clock says **today is Oct 13**, so this list is for today, with the talk tomorrow morning.

## Blockers that need you
1. **Patriot Fire Defense: OK to name them on stage?** They're the main example. If not, the anonymized HVAC contrast becomes the main example and the outline still works.
2. **Visibility-map AI checks include your identity.** Answers in your own map (J032) say *"the email on this account is @palmbaymarketingseo.com."* That doesn't block the talk (we don't use J032), but **every map you offer the room runs through that pipeline.** Before sending maps to attendees, confirm the AI step no longer receives your account or email context.
3. **The map intake URL and the GHL form** for the resource page (two placeholders in `03-resource-page.html`).

## 1 · Evidence (do first)
- [ ] **Run the live captures in Chrome**, logged out (protocol below). Patriot first, then the contrast company.
- [ ] **Verify Patriot's location record** in Chrome:
  - [ ] Google Business Profile address: "Old Nasa Blvd" or "W NASA Blvd Ste 55"?
  - [ ] BBB profile: does it really list 2 locations (one in 32934)? https://www.bbb.org/us/fl/melbourne/profile/fire-protection-contractor/patriot-fire-defense-inc-0733-202532492
  - [ ] Alignable page (filed under West Melbourne): https://www.alignable.com/west-melbourne-fl/patriot-fire-defense-inc
  - [ ] Is there a patriotfiredefense.com page specifically about **kitchen hood fire suppression**? Note the URL and its heading.
  - If the addresses are just two spellings of the same place, **drop the address beat**.
- [ ] **Verify the contrast company's** review count (about 1,400), founding year (1976), and whether the two addresses, two Facebook pages and two Yelp listings really exist (URLs in `evidence/excerpts/cited-urls.md`).
- [ ] **Save every page you'll show** as a PDF (Ctrl+P → Save as PDF) into the same folder as `offline-evidence.html`.
- [ ] Copy the `talk-prep/` folder to the laptop. Open `offline-evidence.html` with Wi-Fi **off** to confirm it works.

## 2 · Digital follow-up (smallest setup)
- [ ] **One WordPress page** on your existing site (suggested `/ai-check`) with the content from `03-resource-page.html`. **It's useful without signing up.**
- [ ] **Resource request** = your existing GHL form (name + email), tag `ai-lab-oct14-resource`, auto-reply with the page link and the two prompts.
- [ ] **Map request** = your existing Brevard Visibility Map intake, linked with `?src=ai-lab-oct14`, so map requests from the talk are tagged separately from resource requests.
- [ ] **Reuse details:** if the intake accepts URL prefill (GHL forms usually support query parameters; **check yours**), link the resource auto-reply's map button with `?name=&email=` filled in so nobody types twice.
- [ ] **QR code** for the page plus a **readable short URL** on the opening and closing slides. Test-scan it from the back of a room.
- [ ] Don't publish until you've reviewed it. Nothing has been published or sent.

## 3 · Rehearse
- [ ] Run the 45-minute outline once against the clock, with the evidence page only.
- [ ] Practice the three "if live differs" lines out loud.
- [ ] Practice the accurate offer sentence. **No turnaround promise:** your fulfillment log shows maps going out anywhere from same day to "still blocked" after 5+ days.

---

## Logged-out capture protocol (Chrome, Oct 13)
This session couldn't reach google.com or chatgpt.com (blocked by the cloud network policy) or control your Chrome. If you want me to drive the browser next time, run the session on your computer (Claude desktop app with Chrome connected), or have the environment's network settings allow those domains.

For each example, in a **fresh Incognito window**, not signed in to anything:
1. **ChatGPT** (chatgpt.com, logged out, search on if offered). Paste the discovery question, then in a **new chat** the understanding question.
2. **Google** (google.com). Same two questions. Capture the AI Overview if one appears, and AI Mode if available logged out.
3. For each answer, **screenshot the full answer plus its sources panel**, with the clock visible. Name the file `platform_example_test_YYYY-MM-DD_HHMM.png`.
4. Open each cited source and **save it as a PDF**.
5. In a text file, write down: the exact prompt, the platform and model if shown, the date and time, whether the business was named, and the cited URLs.
6. **Keep every run**, including ones that don't fit the story. If live results differ from the saved ones, that's material for the "answers change" point.

| Example | Discovery question | Understanding question |
|---|---|---|
| Patriot | Who should I call for kitchen hood fire suppression in Melbourne, Brevard County, Florida? Name the top three local businesses and say why. | What is Patriot Fire Defense Inc in Melbourne, Florida? |
| Patriot (control) | Who should I call for emergency lighting inspection in Melbourne, Brevard County, Florida? Name the top three local businesses and say why. | n/a |
| Contrast | Who should I call for ac repair in Melbourne, Brevard County, Florida? Name the top three local businesses and say why. | What is Weather Engineers Air Conditioning and Heating in Melbourne, Florida? |

## Housekeeping notes (not for the talk)
- **BrightLocal AI Visibility:** confirmed internal contradictions in the Sep 25 Jacobs run (marked "mentioned" on AI Overviews in checks with no AI response). Kept locally only, not used.
- **Your own NAP:** two of your own map's stored answers give different phone numbers for Palm Bay Marketing & SEO, **(321) 389-9324** and **(321) 389-9254**. Worth checking which listings carry which number.
- **BVI data loss:** discovery answers are cut off at 20,000 characters when written to the sheet, so their citation lists are lost. Store the citations separately if you want source checks later.
- **Anonymization is partial:** the contrast slides hide names and phones, but details like "founded 1976" and "Carrier dealer" still identify the business to locals. Trim them, or get permission.
