You are placing INTERNAL LINKS into a finished article published by {{BRAND}}. An internal link
lays a link over words that ALREADY exist in the text, pointing to another {{BRAND}} page.

THE TEST for every link — value first, always: a reader who clicks it must land on a page that
gives a genuinely deeper or more practical treatment of the exact thing those words talk about.
The link is a promise ("more on this here"); a link that breaks that promise teaches the reader
to stop clicking. When in doubt, do not link.

THE ARTICLE, in full (so you can judge what each section actually says):

{{ARTICLE}}

THE CANDIDATE PAGES — the only pages you may link to. Each entry: url · title · where it came
from (card = already cited by this article's evidence; research = matched to this topic during
research):

{{CANDIDATES}}

────────────────────────────────────────────────────────────────────────
THE RULES:
- Choose 3 to 5 links in total — no more. Fewer beats forced.
- The anchor is a run of words that ALREADY EXISTS VERBATIM in the section you name. Never add,
  reword or extend the text. 2 to 6 words, describing what the target page is about — never
  "click here", never a whole sentence.
- QUOTE THE ANCHOR EXACTLY as it appears in the BODY TEXT: same capitalisation, same spacing, same
  hyphens, character for character. Copy it from the paragraphs, never from a heading — headings
  are not linkable. An anchor that does not match the body character-for-character is thrown away
  by code, and the link is lost.
- Vary the anchors: no two links may use the same wording.
- At most 2 links in any one paragraph; at most 1 link per section unless two genuinely earn it.
- Include at least ONE product or feature page (a non-blog page) where it fits naturally — and
  skip it if it truly does not fit; never force the product.
- Spread links across the article; do not cluster them all at the top.

Return ONLY this JSON, nothing else:
{"links": [{"section": "<the section heading the anchor sits in, or 'intro'/'close'>",
            "anchor": "<the exact words from the text, verbatim>",
            "url": "<the target>",
            "why": "<one line: what deeper value the reader gets by clicking>"}],
 "rejected": [{"url": "<candidate you did not use>", "why": "<one line>"}]}
