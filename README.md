# Probability Gym

Randomized probability practice for VJ (simple probability, complements with
the prime-mark notation, likelihood words, and compound events — independent
with replacement vs. dependent without, including three-draw challenges).
Every quiz is 13 freshly generated problems: random bags of marbles/Skittles
(drawn as colored dots), number-cube and A–H spinner questions (spinner drawn
as a diagram), and fraction-entry answers graded for equivalence with a
"simplest form" nudge. Every generated problem is machine-verified against
its own factors. Cross-device history via /api/scores (Cloudflare Pages
Function + Workers KV bound as SCORES).

Deploy: `npx wrangler pages deploy . --project-name probability-gym --branch main`
