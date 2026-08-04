THE COMPANY publishing this article: {{BRAND}} — {{ABOUT}}

You are designing the final structure of an article's BODY — the exact sections, in the exact order
the article will be written.

THE ARTICLE (what we are building):
- Asset title: {{TITLE}}
- Distinct angle (what this article is built to deliver): {{ANGLE}}
- H1: {{H1}}
- What this article IS about: {{WORLD_ABOUT}}
- What this article is NOT about: {{WORLD_NOT_ABOUT}}

THE FORMAT'S REQUIRED SHAPE:
{{FORMAT_STRUCTURE}}

THE OPTIONS this comparison covers (each earns its own section, in the format's order):
{{ENTITIES}}

THE YARDSTICKS every option's section should speak to:
{{YARDSTICKS}}

THE MATERIAL — numbered BOXES. Each box is one sub-topic (an H3) with its evidence cards, shown grouped
under the original section (H2) it came from, with the promises it serves:
{{BOXES}}

THE MAIN RULE — above everything else:
- STAY INSIDE OUR WORLD. Read the NOT ABOUT line above before you place anything. A box can be well
  evidenced, well written and genuinely interesting and still belong to a different field — the same
  words used by a different audience, a neighbouring industry, an academic or clinical use of the term.
  Those boxes are benched, whatever they match. This is the last step that can catch one: after you, it
  becomes a section and gets written.
- The article must speak about ONE main idea from start to finish, and it must READ as one continuous
  piece: each section following naturally from the one before, building a single argument a reader can
  follow top to bottom. A section that pulls the article into a side-topic does not belong in it.
- NEVER pad a section with material that does not belong just to fill it out. A reader feels it
  immediately. If a section cannot be built from material that genuinely fits, leave its boxes empty.

HOW TO BUILD IT — work in this order; each decision feeds the next:
1. The SPINE first: one short paragraph stating what this whole article argues, for whom, and what
   the reader should be able to do at the end. Every section must serve it.
2. Then the sections, in the exact order the final article should read. Give each option ONE
   section of its own; add supporting sections only where the material justifies them. For each one,
   write its JOB before its headline: one or two sentences saying what that section must deliver
   and how it moves the argument forward (including what it depends on or sets up). Then give it a
   real, publishable HEADLINE (an actual article heading, not a label) that names what the job
   describes.
3. Then fill each section with its boxes. Answer only with box numbers shown above — never invent a
   number. Each box belongs in ONE section; two sections must not share the same box. If a section
   genuinely does not have good-enough material among the boxes, do NOT force-fit boxes into it —
   leave its boxes empty.

THE MECHANICS:
- Design the BODY only. The intro, TL;DR, key takeaways, CTA and FAQ are added later by another step —
  do not create them, do not reserve space for them, do not force-feed them.
- If the format's required shape above names a block (a methodology block, an appendix, a definition
  block), you MUST create a section for it. The ONLY blocks another step adds are the intro, TL;DR,
  key takeaways, CTA and FAQ.
- BENCHING: before benching a box, check whether one of your own sections could naturally host it.
  Bench what no section genuinely wants — and bench what would pull the article away from its one
  main idea. Not every box must be used — leave out what the article does not honestly need. But for
  every box you leave out that carries a promise (its "serves:" line names one) or holds hard
  numbers, add one line to "benched" saying why. A box that serves a promise is never dropped
  silently — place it or justify it.
- RESEARCH: if a section lacks the material to be genuinely good, fill its "needs_research" with a
  LIST of the H3s to research — each entry a specific, self-explanatory H3 title for the missing
  sub-topic (put the metric, segment, or timeframe in the title itself where it matters). These H3
  titles are used AS-IS downstream. Research requests must target missing FACTS — data, pricing,
  benchmarks, named studies, real-world figures — never questions about how to SCORE, RANK or WEIGH
  things (that judgment is yours, not the web's). Raise as many as the section genuinely needs. Judge
  QUANTITY as well as fit: a section resting on only one or two thin cards LACKS material, however
  well those cards fit, so raise a marker rather than stretch the little you have.
- {{BRAND}} is the company publishing this article. IF {{BRAND}} is among the options above, it is an
  option like any other: it keeps its own section, it appears in EVERY table, score grid and ranked
  list that covers the other options, judged on the same yardsticks and on the same scale. It may
  score below a rival — say so plainly when the evidence says so. It may never be missing from a
  comparison the others are in: a grid that scores every rival but not the publisher reads as though
  the publisher has something to hide, and costs the article its whole credibility.
  If {{BRAND}} is NOT among the options (this article compares something else entirely — methods,
  approaches, categories, providers we don't sell against), this rule does not apply at all: do not
  insert {{BRAND}} into the comparison.

Return ONLY this JSON, nothing else:
{"spine": "<what this whole article argues, for whom, and what the reader can do at the end>",
 "sections": [{"job": "<what this section must deliver and how it moves the argument>",
               "headline": "<the section's real heading>", "boxes": [<box numbers>],
               "needs_research": ["<H3 title to research>", "<another H3 title>", ...]}],
 "benched": [{"box": <n>, "why": "<one line: why this box is not in the article>"}]}
(needs_research is OPTIONAL — include it only for sections that genuinely need research)
