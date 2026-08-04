You are finding the LIST ITEMS of a listicle — the concrete things the reader came for.

THE COMPANY publishing this article: {{BRAND}} — {{ABOUT}}

THE ARTICLE (what we are building):
- Asset title: {{TITLE}}
- Distinct angle (what this article is built to deliver): {{ANGLE}}

THE MATERIAL (the planned sections — H2s, their H3s, and the evidence cards under each):
{{MATERIAL}}

The items come from the CONTENT of the material, not from brands or publishers. Examples by topic:
- "strategic interview questions" -> each individual QUESTION (e.g. "Tell me about a time you resolved a conflict")
- "common hiring mistakes"        -> each MISTAKE
- "best assessment tools"         -> each TOOL

Rules:
- Return at most {{MAX_ITEMS}} items. A shorter list that is fully written beats a longer list of stubs.
- Two items a reader would answer the same way are ONE item. Merge near-duplicates (same question in
  different wording, tense, or seniority) and keep the clearest phrasing.
- Keep an item ONLY if the material contains evidence about THAT item specifically — an example, a standard,
  a scoring note, or a fact naming it. An item mentioned only in passing inside a general box does not qualify.
- Every item must serve the article's angle above. Drop items that belong to a neighbouring topic (a different
  role, a different stage of hiring) even when the material mentions them.
- Each item must be a complete, usable prompt as it would be said aloud — never a fragment or a stub.
- Pick the true grain the article promises (individual questions, not question categories).
- Only items the material actually supports. Never invent one.
- Do NOT list research firms, authors, or sources (DDI, SHRM, OPM) — those are sources, not list items.
- Return each with a rough count of the cards supporting it.

Return ONLY this JSON, nothing else:
{"entities": [{"name": "<the list item>", "count": <supporting cards>}]}
