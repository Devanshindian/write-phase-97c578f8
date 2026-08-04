You have the finished article below, already written and already edited into one continuous piece.
Your job is to write what wraps around it: the opening the reader meets first, and the close they
leave on. You are the only writer who has read the whole thing, so you are the right person for it.

THE COMPANY publishing this article: {{BRAND}} — {{ABOUT}}

THE ARTICLE:
- Working H1: {{H1}}
- Distinct angle (what this article is built to deliver): {{ANGLE}}
- What the whole piece argues (the spine): {{SPINE}}
- Primary keyword: {{PRIMARY}}
- Natural variations of it: {{VARIATIONS}}

THE ARTICLE ITSELF, in order:
{{SECTIONS}}

────────────────────────────────────────────────────────────────────────
THE ONE RULE THAT GOVERNS EVERYTHING YOU WRITE HERE:
you have no sources. Every fact, number, name and claim you use must ALREADY be in the article
above. When you carry a fact over, carry its [c…] tag with it, unchanged. If you cannot say
something without inventing, do not say it.

────────────────────────────────────────────────────────────────────────
WRITE THESE, in this order:

1. H1 — return it EXACTLY as given: "{{H1}}". The architect already placed the primary keyword in
   it; it is not yours to change.

2. INTRO — 2 to 4 sentences that sit directly under the H1 with NO heading of their own.

   Start with the ANSWER: the single most useful, most concrete thing this article establishes —
   a number, a verdict, a correction. The first sentence must be a claim the reader can act on,
   not a description of the page they are on.

   BANNED — never open with, or include anywhere in the intro, any sentence that describes the
   article instead of informing the reader. These exact shapes are forbidden:
     "This article breaks down / covers / explores / explains / walks through…"
     "In this article we will…" · "This guide will show you…" · "Below we look at…"
     "Here's everything you need to know about…" · "Let's dive into…"
   If you catch yourself naming the article, delete that sentence and state the fact instead.
   Wrong: "This article breaks down hard versus soft costs by role and industry."
   Right: "Two thirds of what a hire costs never appears on an invoice."

   Work the primary keyword into these sentences naturally — it must appear within the article's
   first 100 words and must not read as though it was inserted.

3. KEY TAKEAWAYS — 3 to 5 bullets, no heading of their own. The concrete, quotable conclusions a
   busy reader would screenshot: real numbers, real thresholds, real verdicts, each carrying its
   [c…] tag. Not a table of contents, not "we will cover X".

4. FAQ — EXACTLY 5 questions, under the heading "Frequently asked questions". Not four, not eight.

   Below are the questions real searchers ask around this topic:
{{PAA}}
   Take from that list, add your own, or both — the list has search demand behind it, so prefer it
   where a question qualifies, but a researched question that fails the test below does not earn a
   slot just for being on the list.

   THE TEST — a question earns one of the five slots only if ALL of these hold. Read (a) and (b)
   together: they are about DIFFERENT things. (a) is about the QUESTION, (b) is about the FACTS you
   answer it with. A good FAQ asks something no heading already covers, and answers it using facts
   the article has already established somewhere.
   a) THE QUESTION is not one the article already answers under a heading. If a section is devoted
      to it, repeating it here wastes a slot — the reader just read it.
   b) THE FACTS in your answer are already in the body. You have no sources; you cannot answer
      beyond what the article establishes. Pulling together facts from two different sections to
      answer a new question is exactly right; restating one section's paragraph is not.
   c) It is specific enough to have a real answer — a number, a threshold, a method, a verdict.
      Skip the vague ("What is X?" when the whole article is about X).
   d) It is the kind of question someone would type into a search box, not phrasing invented to
      sound thorough.
   e) NO TWO of the five may share an answer. If two questions would be answered with the same
      facts, they are one question in two costumes — keep the better-phrased one and find another.

   Answer each in 2 to 4 sentences using only what the article says, tags carried. Rank them: the
   most useful question first. If fewer than 5 questions pass the test, return the ones that do and
   say in dropped_questions why the rest failed — five real questions is the target, never five
   questions padded out to reach the number.

5. CLOSE — 2 to 4 sentences wrapping up what the article established (no new facts), then the
   honest bridge to {{BRAND}} and one clear call to action that fits THIS article and THIS reader.
   What {{BRAND}} offers:
{{FEATURES}}
   - Ground every claim about {{BRAND}} in the list above. Never overclaim, never imply it solves
     something the article showed to be unsolvable.
   - This is a forward CTA, not a recap of the article.
   - Work the primary keyword ("{{PRIMARY}}") into the close where it reads naturally. If it cannot
     go in without sounding bolted on, leave it out and let the close read well.

6. TOUCH-UPS — adding an intro and a close creates two new seams. The article's first section may
   now repeat what your intro just said; its last section may no longer flow into your close. Fix
   that. For any section you touch, return its heading and its corrected prose, using ONLY these
   moves: cut a repetition, shorten a re-introduction to a reference, add or adjust one linking
   sentence. Never add a fact. Never change a heading. Leave every other section alone — most
   articles need one or two touch-ups, not ten.

────────────────────────────────────────────────────────────────────────
HOW EVERYTHING ABOVE MUST READ — these apply to the intro, the takeaways, every FAQ answer, the
close and any touch-up. This is the first and last thing a reader sees, so hold them TIGHTER here
than in the body, not looser. (Same four rules as write-body.md — edit both files together.)
- ONE IDEA PER SENTENCE. A sentence carries a subject, a verb and one point. When you catch yourself
  joining two points with "which", "while", "and thereby" or a second comma-clause, split it in two.
  A takeaway bullet holding two claims is a failed takeaway — it needs to survive being read alone.
- SAY IT AS A VERB, NOT A NOUN. "Evaluate candidates", not "conduct an evaluation of candidates".
  "Decide", not "make a determination". Turning a verb into a noun doubles the words and drains the
  action out of the sentence.
- EXPLAIN A TERM THE FIRST TIME OR DROP IT. If a phrase would stop a competent reader from outside
  this field — "inter-rater reliability", "adverse impact", "construct validity", "behaviourally
  anchored" — give its meaning in the same words, plainly. The intro and the takeaways reach the
  least committed reader in the piece, so an unexplained term there loses them for good.
- CUT THE QUALIFIER STACK. One qualifier per claim. "A weighted, behaviourally anchored, structured
  rubric" is three stacked in front of one noun; keep the one that carries the meaning and drop the
  rest. Never open a takeaway with a stack — the reader cannot hold three at once, so all three
  land as none.
- WRITE THE PLAIN WORD. Use, not leverage. Help, not facilitate. Start, not commence.

────────────────────────────────────────────────────────────────────────
ON MENTIONING {{BRAND}}: the close is where it belongs. Elsewhere, mention it only where a reader
would genuinely find it useful and the article already supports it. Never insert it to hit a quota —
a forced mention costs more trust than it buys.

Return ONLY this JSON, nothing else:
{"h1": "<the H1, exactly as given above>",
 "intro": "<2-4 sentences>",
 "key_takeaways": ["<bullet>", "..."],
 "faq": [{"question": "<kept or added>", "answer": "<2-4 sentences>", "origin": "researched | added"}],
 "dropped_questions": [{"question": "<the one you dropped>", "why": "<one line>"}],
 "close": "<the closing paragraph ending in the call to action>",
 "touch_ups": [{"heading": "<unchanged heading>", "prose": "<that section's corrected prose>",
                "what": "cut repetition | fixed re-intro | added transition", "why": "<one short line>"}]}
