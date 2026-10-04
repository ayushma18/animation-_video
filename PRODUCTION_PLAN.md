# Tens Town & Ones Town — Complete Production Plan
### A 2-minute animated Place Value lesson for Grade 1 (USA)

> **How to use this document:** This is the full production bible. Follow it top to bottom.
> The math-critical parts (base-10 blocks, numbers, place-value chart) are also delivered as a
> **working, deterministic code animation** in `/animation/index.html` so the quantities are
> provably exact. See **Section 19** for how to play and record it to MP4.

---

## 0. Requirement Analysis & Compliance Matrix

Everything below is cross-checked against the AIRA Incorporation brief.

| # | Requirement (from PDF) | How this plan satisfies it |
|---|---|---|
| 1 | Learning objective: Place Value — Tens & Ones | Entire lesson; Scenes 2–8 |
| 2 | Duration: **max 2:00** | Storyboard sums to **1:58** (hard budget below) |
| 3 | Resolution / aspect: **1920×1080, 16:9** | Canvas + export settings fixed at this |
| 4 | Language: **English** | All narration + on-screen text in English |
| 5 | Audience: **Grade 1, USA** | Vocabulary, pacing, CCSS 1.NBT alignment |
| 6 | Concepts: tens, ones, 10 ones = 1 ten, build 2-digit #, digit position = value, compare | Scenes 2,3,4,5,6,7 (comparison is an *application*, Scene 7) |
| 7 | Mandatory visual: **base-10 blocks** | Ones = unit cube; Ten = rod of 10; animated merge |
| 8 | Audio: narration + music + SFX | Section 12 + 13B |
| 9 | Deliverables: **Final MP4 + editable project files** | Sections 15, 16 |
| 10 | Evaluation: clarity, creativity, visual comm., engagement, accuracy, pacing, polish | Addressed per-criterion in Section 18 |
| 11 | Constraints: safe margins, cross-device readability, commercial licensing | Sections 10, 15, 17 |
| 12 | "Invite the child to think/predict/answer" | Scene 7 think-pause (3s) with chime |
| 13 | Understandable with **no prior knowledge** | Builds from a single cube upward |
| 14 | Math must be **correct**, shown **visually not just narrated** | Deterministic code build (Section 19) |
| 15 | Cohesive **story**, not disconnected explanations | "Tens Town & Ones Town" through-line |

**CCSS alignment (supports "Grade 1 USA standard"):** 1.NBT.B.2 (tens and ones), 1.NBT.B.2a (10 = a bundle of ten ones), 1.NBT.B.3 (compare two 2-digit numbers using >, =, <).

---

## 1. Final Creative Concept

**Title card:** *"Place Value Pals: Tens Town & Ones Town"*

**The idea.** Numbers live in a cheerful little world split into two neighborhoods.
- **Ones Town** is where small square friends live — each one is a single cube worth **1**.
- **Tens Town** is up the hill, where the tall rod friends live — each is worth **10**.

Our guides are two characters:
- **Ollie** — a small, round-cornered **orange unit cube** (value **1**). Bouncy, excited, counts everything.
- **Tenny** — a tall, friendly **blue ten-rod** made of 10 visible segments (value **10**). Calm, proud, "the big helper."

**The hook / teaching metaphor:** *"When 10 Ones hold hands, they become 1 Ten!"*
Ten Ollies line up, do a little "team-up" squeeze, and **snap together into one Tenny**. That single visual — repeated and reinforced — is the heart of the lesson. The place-value chart then shows that the *position* of a digit is what tells you whether it means "that many tens" or "that many ones."

**Why it works for a 6-year-old:** one concrete object (a cube) → a bundle (a rod) → a chart → a written number. Each step is a small, visible promise kept. The two characters give the abstract columns ("tens place," "ones place") a face and a home.

---

## 2. Complete Story (the through-line)

1. We fly into the bright world of numbers and meet Ollie, who's worth 1.
2. Ollie shows us Ones — you can count them one by one.
3. Ten Ones team up and *become* Tenny, a Ten. ("10 ones = 1 ten!")
4. Tenny and Ollie build the number **34** together with 3 tens and 4 ones.
5. They slide the blocks into a magic chart — **TENS | ONES** — and reveal **30 + 4 = 34**, explaining that where a digit sits changes its value.
6. They build a second number, **52**, so the child sees the pattern repeat.
7. Both numbers stand side by side. Ollie asks the child: *"Which is greater?"* (pause to think) Tenny shows the trick: **check the tens first** → 5 tens beats 3 tens → **52 > 34**.
8. Quick, happy recap: a 2-digit number is tens and ones; 3 tens + 4 ones = 34. "Great job!"

One world, two friends, one promise ("10 ones make 1 ten") that pays off again and again.

---

## 3. Complete 8-Scene Storyboard (with exact timing)

**Total runtime target: 1:58 (118 s).** All times in `M:SS`.

| # | Scene | Start | End | Dur |
|---|---|---|---|---|
| 1 | Introduction / Title | 0:00 | 0:12 | 12s |
| 2 | Ones | 0:12 | 0:27 | 15s |
| 3 | Tens (10 ones = 1 ten) | 0:27 | 0:47 | 20s |
| 4 | Build 34 | 0:47 | 1:07 | 20s |
| 5 | Place-Value Chart (30 + 4 = 34) | 1:07 | 1:24 | 17s |
| 6 | Another Number (52) | 1:24 | 1:36 | 12s |
| 7 | Compare 34 vs 52 (think-pause) | 1:36 | 1:51 | 15s |
| 8 | Recap / "Great job!" | 1:51 | 1:58 | 7s |

> Timing is built to the exact second in the code animation. If you add a full narration track and it runs slightly long, trim Scenes 6 and 1 first (they have the most slack).

Below, every scene gives: Visual · Character action · Objective · On-screen text · Narration · Animation · SFX · Music · Transition.

---

### SCENE 1 — Introduction (0:00–0:12)
- **Visual:** Soft sky-blue world with rolling green hills, a sign reading "Tens Town" on the hill and "Ones Town" below. Title pops in.
- **Characters:** Ollie bounces up from Ones Town and waves.
- **Objective:** Set the world; promise a fun math adventure; zero prior knowledge needed.
- **On-screen text:** `Place Value Pals` → `Tens Town & Ones Town`
- **Narration:** "Welcome to the world of numbers! *(beat)* This is Ollie. Ollie is a One. Today we'll learn how tens and ones build big numbers. Let's go!"
- **Animation:** Gentle parallax clouds drift; title scales in with a bounce; Ollie hops (squash & stretch).
- **SFX:** cheerful **whoosh** on title; soft **pop** on Ollie.
- **Music:** upbeat, light xylophone/ukulele begins (loop bed).
- **Transition:** Ollie hops toward center → quick **whoosh** wipe to Scene 2.

### SCENE 2 — Ones (0:12–0:27)
- **Visual:** Clean stage. Big label `ONES`. A ten-frame-style tray appears.
- **Characters:** Ollie points as each cube appears.
- **Objective:** A "one" is a single unit cube; you can count ones.
- **On-screen text:** `ONES` · counter `1, 2, 3, 4` · `4 ones`
- **Narration:** "These little blocks are **ones**. Let's count them. *(count with pops)* One… two… three… four. Four ones!"
- **Animation:** 4 unit cubes **pop in one at a time**; a number counter ticks 1→4; each cube does a tiny bounce as it lands.
- **SFX:** **pop** per cube (4 pops), soft **tick** on counter.
- **Music:** continues, slightly softer under the counting.
- **Transition:** Cubes slide left; **whoosh** to Scene 3.

### SCENE 3 — Tens: 10 ones = 1 ten (0:27–0:47) ★ core moment
- **Visual:** Label `TENS`. A row of 10 unit cubes fills a ten-frame.
- **Characters:** Ollie calls friends; 10 Ollies line up. Tenny is revealed after the merge.
- **Objective:** **10 ones bundle into exactly 1 ten.** This is the key insight.
- **On-screen text:** `10 ones` → `=` → `1 ten` · big `10 ones = 1 ten`
- **Narration:** "Now watch this! When **ten ones** come together… *(beat)* they make **one ten**! Ten ones equals one ten. Say hi to Tenny — Tenny is a Ten!"
- **Animation:** 10 cubes fill the frame (count 1–10), glow, **squeeze together**, and **snap/merge into a single tall ten-rod** (Tenny) that still visibly shows its 10 segments. `10 ones = 1 ten` stamps in.
- **SFX:** rising **10-note count**, a satisfying **transformation "sparkle-clunk,"** gentle **ding** on the equation.
- **Music:** small triumphant lift at the merge.
- **Transition:** Tenny slides up the hill; **whoosh** to Scene 4.

### SCENE 4 — Build 34 (0:47–1:07)
- **Visual:** Two labeled drop-zones: `TENS` (left) and `ONES` (right). Base-10 blocks assemble.
- **Characters:** Tenny stacks tens; Ollie places ones.
- **Objective:** Build a 2-digit number from tens and ones; connect quantity to the number.
- **On-screen text:** running line `3 tens + 4 ones` → `= 34`
- **Narration:** "Let's build a number! Three tens… *(place)* and four ones. *(place)* Three tens and four ones make… **thirty-four!**"
- **Animation:** 3 ten-rods **slide into the TENS zone** one by one (counter: 10, 20, 30); 4 unit cubes **pop into the ONES zone** (31, 32, 33, 34); the numeral `34` scales in with a bounce.
- **SFX:** **whoosh/clack** per rod (×3), **pop** per cube (×4), **ding** on "34."
- **Music:** steady, building.
- **Transition:** Blocks hold; a chart frame **draws on** over them → Scene 5 (match-cut, no hard wipe — keeps continuity).

### SCENE 5 — Place-Value Chart: 30 + 4 = 34 (1:07–1:24) ★ position = value
- **Visual:** A clean two-column chart. Header `TENS | ONES`. The 3 rods sit under TENS, the 4 cubes under ONES. Digits `3` and `4` drop into the header row.
- **Characters:** Tenny stands over the tens column, Ollie over the ones column; arrows point from each digit to its blocks.
- **Objective:** **A digit's position decides its value.** The `3` means **30**, the `4` means **4**.
- **On-screen text:** chart `TENS 3 | ONES 4` · `3 → 30` · `4 → 4` · `30 + 4 = 34`
- **Narration:** "Here's the secret! The **3** is in the **tens** place, so it means **thirty**. The **4** is in the **ones** place, so it means **four**. Thirty plus four equals thirty-four!"
- **Animation:** Digit `3` glows → arrow to the 3 rods → label `30`; digit `4` glows → arrow to the 4 cubes → label `4`; equation `30 + 4 = 34` assembles left to right.
- **SFX:** soft **ding** on each reveal; light **sparkle** on the final equation.
- **Music:** calm, clear (let narration lead).
- **Transition:** Chart shrinks to a corner; **whoosh** to Scene 6.

### SCENE 6 — Another Number: 52 (1:24–1:36)
- **Visual:** Same chart layout, now building `52`.
- **Characters:** Tenny proudly brings 5 tens; Ollie adds 2 ones.
- **Objective:** Reinforce the pattern with a new number (fast, confident).
- **On-screen text:** `5 tens + 2 ones = 52` · chart `TENS 5 | ONES 2`
- **Narration:** "Let's try another! Five tens… and two ones. That makes **fifty-two**. Five, two — fifty-two!"
- **Animation:** 5 rods snap into TENS (counter 10→50), 2 cubes pop into ONES (51, 52); `52` scales in.
- **SFX:** **clack** ×5, **pop** ×2, **ding** on "52."
- **Music:** upbeat, momentum.
- **Transition:** `52` slides to the right side of the stage; `34` slides back in on the left → Scene 7.

### SCENE 7 — Compare 34 vs 52 (1:36–1:51) ★ think-pause
- **Visual:** Both numbers side by side with their block towers: `34` (3 rods, 4 cubes) | `52` (5 rods, 2 cubes). A big question mark.
- **Characters:** Ollie asks; both lean in waiting. On reveal, confetti + happy hop.
- **Objective:** Apply place value to compare — **check the tens first**. (Application, not a new lesson.)
- **On-screen text:** `Which is greater?` · *(pause)* · `Check the tens first!` · `5 tens > 3 tens` · `52 > 34`
- **Narration:** "Which number is greater — 34 or 52? *(PAUSE ~3s — let the child think.)* Look at the **tens** first! Five tens is more than three tens. So **52 is greater than 34**!"
- **Animation:** `?` pulses during the pause (a soft thinking chime). On reveal: the tens columns highlight, `5 > 3` flashes, then `52 > 34` stamps with the `>` enlarging; a small **confetti** burst.
- **SFX:** gentle **thinking chime** during pause; **ding** + **celebration** on reveal.
- **Music:** holds softly under the pause, lifts on the reveal.
- **Transition:** Confetti settles; quick **whoosh** to recap.

### SCENE 8 — Recap / "Great job!" (1:51–1:58)
- **Visual:** Tenny and Ollie together, center, with a tidy summary card.
- **Characters:** Both wave and cheer.
- **Objective:** Lock in the one-sentence takeaway.
- **On-screen text:** `Tens + Ones = a 2-digit number` · `3 tens + 4 ones = 34` · `Great job!`
- **Narration:** "Remember — a two-digit number is made of **tens** and **ones**. Three tens and four ones make thirty-four. Great job! See you next time!"
- **Animation:** summary lines pop in; Tenny & Ollie bounce; `Great job!` sparkles.
- **SFX:** **celebration** sting, final **ding**.
- **Music:** happy resolve / button, fades out.
- **Transition:** Gentle fade to a solid brand end-card (optional logo).

---

## 4. Exact Timing (cue sheet)

```
0:00  Scene 1  Title + Ollie            whoosh, pop        music in
0:12  Scene 2  ONES, count 1–4          pop×4, tick
0:27  Scene 3  10 ones → 1 ten (merge)  count×10, sparkle-clunk, ding
0:47  Scene 4  Build 34                 clack×3, pop×4, ding
1:07  Scene 5  Chart 30 + 4 = 34        ding×3, sparkle
1:24  Scene 6  Build 52                 clack×5, pop×2, ding
1:36  Scene 7  Compare (pause 1:40–1:43) chime, ding, confetti
1:51  Scene 8  Recap + Great job!       celebration, ding   music out
1:58  END
```

---

## 5. Complete Narration Script (Grade 1 English)

> Tone: warm, friendly, energetic but **not rushed**. Short sentences. `[...]` = pause.
> Total ≈ 150–160 spoken words → fits comfortably in ~1:58 with the written pauses.

```
[Scene 1]
Welcome to the world of numbers! [0.5s]
This is Ollie. Ollie is a One.
Today we'll learn how tens and ones build big numbers. Let's go!

[Scene 2]
These little blocks are ones.
Let's count them. [0.3s]
One… two… three… four.
Four ones!

[Scene 3]
Now watch this!
When ten ones come together… [0.6s] they make one ten!
Ten ones equals one ten.
Say hi to Tenny. Tenny is a Ten!

[Scene 4]
Let's build a number!
Three tens… [0.4s] and four ones. [0.4s]
Three tens and four ones make… thirty-four!

[Scene 5]
Here's the secret!
The three is in the tens place, so it means thirty.
The four is in the ones place, so it means four.
Thirty plus four equals thirty-four!

[Scene 6]
Let's try another!
Five tens… and two ones.
That makes fifty-two. Five, two — fifty-two!

[Scene 7]
Which number is greater — thirty-four or fifty-two?
[PAUSE 3s — let the child think]
Look at the tens first!
Five tens is more than three tens.
So fifty-two is greater than thirty-four!

[Scene 8]
Remember — a two-digit number is made of tens and ones.
Three tens and four ones make thirty-four.
Great job! See you next time!
```

A clean, TTS-ready copy (no stage directions) is saved separately at **`narration_script.txt`**.

---

## 6. All On-Screen Text (complete list)

Keep every item short and large. No paragraphs on screen.

| Scene | Text |
|---|---|
| 1 | `Place Value Pals` · `Tens Town & Ones Town` |
| 2 | `ONES` · `1` `2` `3` `4` · `4 ones` |
| 3 | `TENS` · `10 ones = 1 ten` |
| 4 | `3 tens + 4 ones = 34` · `34` |
| 5 | `TENS | ONES` · `3` `4` · `30 + 4 = 34` |
| 6 | `5 tens + 2 ones = 52` · `52` |
| 7 | `Which is greater?` · `Check the tens first!` · `5 > 3` · `52 > 34` |
| 8 | `Tens + Ones = a 2-digit number` · `3 tens + 4 ones = 34` · `Great job!` |

---

## 7. Character Designs

### Tenny (the Ten)
- **Represents:** 10 (one ten-rod).
- **Shape:** Tall vertical rounded rectangle, clearly divided into **10 equal segments** (so it always "reads" as ten units). ~3× taller than wide.
- **Color:** Sky/royal **blue** (`#2F6BFF`) body, slightly darker segment lines, white segment highlights.
- **Face:** Big friendly eyes near the top, small smile; soft rosy cheeks.
- **Accessory:** A tiny number **"10"** badge or a little flag; optional small graduation-style cap to read as "the helper/teacher."
- **Personality:** Calm, proud, encouraging — the "big buddy."
- **Movement:** Smooth slides, gentle lean; squashes a little when landing. Doesn't bounce as fast as Ollie.
- **Expressions needed:** neutral-happy, proud, "ta-da," thinking (Scene 7), cheering (Scene 8).

### Ollie (the One)
- **Represents:** 1 (one unit cube).
- **Shape:** Small rounded **square cube**, roughly 1 segment of Tenny (so scale relationship is honest).
- **Color:** Warm **orange** (`#FF8A3D`) body, white highlight, darker outline.
- **Face:** Large excited eyes, wide smile; very expressive.
- **Accessory:** Tiny number **"1"** badge.
- **Personality:** Bouncy, curious, enthusiastic counter — the "little explorer."
- **Movement:** Fast hops with strong squash & stretch; spins on excitement.
- **Expressions needed:** excited, counting/pointing, surprised (merge), questioning (Scene 7), cheering.

### Consistency rules (critical for AI reproduction)
- **Scale law:** Ollie = exactly 1 unit; Tenny = exactly 10 of those units tall. Never change this.
- **Fixed palette:** only the hexes above for bodies; outlines `#1B2B4D`.
- **Flat vector, thick rounded outline, no gradients beyond a single soft highlight.**
- **Front-facing 3/4 view in every scene.** Same eye style, same smile curve.
- **Build each character ONCE as a master SVG/PNG with transparent background**, then reuse that exact file in every scene (do **not** re-generate the character per scene — that's how AI tools drift). Pose changes are done by the animator, not by re-prompting.

---

## 8. Visual Asset List (with production method)

Method key: **AI** = AI image gen · **VEC** = vector (Illustrator/Figma/Inkscape) · **SW** = built in the animation/editor software · **IMP** = generated separately & imported · **CODE** = the deterministic code build in `/animation`.

| Asset | Method | Notes |
|---|---|---|
| Tenny (master, transparent PNG + SVG) | AI → clean up as VEC, or VEC directly | One master file, reused |
| Ollie (master, transparent PNG + SVG) | AI → VEC, or VEC | One master file, reused |
| Tenny/Ollie expression set (5 each) | VEC/SW | Swap faces, keep body |
| Background: Tens Town & Ones Town world | AI or VEC | 1920×1080, low-detail so text pops |
| Clean teaching background (plain) | VEC/SW | Light solid/soft-gradient for math scenes |
| Ones block (unit cube) | **VEC/CODE** | **Never AI** — must be exact |
| Tens block (rod of 10) | **VEC/CODE** | Must visibly show 10 segments |
| Ten-frame tray | VEC/SW/CODE | Helps counting |
| Place-value chart (TENS | ONES) | **VEC/SW/CODE** | Clean, high-contrast |
| Numerals 0–9 + "34", "52" | **SW/CODE** | Rendered as text, never AI |
| Math symbols `+ = > < ?` | SW/CODE | Text/vector |
| Arrows (digit → blocks) | VEC/SW | Simple, bold |
| Text/title lower-thirds & cards | SW | Big, safe-margined |
| Confetti / sparkle / glow FX | SW | Editor particle presets |
| Town signs ("Tens Town"/"Ones Town") | VEC/AI | Readable font |
| **SFX** pop, click, whoosh, ding, celebration, transform, thinking chime | IMP (licensed) or CODE (WebAudio) | Section 12/17 |
| **Music** upbeat kids bed (loopable) | IMP (licensed) | Section 12/17 |

**Rule of thumb:** anything that carries a *quantity or a number* is **CODE/VEC/SW**, never AI. Anything decorative (characters, world, signs) may be AI.

---

## 9. Exact AI Prompts for Assets

Use any capable image model (Midjourney, DAL·E, Adobe Firefly, Ideogram, Leonardo, or ElevenLabs/Higgsfield image tools if available). Generate at the largest square/landscape you can, transparent where noted.

**Shared style suffix (append to every character/world prompt):**
> `flat 2D vector children's educational illustration, thick rounded outlines, bright friendly colors, simple shapes, soft single highlight, no gradients, no text, clean, modern, Pixar-cute but flat, high contrast, plain background, 4k`

**Tenny (the Ten):**
> `A cute friendly cartoon mascot shaped as a tall vertical rounded rectangle divided into exactly 10 equal stacked segments, sky-blue (#2F6BFF) body with soft white highlights, big happy eyes near the top, small smile, rosy cheeks, tiny "10" badge, front 3/4 view, transparent background` + style suffix. *(Regenerate until segments = 10; then vectorize/clean once and lock.)*

**Ollie (the One):**
> `A cute friendly cartoon mascot shaped as one small rounded cube, warm orange (#FF8A3D) body with a white highlight, large excited eyes, wide smile, tiny "1" badge, front 3/4 view, transparent background` + style suffix.

**Expression sheet:**
> `Character turnaround / expression sheet of [Tenny OR Ollie as described], five expressions in a row: neutral-happy, excited, surprised, thinking, cheering, identical body and colors in each, transparent background` + style suffix.

**World background (Tens Town & Ones Town):**
> `A bright cheerful cartoon landscape: rolling green hills under a soft blue sky with simple round clouds, a small town of square houses at the bottom labeled area "Ones Town", taller buildings on the hill area "Tens Town", lots of empty sky space in the center for overlays, low detail, 16:9, 1920x1080` + style suffix (allow small readable sign text).

**Clean teaching background:**
> `A very simple, soft pastel gradient background, light sky blue to white, with a faint rounded rectangle stage area in the center, minimal, uncluttered, 16:9` + style suffix.

> ⚠️ **Do NOT** prompt an AI image model to draw "34 as base-10 blocks," "a place value chart," or any numbers — AI will miscount. Those come from the code build / vector / editor.

---

## 10. Exact AI Prompts for Each Animation Scene (+ the accuracy rule)

> **READ FIRST — Accuracy rule:** Generative *video* models (Runway, Kling, Pika, Sora, Veo, Higgsfield, etc.) **cannot be trusted to keep exact quantities, numbers, or text.** Use them **only** for character/world motion with **no numbers on screen**. All blocks, digits, charts, and equations must be composited from the **code build or vector assets** on top (see Section 11 & 19). Each prompt below therefore ends with **"NO numbers, NO text, NO math symbols in frame."**

Format per scene: Characters · Appearance · Position · Action · Camera · Object motion · Concept · Background · Duration · Style · Text · Must-not-change.

**Scene 1 (12s):**
> Characters: Ollie (small orange cube mascot, big eyes). Position: enters bottom-left, hops to center. Action: waves happily, bounces. Camera: slow push-in over the town landscape, gentle cloud parallax. Object motion: clouds drift. Concept: welcome. Background: Tens Town & Ones Town world. Duration: 12s. Style: flat 2D kids animation, smooth, bright. Text: NONE (title added later). Must not change: Ollie's shape/orange color. **NO numbers, NO text, NO math symbols in frame.**

**Scene 2 (15s):**
> Characters: Ollie. Position: left side, pointing right. Action: points and nods as if counting small objects. Camera: static, centered stage. Object motion: none (blocks added later in editor). Concept: counting ones. Background: clean pastel stage. Duration: 15s. Style: flat 2D. Text: NONE. Must not change: Ollie. **NO numbers, NO text, NO math symbols in frame.**

**Scene 3 (20s):**
> Characters: ten Ollie cubes in a row that squeeze together and a single tall blue Tenny rod appears in their place. Position: center. Action: cubes huddle, glow, merge into one tall rod that smiles. Camera: static. Concept: ten ones become one ten. Background: clean stage. Duration: 20s. Style: flat 2D, satisfying squash-and-merge. Text: NONE. Must not change: 10 small orange cubes become exactly 1 tall blue rod; blue rod shows stacked segments. **NO numbers, NO text, NO math symbols in frame.** *(Because count matters here, prefer doing this merge in the code build — Scene 19 — and use AI only if it reliably shows 10→1.)*

**Scene 4 (20s):**
> Characters: Tenny and Ollie working together. Position: Tenny left, Ollie right. Action: Tenny carries tall rods and sets them down on the left; Ollie sets small cubes on the right. Camera: static. Concept: building a number from tens and ones. Background: clean stage with two faint zones. Duration: 20s. Style: flat 2D. Text: NONE. Must not change: Tenny blue tall rods, Ollie orange cubes. **NO numbers, NO text, NO math symbols in frame.** *(Exact counts 3 and 4 are composited from code/vector, not from the AI.)*

**Scene 5 (17s):**
> Characters: Tenny stands on the left, Ollie on the right, both pointing upward. Position: flanking a central empty chart area. Action: gesture to the chart (chart + digits added later). Camera: static. Concept: position decides value. Background: clean stage. Duration: 17s. Style: flat 2D. Text: NONE. Must not change: character colors/positions. **NO numbers, NO text, NO math symbols in frame.**

**Scene 6 (12s):**
> Same setup as Scene 4, confident/proud poses, Tenny brings more rods. Duration 12s. **NO numbers, NO text, NO math symbols in frame.**

**Scene 7 (15s):**
> Characters: Ollie leans in with a curious/questioning look, Tenny thinks then nods; on cue both cheer with a small confetti burst. Position: Ollie left, Tenny right, central gap for the two towers. Action: questioning → thinking → celebrating. Camera: static. Concept: comparing. Background: clean stage. Duration: 15s. Style: flat 2D. Text: NONE. Must not change: characters. **NO numbers, NO text, NO math symbols in frame.**

**Scene 8 (7s):**
> Characters: Tenny and Ollie together center, waving and cheering, confetti. Camera: static, slight zoom. Duration: 7s. Style: flat 2D celebratory. Text: NONE. **NO numbers, NO text, NO math symbols in frame.**

---

## 11. Recommended Workflow if AI Video Is Unreliable (it is, for math)

**Use this hybrid — it's what the code build already implements:**

1. **Characters & world:** AI image gen → clean to vector → lock master files.
2. **Character motion (optional):** either (a) AI video per prompts above with **no numbers in frame**, or (b) simple keyframed motion in the editor using the master PNGs. (b) is more reliable and on-brand.
3. **All math (blocks, numbers, chart, equations, comparison):** the **deterministic code animation** in `/animation/index.html` (Section 19) OR vector shapes animated by hand. These are pixel-exact and can never miscount.
4. **Narration:** AI TTS (Section 13B).
5. **Music & SFX:** licensed library or the code build's WebAudio SFX.
6. **Assemble & export** in your editor (Section 14) — or just **screen-record the code build** for a finished MP4 with zero compositing.

> **Priority order, always: mathematical accuracy > story/cohesion > polish > fancy AI effects.**

---

## 12. Audio Plan

**Narration (VO):**
- One continuous track, child-friendly adult female or warm teacher voice (see 13B).
- Normalize to about **−3 dB peak**; sits on top, always clearest element.
- Honor the written pauses, especially the **3s think-pause** in Scene 7.

**Background music:**
- Mood: happy, playful, curious — ukulele/xylophone/marimba kids' bed, ~100–120 BPM.
- Plays the whole video at **low level (−18 to −20 dB under VO)**; small lifts at the Scene 3 merge, Scene 7 reveal, Scene 8 button. Fade in 0:00, fade out by 1:58.

**Sound effects (where):**
| SFX | Where |
|---|---|
| **Pop** | each one-cube appears (Scenes 2,4,6) |
| **Click/tick** | counter increments |
| **Whoosh** | scene transitions, title |
| **Transform "sparkle-clunk"** | 10→1 merge (Scene 3) |
| **Ding** | each correct reveal / equation complete |
| **Thinking chime** | Scene 7 pause |
| **Celebration** | Scene 7 reveal, Scene 8 |

**Mixing rule:** duck music slightly under VO; place SFX in gaps so they **never cover narration**. Target overall loudness around **−14 LUFS** (web-friendly).

---

## 13. AI Production Workflow

### A. Image / Asset Generation
Follow Section 9 prompts. Generate characters + world, pick the best, **vectorize and lock master files** into `/Characters` and `/Backgrounds`. Build an expression sheet for each character. Export blocks/chart/numbers as vector or use the code build.

### B. Voice Generation
- **Tool:** ElevenLabs (recommended for natural kid-friendly reads), or PlayHT, Murf, Microsoft Azure Neural TTS (e.g., "Jenny"/"Aria"), Google WaveNet.
- **Voice pick:** warm, bright, friendly female "teacher" voice; moderate pace; expressive.
- **Settings (ElevenLabs-style):** Stability ~40–50 (expressive), Similarity ~75, Style exaggeration low–moderate. Speaking rate ~0.95× (slightly slower for Grade 1).
- **Input:** paste `narration_script.txt`. Render **each scene as its own clip** (easier to time) or one full take. Insert real silence for the Scene 7 pause (or leave a 3s gap and add in editor).
- **Export:** WAV/MP3, 44.1 kHz. Save to `/Audio`.
- **If a voice tool is available in this environment** (e.g., an ElevenLabs/Higgsfield MCP with `generate_audio`/`create_voice`), you can generate the VO directly from `narration_script.txt` — just confirm the tool's commercial-use rights (Section 17).

### C. Animation / Video Generation
- Preferred: **code build (Section 19)** for all math scenes.
- Optional: AI video per Section 10 prompts for character/world motion **only**, composited under the code/vector math layers.

---

## 14. Editing / Assembly Plan

**Editor options:** After Effects (best control), Premiere/DaVinci Resolve/CapCut (timeline assembly), or Canva (simplest). Or skip compositing entirely by recording the code build.

- **Canvas:** 1920×1080, **16:9**, 30 fps (or 60), square pixels.
- **Scene order & durations:** exactly per Section 3/4.
- **Safe margins:** keep all numbers/text/chart within the **center 90% (title-safe ~5% inset ≈ 54 px top/bottom, 96 px sides)**. Nothing important in the outer border.

**Layer structure (bottom → top):**
```
L1  Background (world or clean stage)
L2  Characters (Tenny, Ollie — master PNG/SVG)
L3  Base-10 blocks & ten-frame (vector/code)
L4  Place-value chart
L5  Numbers, symbols, arrows
L6  On-screen text / titles / cards
L7  FX (sparkle, confetti, glow)
L8  Transitions (whoosh wipes)
---- audio ----
A1  Narration (VO)
A2  Background music (ducked)
A3  SFX
```

- **Text placement:** titles upper-center or centered; equations centered; labels directly above their columns. Font: rounded, friendly, highly legible (see 17 for licensing) — e.g., **Baloo 2, Fredoka, Quicksand, or Nunito** (all free/commercial-OK via Google Fonts). Min on-screen text height ≈ **48–60 px**; the big numbers much larger.
- **Character placement:** Tenny left/tens side, Ollie right/ones side — keep consistent so position reinforces place value.
- **Block placement:** TENS zone left, ONES zone right — **matches the chart column order** (crucial).
- **Transitions:** quick whoosh wipes (~8–12 frames) between scenes; match-cut from Scene 4→5.
- **Audio tracks:** as above; duck music under VO; fades at head/tail.

---

## 15. Editable Project — What to Keep & Folder Structure

**Preserve (so the submission is genuinely editable):**
- The **editor project file** (`.aep` / `.prproj` / `.drp` / CapCut / Canva link) in `/Project`.
- The **code build** (`/animation/index.html`) — itself an editable, re-exportable source.
- All **master character files** (layered/SVG + transparent PNG) in `/Characters`.
- **Backgrounds** (editable + flattened) in `/Backgrounds`.
- **Block/chart vector sources** in `/Blocks`.
- **VO stems** in `/Audio`, **music** in `/Music`, **SFX** in `/SFX`.
- **Fonts** (and their license files) in `/Fonts`.
- The final render in `/Final`.
- This `PRODUCTION_PLAN.md` + `narration_script.txt` + `LICENSES.md`.

**Folder structure (already created):**
```
Place_Value_Animation/
├── Final/          ← Place_Value_Tens_Ones_1080p.mp4
├── Project/        ← editor project file(s)
├── Characters/     ← Tenny, Ollie (SVG/PNG + expression sheets)
├── Backgrounds/    ← world + clean stage
├── Blocks/         ← ones cube, tens rod, chart (vector)
├── Audio/          ← narration stems
├── Music/          ← background music bed
├── SFX/            ← pop, click, whoosh, ding, celebration, transform, chime
├── Fonts/          ← font files + license
├── animation/      ← index.html (working deterministic build)  ← SEE SECTION 19
├── PRODUCTION_PLAN.md
├── narration_script.txt
└── LICENSES.md
```

---

## 16. Export Settings

- **Format:** MP4 (H.264).
- **Resolution:** 1920×1080.
- **Aspect:** 16:9.
- **Frame rate:** 30 fps (60 fps acceptable for extra-smooth motion).
- **Bitrate:** 10–16 Mbps VBR (2-pass) — crisp text, reasonable file size.
- **Audio:** AAC, 320 kbps, 48 kHz, stereo.
- **Color:** Rec.709, 8-bit.
- **Filename:** `Place_Value_Tens_Ones_1080p.mp4` → `/Final`.
- **Also export (optional):** a 1280×720 lightweight copy for quick sharing.

---

## 17. Commercial-Use / Licensing Checklist

All assets must be **original or licensed for commercial use** (PDF requirement).

| Asset type | Action | Notes |
|---|---|---|
| Characters/world (AI) | Verify tool's commercial rights | Firefly, DALL·E (OpenAI), Midjourney (paid tier) grant commercial use; check current ToS. Keep a screenshot of the license terms. |
| AI voice | Verify commercial license | ElevenLabs/PlayHT/Murf paid plans allow commercial use — confirm your plan tier. |
| Fonts | Use commercial-OK fonts | **Google Fonts** (Baloo 2, Fredoka, Quicksand, Nunito) = OFL/Apache, commercial OK. Save the license text in `/Fonts`. |
| Music | License or royalty-free | Sources with clear commercial licenses: Pixabay Music, YouTube Audio Library, Incompetech (CC-BY, give credit), Uppbeat, Epidemic/Artlist (paid). Avoid anything "personal use only." |
| SFX | License or generate | Same as music, or use the **code build's WebAudio SFX (fully original, no license needed)**. Freesound = check each clip's CC license. |
| Blocks/chart/numbers | Original (yours) | Vector/code = original work, no license issue. |

**Keep a license record:** fill in `LICENSES.md` (template provided) with, per asset: source, license type, link, date obtained, and commercial-use confirmation. Prefer assets you generate yourself (code SFX, vector math) to minimize licensing risk.

---

## 18. Final Quality Checklist (pre-submission)

**Educational**
- [ ] Ones explained (Scene 2)
- [ ] Tens explained (Scene 3)
- [ ] **10 ones = 1 ten shown visually** (Scene 3 merge)
- [ ] 2-digit number explained (Scene 4)
- [ ] Digit **position → value** explained (Scene 5)
- [ ] **3 tens + 4 ones = 34** shown with real blocks (Scenes 4–5)
- [ ] Another number demonstrated — **52** (Scene 6)
- [ ] Comparison included (Scene 7)
- [ ] **Tens checked first** during comparison (Scene 7)
- [ ] Child gets a **think/answer pause** (Scene 7, ~3s)
- [ ] Clear final takeaway (Scene 8)

**Technical**
- [ ] English · [ ] ≤ 2:00 · [ ] 16:9 · [ ] 1920×1080 · [ ] MP4
- [ ] Narration present · [ ] Background music · [ ] SFX
- [ ] Editable project files included
- [ ] Readable on desktop/laptop/tablet (big text, high contrast)
- [ ] Safe margins respected (nothing important near edges)
- [ ] **No mathematical errors** (counts verified against code build)

**Creative**
- [ ] Engaging for Grade 1 · [ ] Consistent characters · [ ] Cohesive story
- [ ] Smooth pacing · [ ] Clear visual hierarchy · [ ] Not text-overloaded · [ ] Polished

**Evaluation-criteria pass (AIRA's list):** clarity ✓ · creativity ✓ · visual communication ✓ · engagement ✓ · concept accuracy ✓ · storytelling/pacing ✓ · overall execution ✓.

---

## 19. The Working Code Animation (your accuracy guarantee)

`/animation/index.html` is a **complete, self-contained, deterministic** build of the full ~2-minute lesson:

- All 8 scenes with the exact timing in Section 4.
- **Base-10 blocks rendered from counts in code** — when it shows 34, it is *generated from the numbers 3 and 4*, so it is **impossible** to show the wrong quantity.
- Tenny & Ollie as inline SVG (editable).
- The 10→1 merge, the TENS|ONES chart, `30 + 4 = 34`, `52`, the compare with a real **think-pause**, confetti, and `Great job!`.
- **Original WebAudio SFX** (pop, click, whoosh, ding, transform, chime, celebration) — no licensing needed.
- On-screen captions synced to the narration (so it teaches even before you add a VO track).
- Safe-margin guides respected; scales to any screen while staying 16:9.

**How to play:** open `animation/index.html` in Chrome/Edge → click **Play**.

**How to turn it into the Final MP4 (easiest, zero compositing):**
1. Open it full-screen in Chrome.
2. Record the stage with **OBS Studio** (free, commercial-OK) at 1920×1080, 30 fps — or Windows **Game Bar** (`Win+G`).
3. Add your AI-generated **narration** track over it in any editor (or let the on-screen captions carry it), plus a licensed **music** bed.
4. Export per Section 16 → `/Final/Place_Value_Tens_Ones_1080p.mp4`.

**How to add real narration into the page:** drop a `voiceover.mp3` into `/animation/` and the player will use it automatically (it's wired to look for that file); otherwise it plays with SFX + captions.

> This is the "safer hybrid workflow" the brief hints at, taken to its most reliable form: the math is code, so it is exact every time.

---

### Quick-start checklist for YOU
1. Open `animation/index.html`, watch it, confirm the math reads clearly.
2. Generate **Tenny/Ollie/world** images (Section 9) → drop into `/Characters`, `/Backgrounds` (optional upgrade of the SVG characters).
3. Generate **narration** from `narration_script.txt` (Section 13B) → `/animation/voiceover.mp3` and/or `/Audio`.
4. Pick a **licensed music** bed → `/Music`; fill in `LICENSES.md`.
5. **Record** the animation (OBS) + mix audio in your editor → export MP4 → `/Final`.
6. Run the **Section 18 checklist**. Submit `Final/` + `Project/` + `animation/`.
