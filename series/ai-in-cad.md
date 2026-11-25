# Series: AI in CAD — "AI vs Engineer"

**Pillars:** CAD & Software (primary) · Design Engineering · Manufacturing · Engineering Reality
**Format:** 45–75 s reels, recurring visual identity, numbered episodes

---

## Why reframe "AI in CAD" as "AI vs Engineer"

"AI in CAD" as a plain topic tends to drift into:
- "5 AI tools every engineer must know" lists that every tech page already posts
- Hype claims ("AI will replace CAD designers") that age badly and hurt credibility
- Feature tours that go out of date with the next software release

**Stronger angle:** every episode is an **experiment**. Give AI a real engineering task, then judge the output like a senior engineer would: can it be made, does it fit, would it pass a drawing review?

That fits re.mecch exactly: curious, experimental, practical, and focused on *what happens when things go wrong*. It also takes a stand people will argue about in the comments (good for reach) without overhyping.

**Series promise (say it in every episode):**
> "AI ko real engineering kaam dete hain. Pass ya fail — engineer decide karega."

**Recurring identity**
- Title card: `AI vs ENGINEER #0X`
- Verdict stamp at the end: **PASS** (blue) / **FAIL** (orange) / **"PASS… with a fine print"**
- Score on 3 axes: *Manufacturable? · Accurate? · Time saved?*

---

## Episode bank

| # | Experiment | Pillar tie-in | Likely payoff |
|---|-----------|---------------|---------------|
| 1 | Generative design makes a bracket. Can it actually be machined? | Manufacturing | Organic shape looks amazing, but manufacturing constraints change everything |
| 2 | Ask an AI chatbot to write a SolidWorks macro (batch-export PDFs/DXFs) | CAD productivity | Real time saved, plus where it broke and how it was fixed |
| 3 | Ask AI to suggest a fit for a bearing on a shaft (e.g. H7/k6-style choice) | Design / tolerances | Check its answer against a fits table and the actual use case |
| 4 | Show AI a drawing and ask it to find mistakes | Design review | What it caught vs. what a human checker caught |
| 5 | Text-to-CAD: "make me a flange with 6 bolt holes on a PCD" | CAD | Geometry right? Design intent / feature tree usable? |
| 6 | Ask AI to apply GD&T to a simple part | GD&T | Datum choice and functional logic, usually the weak spot |
| 7 | AI picks a material for a part (given load, environment, cost) | Materials | Reasonable shortlist vs. what industry would actually stock and use |
| 8 | AI vs fresher vs senior: same design question | Careers | What actually makes an engineer valuable |
| 9 | Ask AI to write a DFM checklist for sheet metal | Manufacturing | Generic points vs. real shop-floor rules (bend radius, hole-to-bend distance) |
| 10 | Season finale: "Will AI replace CAD designers?" with evidence from eps 1–9 | Careers / Reality | A grounded, provocative verdict |

> **Accuracy rule for this series:** film real results and don't script the verdict in advance. If the AI does well, say so. Name the tool and version/date on screen, because these tools change fast.

---

## Pilot script — Episode 1

**Title:** AI ne bracket design kiya. Machinist ne mana kar diya.
**Length:** ~60 s
**Core idea:** Generative design output depends heavily on the **manufacturing method you choose as a constraint**. "Unrestricted" shapes often need additive manufacturing; selecting milling constraints gives a very different, machinable part.
**Accuracy check:** Confirm the constraint options available in the tool/version you use (e.g. Autodesk Fusion generative design offers unrestricted, additive, milling, 2-axis cutting and die-casting style options). Run the study for real and show the actual outputs.

### Hook (0–3 s)

| Spoken | On-screen text | Visual |
|---|---|---|
| "AI ne ye bracket design kiya… aur machinist ne bola — *bhai, ye banega kaise?*" | AI vs ENGINEER #01 | Slow orbit of an alien, bone-like generative bracket. Hard cut to a machinist shaking their head (or a meme stand-in). |

### Body

| Time | Spoken | On-screen text | Visual / B-roll | Edit note |
|---|---|---|---|---|
| 3–12 s | "Generative design simple hai — tum load, fixed points aur material batao, software khud shape nikalta hai. Weight kam, strength same." | Loads + Constraints → AI Shape | Screen recording: applying loads, preserve/obstacle geometry | Fast zoom-ins on each input |
| 12–25 s | "Problem? Default pe 'unrestricted' chhodo toh aisi shapes aati hain — undercuts, hollow pockets, curved branches. End mill wahan pahunch hi nahi sakta." | UNRESTRICTED = ⚠️ | Highlight undercuts in **orange**; animate an end mill colliding | Collision sound effect |
| 25–40 s | "Ab wahi study, but constraint daalo — 3-axis milling, tool direction fix. Dekho shape kaise badal gayi." | + MILLING CONSTRAINT | Side-by-side: unrestricted vs milling result, milling one in **blue** | Swipe transition, before/after slider |
| 40–50 s | "Matlab AI design nahi kar raha — tumhare constraints ka answer de raha hai. Galat constraint, galat part." | Garbage constraints in = garbage part out | Close-up on constraint panel | Punch-in on the line |

### Payoff + CTA (50–60 s)

| Spoken | On-screen text | Visual |
|---|---|---|
| "Verdict? AI pass — *agar engineer ko pata hai manufacturing kaise hoti hai.* Next episode: AI se SolidWorks macro likhwayenge. Follow karo, dekhte hain kitna time bachta hai." | VERDICT: PASS… with a fine print | Stamp animation. Episode 2 teaser frame. |

**Caption:**
Generative design looks like the future… until a machinist sees it 😅
AI vs Engineer #01: unrestricted vs milling constraint, same load case and two completely different parts.
Kya tumne kabhi generative design try kiya hai? Comment mein batao 👇

**Hashtags:** #generativedesign #cad #designengineering #cncmachining #dfm #mechanicalengineering #fusion360 #engineeringreels #aiinengineering

**Save trigger:** side-by-side comparison frame (unrestricted vs milling)
**Share trigger:** "Send this to the friend who thinks AI will replace engineers"
**Follow trigger:** episode 2 teaser
