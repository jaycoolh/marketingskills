# Anti-AI-Writing Pass (Sweep 8 Detail)

The humanizer pass. Run it last, after the copy is otherwise clean. Read the draft once asking only "what here looks AI-generated?", flag every tell, then rewrite each in plain, direct language. This standard mirrors the Hedera `humanizer` skill.

## Patterns to find and fix

**Significance inflation** — "stands as a testament", "marks a pivotal moment", "in today's evolving landscape", "plays a crucial role". Cut the inflation; state the fact.
- Before: "The release stands as a testament to the team's commitment to performance."
- After: "The release cuts median query time from 400ms to 90ms."

**Superficial "-ing" tails** — "..., highlighting its importance", "..., showcasing the team's commitment", "..., reflecting a broader shift". Delete the tail or make it a real, separate claim.

**Copula avoidance** — "serves as", "stands as", "boasts", "features", "represents". Replace with "is", "are", "has".
- Before: "The dashboard serves as a single source of truth and boasts ten integrations."
- After: "The dashboard is a single source of truth and has ten integrations."

**Promotional filler** — "vibrant", "rich", "nestled", "must-have", "renowned", "world-class". Cut or replace with concrete description.

**Negative parallelisms** — "not just X, it's Y", "it's not only A but also B". Rewrite as a direct positive statement.
- Before: "It's not just a wallet, it's a financial command center."
- After: "The wallet also handles staking and swaps."

**Rule-of-three padding** — forced groups of three ("fast, simple, and powerful") that exist for rhythm, not meaning. Keep only what's true; list two if there are two.

**False ranges** — "from X to Y" where X and Y aren't on a real scale. List the items plainly.

**Em-dash overuse** — long stretches leaning on em dashes for punch. Prefer commas and periods.

**Inline-header vertical lists** — bullets shaped as "**Bolded label:** full sentence". Convert to prose or plain bullets.

**AI vocabulary** — delve, underscore, leverage, garner, intricate, tapestry, testament, foster, robust. Use the "Replace these" table in SKILL.md.

**Curly quotes and stray emojis** — normalize to straight quotes; remove emojis.

**Generic upbeat closers** — "the future is bright", "exciting things ahead", "the possibilities are endless". Replace with a concrete next step or CTA.

**First person** — any "I", "we", "our", "us", "let's" that slipped through. Rewrite per the Brand Voice section.

## Hype and AI-vocabulary replacements

Extends the "Replace these" table in SKILL.md.

| Weak / AI-ism | Strong |
|---------------|--------|
| Revolutionary | New |
| Groundbreaking | New |
| Game-changing | (cut; state the actual change) |
| Delve into | Explore / Cover |
| Underscore | Show |
| Showcase | Show |
| Testament to | (cut; state the fact) |
| Pivotal | Important / Central |
| Vibrant | (cut; describe it concretely) |

## Final check

After rewriting, read once more for rhythm. Sentences should vary in length and sound natural aloud. The copy should pass with no AI tells and no brand-voice violations.
