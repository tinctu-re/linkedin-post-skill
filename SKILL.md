# LinkedIn Post Generator — Claude Skill

## What this skill does

Takes your bullet points or rough idea and structures them into a ready-to-post LinkedIn post using one of six proven formats for technical founders. Writes in your voice, not a generic content-creator voice.

## Invocation

```
/linkedin-post [your bullet points or rough idea]
```

Optional flags:
```
format: observation | number | before-after | question | polarising | unspoken-truth | choose
voice: [one sentence about your style, e.g. "direct, occasional profanity, no fluff"]
```

## Examples

```
/linkedin-post We noticed our best customers came from competitor failures. They close faster and churn less.
format: observation
```

```
/linkedin-post Cold email reply rates have dropped significantly over two years. Most founders are using old playbooks.
format: number
```

```
/linkedin-post Six months ago I was on every sales call. Now I'm on fewer than 20%. Close rate went up.
format: before-after
voice: direct, first-person, slightly self-deprecating
```

---

## The six formats

### Format 1: The Observation
- Line 1: the specific thing you noticed (concrete, not vague)
- Lines 2–3: what it means, why it matters
- Line 4: the implication or takeaway
- Optional line 5: the question it raises

### Format 2: The Number
- Line 1: the number, naked and upfront
- Lines 2–3: what the number means in plain language
- Line 4: what founders should do differently because of it

### Format 3: The Before/After
- Lines 1–2: the before (specific, honest)
- Lines 3–4: what changed — one action or decision, not a montage
- Line 5: the after (specific, measurable difference)
- Optional: what you'd tell yourself then

### Format 4: The Question You Already Know the Answer To
- Line 1: the question (genuine, specific)
- Lines 2–3: your actual answer — a position, not "it depends"
- Line 4: the one thing that changes if they take that position

### Format 5: The Polarising Statement
- Line 1: the claim, naked — just say the thing
- Lines 2–3: the evidence or reasoning
- Line 4: the implication — what changes if this is true
- Optional: the strongest pushback and why you still hold the position

### Format 6: The Unspoken Truth
- Lines 1–2: the thing that's usually not said — specific, no softening
- Lines 3–4: the concrete moment or feeling (one scene, one number)
- Close: what you wish someone had told you — or leave it open

---

## Writing rules this skill follows

- Max 3 hashtags, at the end only
- No em-dashes
- No filler openers ("In today's world", "Here's the thing", "Let me explain")
- No subject-dropping — complete sentences
- No markdown formatting (LinkedIn renders plain text)
- Varied sentence length — no three consecutive short sentences
- 150–300 words
- No listicles
