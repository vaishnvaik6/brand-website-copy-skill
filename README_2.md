# Brand Website Copy Generator (Claude Skill)

A reusable Claude Skill that turns raw, informal product notes into
consistent, ready-to-publish website copy.

## What it does
Give it a product's name, ingredients, the problem it solves, sizes,
and prices — it returns clean website copy (headline, benefits,
ingredients section, pricing, closing line) in a fixed premium &
minimal brand voice, every time.

## When to use it
- Adding a new product to a website or store page
- Rewriting an existing product description to sound consistent with
  the rest of the site
- Producing marketing copy fast without re-explaining the brand's tone
  in every conversation

## Why this exists
Built for a small hand-made goods business (currently selling an
Ayurvedic hair oil, expanding to more products in the future). Instead
of writing product copy from scratch each time, or repeating brand
instructions in every prompt, this Skill encodes the brand's voice and
non-negotiable content rules (no unverified claims, no medical
promises, consistent structure) once — so it can be reused for every
future product.

## How to use it
1. Provide the required inputs: product name, core problem it solves,
   ingredients, usage/expected timeframe, sizes and prices.
2. The Skill returns copy in a fixed 7-part structure (see `SKILL.md`).
3. Swap in real founder-provided facts only — the Skill will not invent
   ingredients, prices, or results.

See `SKILL.md` for the full instructions and rules, and `example.md`
for a worked example using a real product.
