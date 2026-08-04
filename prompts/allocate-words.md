You are budgeting an article's length across its sections.

THE COMPANY publishing this article: {{BRAND}} — {{ABOUT}}

THE ARTICLE:
- Asset title: {{TITLE}}
- Distinct angle: {{ANGLE}}
- The spine: {{SPINE}}

TOTAL LENGTH TO DISTRIBUTE: {{TARGET}} words (the body only).

THE SECTIONS — each with its job, what it covers, and how much evidence sits behind it:
{{SECTIONS}}

Decide what SHARE of the article each section deserves, as a percentage. Judge by how much the
section matters to the argument above and how much a reader needs from it — NOT by how many
evidence cards it happens to hold. A section with few cards can still be the heart of the piece;
a section with many cards can still deserve a short, tight treatment.

Rules:
- The shares must add up to 100.
- No section below 4 — anything that small should not be its own section.
- Give one short reason per section.

Return ONLY this JSON, nothing else:
{"allocation": [{"section": <index as listed>, "share": <percent>, "why": "<one short line>"}]}
