# Revision Notes

Track what you've added, removed, or rewritten here.

## 2026-05-06 — Attenborough × Feynman conversion run (in progress)

Converting OpenStax Business Ethics chapters from nested module-file subfolders into single rewritten markdown files in AxF v1.1 voice.

**Status: COMPLETE. All 11 chapters rewritten with full companion files. All source folders removed after verification.**

Chapters processed:
- 01-why-ethics-matter — 8,428 words — OK (rev 2 with Mark Faris integration case)
- 02-ethics-from-antiquity-to-the-present — 7,301 words — OK
- 03-defining-and-prioritizing-stakeholders — 6,360 words — OK
- 04-three-special-stakeholders-society-the-environment-and-government — 7,582 words — OK
- 05-the-impact-of-culture-and-time-on-business-ethics — 7,205 words — OK
- 06-what-employers-owe-employees — 6,157 words — OK
- 07-what-employees-owe-employers — 6,154 words — OK
- 08-recognizing-and-respecting-the-rights-of-all — 5,874 words — OK
- 09-professions-under-the-microscope — 5,353 words — OK
- 10-changing-work-environments-and-future-trends — 5,011 words — OK
- 11-epilogue-why-ethics-still-matter — 5,041 words — OK

Companion files generated in pantry/, images/, bookmaps/ for all 11 chapters.

Total prose written: ~70,500 words across 11 chapters; ~25,000 words across 33 companion files.

All chapters pass verification (≥3,500 words, zero forbidden phrases, full structural compliance).

### Revisions applied 2026-05-06 (rev 2)

Three flagged items resolved via deep research:

1. **Mark Faris vignette restored as the integration case.** The earlier draft's "Hypothesis Pizza" constructed scenario has been replaced with the documented Faris case (Interlink Communications / Cisco SMARTnet fraud, January 2001–August 2002, 140 fraudulent claims, $400,000+ defrauded, sentenced July 31, 2009 to one year and one day, Duluth Federal Prison Camp, $215,000 restitution, post-release MPV Ethics work with Hank Shea of St. Thomas University). All facts sourced from DOJ filings, Markkula Center for Applied Ethics, and *Twin Cities Business*.
2. **Friedman timeline anchored to milestones.** The earlier "thirty years" framing has been replaced with a milestone-anchored sequence: 1970 essay → 1976 Jensen-Meckling agency theory paper → 1980s-2000s boardroom dominance → 2008 financial crisis as inflection → August 2019 Business Roundtable statement signed by 181 CEOs formally repudiating shareholder primacy.
3. **Tylenol 1982 not used in Ch 01.** The Toyota / Equifax pair already carries the long-game success/failure contrast; Tylenol is reserved for Chapter 4 or Chapter 9 where it fits better.

Source-level notes:
- OpenStax source has no author byline; chapter written in standard AxF v1.1 voice (not first-person-as-Bear).
- All `<figure>` blocks in source are empty placeholders; chapter-original `[FIGURE: ...]` briefs created in the images companion file.

Pending: Chapters 02-11 await voice approval on Ch 01 rev 2.

---

## 2026-05-12 — Completed LLM Exercises pattern (chs 4, 6, 7, 9, 10, 11 added)

The book now has `## LLM Exercises` blocks across all 11 chapters. The existing 5 chapters (1, 2, 3, 5, 8) were left untouched; 6 gap chapters got new blocks in matching format.

| Ch | Topic | 3 exercises added |
|---|---|---|
| 04 | Society/environment/government as stakeholders | Externalities audit on a chosen firm; Volkswagen regulatory-capture mapping; strongest-case Friedman vs strongest-case multi-stakeholder argument |
| 06 | What employers owe employees | Below/at/above-the-floor decision sorting; operative-culture vs harassment-policy gap; specific monitoring practice through privacy/voice/due-process |
| 07 | What employees owe employers | Levandowski-style departure case via the loyalty framework; situations where loyalty cuts against employer preference; whistleblower breaking-point analysis |
| 09 | Professions under the microscope | Founder-culture paradox in tech (Uber/WeWork/Theranos/FTX); asymmetry-of-persuasion in current advertising practices; catastrophic-risk framing on healthcare/insurance pricing |
| 10 | Changing work environments | Cost-shift analysis on flexibility arrangements; automation-displacement transition framework; AI-deployment accountability in high-stakes domain |
| 11 | Epilogue | Slow-erosion sequence-of-decisions mapping; stress-testing a generated code of ethics against the chapter's how-firms-go-wrong framework; LLM-generated mission statement as comparison point (preserves the chapter's own Exercise 11.1 personal mission statement as the closing note) |

**Format choice:** Matched the Ch 02/05/08 modal format (the most consistent across the existing 5): `## LLM Exercises` header, 3 prompts per chapter, `**Exercise N-LLM-N.**` naming, conversational length (no embedded blockquote), ask-AI-to-do-X-and-evaluate-whether-Y pattern. Each exercise pushes the AI toward specificity over genericness — naming concrete companies, decisions, and structural mechanisms rather than abstract categories.

**Positioning:** Inserted before `## Chapter summary` where that section exists (Ch 06, Ch 09); appended at end where it does not (Ch 04, Ch 07, Ch 10); inserted before the closing `## Exercise 11.1` for Ch 11 to preserve the personal-mission-statement assignment as the chapter's emotional close.

**Format-inconsistency follow-up flag:** The existing 5 LLM blocks are NOT internally consistent:
- Ch 01: `Exercise 1.A` through `1.E` — **5 prompts**, letter labels, no embedded blockquote
- Ch 02: `Exercise 2-LLM-1` through `2-LLM-3` — modal format
- Ch 03: `Exercise 3-L1` through `3-L3` — embedded blockquote prompts (different style)
- Ch 05: `Exercise 5-LLM-1` through `5-LLM-3` — modal format
- Ch 08: `Exercise 8-LLM-1` through `8-LLM-3` — modal format
- Ch 04, 06, 07, 09, 10, 11 (this pass): `Exercise N-LLM-N` — modal format

Standardizing fully would require revising Ch 01 (extra prompts) and Ch 03 (different prompt structure). Not done in this pass — those existing blocks are functional and may have been written deliberately for those chapters' specific needs. Flag for future decision.

**Care note for Ch 11:** Inserted the LLM Exercises block BEFORE `## Exercise 11.1` rather than after, to preserve the chapter's intentional close. The original "Write your personal mission statement... That is all." remains the final word.

**No follow-ups flagged beyond the format-standardization note above.**
