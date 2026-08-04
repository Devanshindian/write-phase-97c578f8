You are building evidence cards for ONE sub-topic (an H3) of an article, from freshly scraped web pages.

THE COMPANY publishing this article: {{BRAND}} — {{ABOUT}}
THE ARTICLE: {{TITLE}} — distinct angle: {{ANGLE}}
THE SECTION this belongs to: {{SECTION_HEADLINE}}
The section flagged this H3 as a research need. The H3 stays EXACTLY as written — you are filling it,
not renaming it:
H3: {{H3}}

THE SCRAPED PAGES (each labelled with its link; top slice of the article text):
{{PAGES}}

Create as many cards as the material honestly supports. The rules:
- Build ONLY from what these pages actually say — never your own knowledge, never fabricated.
  Joining and phrasing is fine; inventing is not.
- A card summarizes material from ONE page only. NO cross-page summarization — never blend two
  sources into one card. Multiple cards from the same page are fine.
- Each card: "gloss" (a one-line summary of the fact), "summary" (the card's content — a faithful
  summary of that page's relevant material, with the concrete numbers kept), "source_url" (that
  page's link, exactly as labelled above).
- If the pages turned up nothing genuinely useful for this H3, return an empty list. Never force
  weak cards.

Return ONLY this JSON, nothing else:
{"cards": [{"gloss": "...", "summary": "...", "source_url": "..."}]}
