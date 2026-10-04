# Synchronization Report — Place Value Pals

## Method
The **actual narration audio is the master timeline.** The voiceover was generated sentence-by-sentence
(Windows SAPI, draft voice), each clip's real duration was measured, and the clips were concatenated with
controlled silence gaps. That measurement produced `animation/sync.json`, which gives the exact start/end
(in ms) of every spoken sentence. Both the **subtitles** and the **animation beats** are driven from those
measured times — they are no longer timed independently, and playback is locked to the audio clock
(`audio.currentTime` drives the animation).

## Numbers
- **Total video duration:** 1:52 (112.5 s audio; timeline cap 112.8 s) — within the 2:00 maximum.
- **Number of scenes:** 8 (Intro, Ones, 10→1 Ten, Build 34, Place Value, Build 52, Compare, Recap).
- **Narration duration:** ~112.5 s, 46 timed sentence/phrase cues, including a ~2.5 s think-pause in the compare scene.
- **Aspect / resolution:** 16:9, 1920×1080. **Language:** English. **Audience:** Grade 1.

## Confirmations
- ✅ **Subtitles are the exact spoken words**, pulled from the same sentence list that was sent to the TTS.
  No rewritten subtitle track. (Math expressions like `3 tens + 4 ones = 34` appear as *separate* on-screen
  educational text, not as the subtitle.)
- ✅ **Subtitle timing = measured audio.** Each caption appears when the sentence starts and clears when it
  ends (+120 ms tail, never into the next line). During the think-pause the subtitle is blank.
- ✅ **Animation retimed to the narration.** Every visual beat fires on its sentence (verified by a full
  forward-playback audit, 0:00→end):
  - Ones: each block pops on its spoken number ("One"→1 … "Four"→4); "4 ones = 4" on "Four ones make four."
  - **10 → 1 ten:** at the moment "Ten." finishes there are exactly **10 ones and 0 tens**; the single ten
    forms only during **"Ten ones make one ten!"**, then "10 ones = 1 ten", then Tenny on "This is Tenny."
  - Build 34: 3 tens on "Here are three tens", 4 ones on "And here are four ones", **34** on "…make thirty-four."
  - Place value: the 3 highlights on "…tens place", the 4 on "…ones place", 30/4/30+4=34 on their lines.
  - Build 52: 5 tens, 2 ones, **52** each on their lines.
  - Compare: both numbers shown on the question; **no answer during the think-pause**; "52 > 34" only on
    "So fifty-two is greater than thirty-four."
- ✅ **Quantities always correct:** 4 ones; exactly 10 ones → 1 ten; 3+4 = 34; 5+2 = 52; compare = 8 rods / 6 cubes.
- ✅ **Design preserved:** Tenny, Ollie, SVG style, backgrounds, colors, story and concept unchanged.
- ✅ **New (requested) reward moment:** a ~1.5 s Tenny+Ollie hop + star burst + cheer sound fires the instant
  **34** appears, inside the existing pause before the next line — it does not change any number, caption, or timing.

## Deliverables
- **A. Synchronized video:** `animation/index.html` (Variant A) + 3 style variants (`toy_room`, `space`,
  `chalkboard`), all narration-synced. Recordable to MP4 (OBS/Game Bar; press **H** for a clean frame).
- **B. Editable project:** all source is editable — `index.html` engine + `sync.json` (timing source of truth),
  `subtitles.srt`, `narration_script.txt`, and `scratchpad/build_vo.ps1` (regenerates audio + sync.json).
- **C. This report.**

## Remaining limitations (honest)
1. **Draft voice.** The narration is a free Windows-TTS placeholder (robotic, and not cleared for commercial
   use per the brief). Replace it with a commercial voice (ElevenLabs/Azure) saved as `animation/voiceover.mp3`.
   **If you keep the exact same sentences and pacing**, the embedded timings still line up; if the new audio's
   sentence lengths differ, re-run `build_vo.ps1` (it rewrites `sync.json`) and I can re-embed the new times.
2. **Sentence-level sync** (not word-level): captions and beats align to each spoken sentence. Counting is
   finer because each number is its own clip, so each block still pops on its own spoken number.
3. **No pre-rendered MP4 / no background music** added here (no ffmpeg in this environment). Record the stage
   and drop a licensed music bed in your editor; both are documented in `PRODUCTION_PLAN.md`.
