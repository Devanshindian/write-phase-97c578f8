You are choosing which of this article's cited sources become VISIBLE LINKS in the published
version. Every fact in the article already carries a verified citation; showing all of them would
mean {{TOTAL}} links, most pointing at ordinary pages. Your job: pick the ones genuinely worth a
reader's click and the article's endorsement — the published article will link ONLY these, and
its short Sources list will contain ONLY these.

Judge them AGAINST EACH OTHER, not one by one — credibility is relative, and you can see the
whole field:

THE CANDIDATES — every distinct source the article cites (competitor and own-brand domains are
already removed). Each entry: domain · url · how many claims in this article it supports · the
key claims (with a ★ marking claims that carry a load-bearing NUMBER):

{{CANDIDATES}}

────────────────────────────────────────────────────────────────────────
HOW TO CHOOSE — at most {{MAX}} , fewer if fewer deserve it:
- CREDIBILITY FIRST: primary sources beat write-ups about them. Research bodies, government
  data, peer-reviewed journals, recognised industry surveys (SHRM, LinkedIn, Gartner and peers),
  named-methodology studies — up. Anonymous blogs, content-marketing pages, aggregator listicles
  — down. A page that merely repeats another source's number loses to the source itself.
- PREFER THE CRITICAL NUMBERS: a claim carrying a specific, decision-shaping number (★) is
  exactly where a reader wants a reliable link to check. All else equal, the source behind a
  ★ claim beats the source behind prose.
- ONE PER DOMAIN unless a second page from that domain supports a genuinely different set of
  claims (hard max 2 per domain).
- For each kept source, give the anchor: if the prose NAMES the source near its claim ("SHRM's
  2025 survey"), return that exact phrase as "anchor_phrase" so the name itself becomes the link;
  otherwise return null and the citation marker will carry the link. Quote the phrase EXACTLY as
  the body text spells it — same capitalisation, spacing and punctuation, copied from the
  paragraphs, never from a heading. A phrase that does not match character-for-character is thrown
  away by code.

Return ONLY this JSON, nothing else:
{"kept": [{"url": "<the source>",
           "anchor_phrase": "<exact phrase from the prose that names this source, or null>",
           "why": "<one line: why this source earns the endorsement>"}],
 "rejected_examples": [{"url": "<a notable rejection>", "why": "<one line>"}]}
