# Finding: visibility-map AI answers can see your identity

**Not a prerequisite for rehearsing.** The talk uses Patriot's answers (J001, J027), and none of them mention you. This needs checking before you rely on visibility-map AI counts as neutral.

## Observed (from the BVI `AiRaw` sheet, 890 stored discovery answers across 58 jobs)

| Job | Business | Answers referencing your identity | When (UTC) |
|---|---|---|---|
| **J032** | Palm Bay Marketing & SEO | **14 of 16** | 2026-10-05 18:41–18:46 |
| J030 | Jacobs Pressure Cleaning | 1 of 16 | 2026-10-02 20:33 |
| J049 | (not in the Maps sheet) | 1 of 16 | 2026-10-09 15:26 |
| J076 | Critical Gains Fitness | 1 of 16 | 2026-10-13 00:48 |

Example wording: *"this is your own company — the email on this account is @palmbaymarketingseo.com"* (J032); *"your email is on a Palm Bay SEO marketing domain"* (J030); *"My email is attached to a marketing/SEO business in Palm Bay"* (J049).

**Correction to my earlier note:** I said this was limited to J032. It isn't. Three other jobs show it at least once.

## What this does and doesn't show
- **Shows:** the AI step that generated these answers had access to something identifying your account (at least your email domain).
- **Doesn't show:** whether answers *without* an explicit mention were affected. The model may know and simply not say so. That would bias every job, not just these four.
- **Doesn't show:** the cause. It could be account-level memory or profile context in the tool the pipeline calls, a system prompt, or something else.

## What to check (in this order)
1. **The pipeline's AI call:** what it sends besides the question (system prompt, user or profile fields, account memory). The `GridJobs` sheet has `ai_route` and `ai_cli_version` columns. Compare J032/J030/J049/J076 against unaffected jobs.
2. **A controlled re-run:** one J032 question through a clean context with no account, no memory and no profile. Compare it with the stored answer.
3. **Only then** decide whether existing `AI named` counts need re-running.

Until then, present visibility-map AI counts as "from my system's AI check," not as neutral results.
