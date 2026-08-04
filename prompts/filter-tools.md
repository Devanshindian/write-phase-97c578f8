You are checking which options have enough material to earn their own section in a comparison article.

THE COMPANY publishing this article: {{BRAND}} — {{ABOUT}}

THE OPTIONS:
{{ENTITIES}}

THE YARDSTICKS every option is measured on:
{{YARDSTICKS}}

THE MATERIAL (the planned sections — H2s, their H3s, and the evidence cards under each):
{{PAGES_NOTE}}{{MATERIAL}}

FIRST, name the category in one line: what kind of product is this article's reader buying? Then remove
from consideration any option that is not that kind of product, however well covered it is — a component,
an integration, or a supplier to the category is not a competitor within it.

THEN, for EACH remaining option, go through the cards and SHOW YOUR WORK: list which yardsticks the material
has real information about for THIS option. Then decide: KEEP the option if it has information for at least
{{MIN_PCT}}% of the yardsticks; DROP it otherwise.

Sanity rules:
- RANK CHECK, before you answer: sort every option by its card count. If any option you DROPPED has more
  cards than any option you KEPT, you have misread the material — recount that pair and name the yardstick
  you found for the better-covered one, or move it back into keep.
- {{BRAND}} is the company publishing this article. When it appears among the options, NEVER drop
  it — it always keeps its place, evaluated on the material it has.
- Judge from the cards only; never from your own knowledge of these products.

Return ONLY this JSON, nothing else:
{"category": "<the kind of product the reader is buying>",
 "keep": [{"name": "<option>", "yardsticks_covered": ["<yardstick>", ...]}],
 "dropped": [{"name": "<option>", "yardsticks_covered": ["<yardstick>", ...]}]}
