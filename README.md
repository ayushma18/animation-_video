# Place Value Pals — Tens Town & Ones Town
### A ~2-minute animated educational video for Grade 1 (USA) teaching Place Value: Tens & Ones

Built as a deterministic, **mathematically-exact** HTML animation (base-10 blocks are generated from the numbers, so the quantities can never be wrong), then rendered to a standard MP4 with synced narration + sound effects.

![status](https://img.shields.io/badge/status-complete-brightgreen) ![res](https://img.shields.io/badge/1920x1080-16%3A9-blue) ![len](https://img.shields.io/badge/duration-1%3A52-orange)

---

## 📺 The video
- **`Final/Place_Value_Tens_Ones_1080p.mp4`** — the final video.
  - 1920×1080, 16:9, **1:52**, H.264 (High, yuv420p/bt709) + AAC 48 kHz, faststart.
  - Narration + sound effects, fully synchronized with the animation and subtitles.
  - > The narration is a **free draft TTS voice** (placeholder, not commercially licensed). Replace `animation/voiceover.mp3` with a commercial voice for final/commercial use.

## ▶️ The animation (editable source)
Open any of these in Chrome/Edge and press **Play** (press **H** to hide the UI for clean recording):
- `animation/index.html` — **Variant A · Storybook** (recommended)
- `animation/toy_room.html` — Variant B · Toy Room
- `animation/space.html` — Variant C · Space
- `animation/chalkboard.html` — Variant D · Chalkboard
- `animation/compare.html` — side-by-side chooser

All four share one engine; the narration audio is the **master clock**, and every visual beat + subtitle is driven from measured audio timestamps in `animation/sync.json`.

## 🗂 Structure
```
Place_Value_Animation/
├── Final/            # final MP4
├── animation/        # the animation (HTML), subtitles.srt, sync.json, voiceover.wav (draft), narration_script.txt
├── context/          # CHATLOG.md + session-export.zip (full build conversation & screenshots)
├── Characters/ Backgrounds/ Blocks/ Audio/ Music/ SFX/ Fonts/   # asset folders (see PRODUCTION_PLAN)
├── Project/          # editor project files (if you assemble in an editor)
├── PRODUCTION_PLAN.md  # full production bible (storyboard, script, prompts, editing, licensing, QA)
├── SYNC_REPORT.md      # A/V/subtitle synchronization report
└── LICENSES.md         # asset & license record
```

## 🔧 How the MP4 is produced
Headless Chromium plays the animation and a timestamped screencast captures every frame; the sound effects are rendered offline (WebAudio → WAV) and mixed under the narration; FFmpeg encodes H.264/AAC. Script: see the build pipeline described in `SYNC_REPORT.md`. (Requires `playwright` + `imageio-ffmpeg`.)

## ✅ Covers the assignment
Tens, ones, 10 ones = 1 ten (animated merge), building 2-digit numbers (34, 52), digit position → value, a place-value chart (30 + 4 = 34), a brief comparison (52 > 34) with a think-pause, a celebration reward, and a clear takeaway — English, Grade 1, 16:9 1080p, ≤ 2 min, with narration, SFX, subtitles, and editable source.

---
*Educational concept, characters (Tenny & Ollie), and all math visuals are original. See `LICENSES.md`.*
