# Examples and evidence: AI Business Lab, Oct 14

Prepared Oct 13. Every claim below is either **Observed** (it's in a stored, dated answer or listing record I read) or **Suspected** (an explanation we can't prove). Anything marked **Verify in Chrome** still has to be checked by you on the live page before you show it.

## Where the evidence comes from, and what it can't tell you

| Source | What it is | Can we use it? |
|---|---|---|
| **Brevard Visibility Index (BVI)**: your own pipeline, sheets `AiRaw`, `AiBrand`, `AiMentions`, `Maps` | Dated answers from **an AI assistant with web search**. The stored JSON names the model as `claude-opus-5`. It is **not ChatGPT and not Google**. | **Yes, as the primary saved evidence.** Say on stage which tool it was. |
| BrightLocal AI Visibility (ChatGPT / AI Overview / AI Mode) | Saved third-party runs | **No.** You reported these as unreliable, and I found internal contradictions: one run marks a business "mentioned" on AI Overviews in checks that got no AI response. They're kept locally as leads only, not shown. |
| Live ChatGPT / Google AI in a logged-out Chrome window | Fresh captures | **Not done.** This session can't reach google.com, chatgpt.com or bing.com (blocked by the cloud network policy), and it can't control your Chrome. **You run these on Oct 13** (protocol in `04-prep-checklist.md`). |

**Two warnings about the BVI data:**

1. **Your own business's results are contaminated.** In the Oct 5 run for Palm Bay Marketing & SEO (job J032), the AI wrote things like *"this is your own company — the email on this account is @palmbaymarketingseo.com"* and *"Your email is brian.r@palmbaymarketingseo.com."* The pipeline is passing your identity into the AI's context. **The "named in 15 of 16" result for your own business is not a neutral test. Don't show it as proof.** I found explicit identity references only in J032. Other businesses' answers don't mention you, but the same pipeline ran them. See `evidence/excerpts/own-business-contaminated.md`.
2. **The stored discovery answers were cut off at 20,000 characters when saved**, so their cited URLs were lost. The answer text survived. Cited URLs survived only for the "What is [business]?" answers (`evidence/excerpts/cited-urls.md`).

---

## MAIN: Patriot Fire Defense (Melbourne, fire protection). *Needs Patriot's OK to name them.*

**Why this one:** It's your client, you have two dated runs on different dates (variation is visible), and it shows the core lesson clearly. The AI **understands** Patriot correctly, but when a customer asks for Patriot's signature service in Patriot's own city, Patriot **doesn't come up**.

### Discovery (customer question, business not named)

> **"Who should I call for kitchen hood fire suppression in Melbourne, Brevard County, Florida? Name the top three local businesses and say why."**

| Date (UTC) | Patriot named? | Who was named instead |
|---|---|---|
| 2026-09-14 (prompt said "Melbourne, Florida") | **No** | J&D Hood System Services, Piper Fire Protection, Pye-Barker Fire & Safety |
| 2026-10-01 | **No** | McConkey Fire (Melbourne), B & E Fire Safety, Summit Fire & Security |

Observed:
- **Not named in either run**, but the two runs named **six different companies with no overlap**. That's the "answers change" point, live from your own data.
- **Same city, same business, different service:** for *"emergency lighting inspection in Melbourne"* Patriot was recommended **#1 on both dates** (Sep 14: "**1. Patriot Fire Defense** — (321) 751-0777…"; Oct 1: "**1. Patriot Fire Defense (Melbourne)** — the most 'local' of the group"). For *kitchen hood* in Melbourne it was absent both times. That's the slide: **same company, same town, #1 for one service, missing for another.**
- Patriot was also named for kitchen hood suppression in **Titusville** on both dates (#3 on Sep 14, #2 on Oct 1), and for emergency lighting in Titusville, Cocoa and Palm Bay on Oct 1.
- In the BVI mention log, one Oct 1 answer (*fire alarm inspection, Titusville*) **cited patriotfiredefense.com but recommended someone else**. *Verify before using:* only the domain was logged, not the passage.

### Understanding (business named)

> **"What is Patriot Fire Defense Inc in Melbourne, Florida?"** (2026-10-01, verdict: recognised)

Observed in the answer:
- Correct: kitchen hood fire suppression, paint booths, extinguishers, emergency lighting; family-owned; started 2006; phone (321) 751-0777; patriotfiredefense.com.
- Address given: **6963 W. NASA Blvd., Ste. 55, Melbourne 32904**. The answer also says **BBB lists 2 locations, one in Melbourne 32934.**
- Your own BVI listing match recorded the Google Business Profile address as **"6963 Old Nasa Blvd, Melbourne, FL 32904"**.
- The AI consulted an Alignable page under **west-melbourne-fl** (see `cited-urls.md`).

So the public record shows up to **three location descriptions**: W NASA Blvd Ste 55, Old Nasa Blvd, a second BBB location (32934), and a West Melbourne directory page. **Verify in Chrome:** the GBP address, the BBB profile's two locations, and the Alignable page. If they really differ, that's your on-screen "location inconsistency." If they're the same place written two ways, say so and drop the point.

### What to show on screen
1. The Oct 1 discovery answer (excerpt file). Point at the three names and the absence of Patriot.
2. The Sep 14 answer side by side: same question, different three names.
3. The understanding answer's **Basics** block and the "BBB lists 2 locations" sentence.
4. Live (if verified): patriotfiredefense.com's kitchen hood service page, and the GBP address next to the BBB address.

### Teaching point
"AI knows exactly who Patriot is. Ask for Patriot by name and it gets the services right. Ask the way a customer does, for kitchen hood suppression in Melbourne, and Patriot didn't come up on either date. Being *known* and being *recommended* are different tests."

### One practical improvement (only if it holds up)
- **Verify in Chrome** whether patriotfiredefense.com has a page focused on *kitchen hood fire suppression in Melbourne* (the stored answers cite extinguisher and general service pages; I couldn't load the site from here). If there's no dedicated page, the improvement is **one plain page that answers "kitchen hood fire suppression in Melbourne"**: who it's for, inspection frequency, licensing, service area.
- If the addresses really conflict, **make the address identical everywhere** (GBP, BBB, website, Yelp, Alignable).

**Suspected, not proven:** that the missing page or the address variants *cause* the omission. Say "this is what we can see," never "this is why."

### If the live result differs
- **Patriot shows up live:** "Good. That's the point. Answers vary. On two separate dates it didn't. The question isn't whether you ever appear, it's how often."
- **Different competitors:** "Notice the names changed again. That's three different lists for one question."
- **No AI answer at all:** go straight to the saved screenshots.

---

## CONTRAST: a 50-year-old Melbourne HVAC company (Weather Engineers). *Show anonymized unless they agree.*

This was a visibility-map prospect, not a client. **Don't name them on stage without permission.** On screen, call them "a family-owned Melbourne HVAC company, founded 1976, about 1,400 Google reviews at 4.9" (rating and count from your BVI `Maps` sheet; **verify on their GBP**).

### Understanding: AI knows them in detail
> **"What is Weather Engineers Air Conditioning and Heating in Melbourne, Florida?"** (2026-09-16 and 2026-09-29, both recognised)

Observed: founded 1976, family-owned, services, BBB accredited since 2004, service area, Carrier/Trane dealer details. The answers also volunteered problems on their own:
- **Two addresses**: "812 E Seminole Ave… with a main address listed at 814 W. Eau Gallie Blvd" (Sep 16).
- **Conflicting hours**: "BBB shows Monday–Friday 7:30am–4:30pm, while Yelp lists 8:00 AM–8:00 PM."
- **Duplicate listings**: "two similarly named Yelp listings" (Sep 16) and "two Facebook pages (an older one and a newer…)" (Sep 29).

### Discovery: 0 for 28
- Sep 16: **0 of 12** customer questions (ac tune up / not cooling / replacement / repair × Titusville, Melbourne, Palm Bay).
- Sep 29: **0 of 16** (installation / not cooling / repair / tune up × Titusville, Cocoa, Melbourne, Palm Bay).
- For *"ac repair in Melbourne"* the answers named Able Air, Climate Experts and others (Sep 16), then Climate Experts, Coast Air & Heat and Brevard Cooling and Heating (Sep 29).

### Teaching point
"Fifty years, roughly 1,400 reviews, and the AI could recite their history. It even pointed out their conflicting hours and duplicate pages. But across 28 customer questions on two dates, it never recommended them once."

### Practical improvement (supported by the answers themselves)
Fix what the AI flagged: **one address, one set of hours, merge the duplicate Yelp and Facebook pages.** (Suspected, not proven, that this changes recommendations.)

### If live differs
"One answer can include them. The saved pattern is 0 of 28 across two dates. I'm showing a pattern, not a ranking."

---

## BACKUP: a Titusville HVAC company (Altman's). *Anonymize unless they agree.*

Use this if Patriot says no, or if you want a proximity example.
- **Understanding** (2026-09-15/16): recognised. The AI noted the **name mismatch** itself: *"Altman's Cooling & Heating, LLC is the actual business name — 'Altman's Air Conditioning & Heating Repair' is just a listing variation."* It also flagged a directory filing it under "Home Health Care Service."
- **Discovery** (2026-09-15, 12 questions): the pipeline flagged it "named" **3 times, all in Titusville**, and **0 of 6** in Melbourne and Palm Bay. But reading the text, only **one** of those three was a recommendation (#1 for "air conditioning service in Titusville"). One was an **honorable mention** (installation). One was a **caution**: *"Altman's comes up frequently in Titusville searches but the reviews are mixed — one customer specifically warned others to reconsider using them…"* (BVI `Maps` shows about 2,100 reviews at 4.9; **verify**.)
- **Teaching point:** "Being mentioned isn't the same as being recommended. Read what it says about you, not just whether your name appears. And it noticed the business goes by two names."
- **Caution:** this one includes a negative mention. Show it **anonymized only**, or skip the caution quote.
- **Suspected:** distance, the name variation and recent reviews all play a part. Not provable from this data.

## Not used, and why
- **Palm Bay Marketing & SEO:** identity contamination (see above). Only usable after a fresh **logged-out** capture, and even then, disclose that it's your own business.
- **Jacobs Pressure Cleaning, A Reliable Pool Service, KMR:** only BrightLocal AI data, which you've flagged as unreliable. The BVI has Jacobs (Oct 2: named 2 of 16, both Cocoa), but there's no clearer lesson there than Patriot's.
- **Arrigo Air & Heat:** strong "known, 0 of 22" pattern, but the stored answer says a Yelp listing marks a Rockledge location closed. Too easy to embarrass a prospect.
