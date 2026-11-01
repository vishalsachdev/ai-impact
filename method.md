**[← AI Impact Research](./)**

---

# How This Was Checked

**Last Updated**: 2026-11-01

## Who did this work

This update was researched and written by Claude, an AI model from Anthropic, working as a set of AI agents under Vishal Sachdev's direction. Anthropic's models and reports are subjects of this research, so that conflict is worth keeping in mind. No outside expert reviewed it, and no person has read all 190 findings against their sources. The checks below were done by scripts and by separate AI agents. They reduce errors but do not replace human review.

## What counts as a source

- A number needs a primary source: the company, agency, survey organisation, benchmark owner or paper authors.
- News articles, aggregators and blogs were used only as leads to the primary page.
- A source that could not be opened was left out.
- Each finding gives the source's own date. Pages that show no date say so, with the date they were read.
- A trend appears only if the source states it. Where two measures differ, the page says so.

## What the labels mean

The labels describe where a number comes from, not whether it is true. A vendor-reported number can be accurate, and a survey can be flawed. The definitions are on the [home page](./#how-to-read-this-report).

## What was checked

1. **Quote check:** 190 findings each had a saved quote from the source. A script fetched the sources and matched the quotes. Pages that block scripts were opened in a browser, where the key numbers and phrases were matched.
2. **Spot check:** a separate agent chose 10 claims and one extra claim, opened each source and compared. Ten matched. One was misleading: it joined a subgroup result to the full sample. That claim was corrected.
3. **Full audit:** because of that error, three more agents re-read all 190 claims against the source text around each number. They flagged 44. After a check against the full source, 27 claims were rewritten, and the rest stayed because the full text or the browser check supported them. Most rewrites removed a detail or an inference that the source did not clearly support.
4. **Page review:** a separate agent reviewed the November 2026 text for contradictions and misplaced corrections.
5. **Links and layout:** a script checked every internal link, and every page was tested at phone width with JavaScript off.

## Known limits

- Many results are vendor-reported, and vendors choose what to publish. Vendors also report different scores for the same model.
- Benchmarks change quickly, and several recent ones were revised. Scores across versions are not like for like.
- The audit in step 3 read excerpts around each number, so an error elsewhere in a long source could be missed. Sources that block scripts got a lighter check.
- This is a snapshot with evidence through October 2026, and no update schedule is promised. Check the date before relying on a number.
- Links can change. Text saved from many sources is kept privately for checking and is not published, because the sources hold the copyright.

## What was left out

These were looked for and left out because no open primary source supported them, or for the reason given:

- RAND, EDUCAUSE, OECD Digital Education Outlook 2026 and U.S. Department of Education pages, which blocked access.
- IMO and ICPC 2026 AI results, which appeared only in secondary reports.
- xAI and Meta benchmark scores, which their own pages did not give in text.
- Artificial Analysis's own GDPval-AA pages, which were not opened. Those scores come from vendor pages and are labelled so.
- PwC's $15.7 trillion estimate, whose page could not be opened.
- First-party user counts for Claude and Meta AI, which were not found.

## Corrections

Errors found in the earlier version are in the [corrections log](corrections.md). To report an error, [open a public GitHub issue](https://github.com/vishalsachdev/ai-impact/issues/new?title=Error%20report&body=Page%3A%0AClaim%3A%0ASource%3A%0AWhat%20is%20wrong%3A).
