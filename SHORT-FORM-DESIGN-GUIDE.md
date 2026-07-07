# Short-Form Content Visual Design Guide

A complete visual playbook for YouTube Shorts, TikTok, and Instagram Reels. Everything here is about how the video **looks** — framing, text, color, light, motion, and polish — down to the pixel. It applies to any niche or content type.

---

## Table of Contents

1. [Canvas & Platform Specs](#1-canvas--platform-specs)
2. [Safe Zones (Pixel-Level)](#2-safe-zones-pixel-level)
3. [Composition & Framing](#3-composition--framing)
4. [The First Frame & Hook Visuals (0–1.5s)](#4-the-first-frame--hook-visuals-015s)
5. [Typography & On-Screen Captions](#5-typography--on-screen-captions)
6. [Color System](#6-color-system)
7. [Lighting](#7-lighting)
8. [Camera & Image Quality](#8-camera--image-quality)
9. [Motion, Pacing & Edit Rhythm](#9-motion-pacing--edit-rhythm)
10. [B-Roll & Overlay Design](#10-b-roll--overlay-design)
11. [Graphics, Branding & Consistency](#11-graphics-branding--consistency)
12. [Platform-Specific Visual Differences](#12-platform-specific-visual-differences)
13. [Accessibility & Readability](#13-accessibility--readability)
14. [Pre-Publish Visual QC Checklist](#14-pre-publish-visual-qc-checklist)

---

## 1. Canvas & Platform Specs

### The one true canvas
- **Shoot, edit, and export at 9:16 — 1080 × 1920 px.** All three platforms natively display this. Design for it from the first second; never "fix it in the crop."
- Set your editing timeline to 1080×1920 **before** importing footage. Retrofitting a horizontal timeline into vertical always produces awkward crops.
- If you shoot in 4K (2160×3840), edit on a 1080×1920 timeline anyway — the extra resolution is your zoom/punch-in headroom (see §8).

### Aspect-ratio traps
- **Never letterbox 16:9 footage into a 9:16 frame raw** (a small horizontal strip floating in black). It screams "repurposed content" and viewers scroll. If you must use horizontal footage:
  - Punch in to fill the vertical frame (you lose the sides — compose around it), or
  - Stack it: footage in the top ~60%, bold caption text filling the bottom ~40% on a solid brand-color plate, or
  - Use a blurred, zoomed copy of the same clip as the background fill (acceptable, but the stacked-caption layout performs better).
- 4:5 and 1:1 exports are for **feed posts**, not Reels/Shorts/TikTok. Post 9:16 to the short-form surfaces; let Instagram auto-crop the feed preview (but design the center-crop to survive — see §12).

### Frame rate & duration targets
- **30fps** is the default for talking-head and most content. **24fps** if you want a slightly filmic feel (fine, but pick one and never mix on the same timeline).
- **60fps capture** only for footage you intend to slow down (interpret 60→30 for clean 50% slow motion).
- Duration sweet spots (visual pacing implication: shorter video = faster visual rhythm):
  - TikTok: 21–34s performs reliably; up to 60s if every second earns it.
  - Reels: 15–30s core; 30–60s for tutorials.
  - Shorts: up to 60s classic; 60–180s allowed but the feed still favors tight edits.

---

## 2. Safe Zones (Pixel-Level)

The platform UI (username, caption, sound, like/comment/share rail, progress bar) sits **on top of your video**. Anything under it is wasted or illegible.

On a 1080 × 1920 canvas, keep critical content (faces, text, product, CTA) out of these bands:

| Zone | TikTok | Instagram Reels | YouTube Shorts |
|---|---|---|---|
| **Top** (username, camera/search icons) | ~150 px | ~220 px | ~120 px |
| **Bottom** (caption, sound, nav bar) | ~320 px | ~420 px | ~180 px |
| **Right rail** (like/comment/share/profile) | ~120 px | ~110 px | ~110 px |
| **Left edge** | ~60 px | ~60 px | ~60 px |

### The universal action-safe box
To design once and post everywhere, keep all essential elements inside:
- **Horizontal:** 60 px from the left, 130 px from the right → a ~890 px-wide working column.
- **Vertical:** 250 px from the top, 420 px from the bottom → a ~1250 px-tall working band.
- Practically: **the middle ~65% of the frame is yours. The bottom quarter belongs to the platform.**

### Rules that follow from this
- **Primary caption text lives in the vertical center** — roughly y = 1150–1450 px (just below the subject's chest on a talking-head shot). Not the bottom. Bottom-placed captions get covered by the Reels caption box.
- Hook text can sit higher (y ≈ 300–500 px) above the subject's head.
- Never put a CTA, handle, or "link in bio" in the bottom 420 px — put it center-frame on its own end card.
- Build a **safe-zone overlay PNG** (1080×1920 with the bands marked at 30% red) and keep it as a toggleable top layer in your edit template. Check every video against it before export.

---

## 3. Composition & Framing

### Vertical rule of thirds
- Divide the frame into a 3×3 grid. In vertical video the **horizontal** third-lines matter most.
- **Eyes on the top third-line** (y ≈ 640 px). This is the single most common framing error — people center their face, leaving a huge dead forehead-to-top gap and cutting their chest where captions should go.
- Leave **headroom of roughly half a forehead** — enough that the hairline isn't clipped, not so much that the top quarter is empty ceiling.

### Talking-head framing distances
- **Tight (head + shoulders, cut at upper chest):** default for hooks, punchlines, emotional emphasis. Vertical video rewards intimacy — closer than feels natural on a horizontal camera.
- **Medium (waist-up):** for demonstrations, gesturing, holding a product/prop. Use as your "B" framing to cut between (see §9 punch-ins).
- Never frame so wide that the face is smaller than ~1/6 of frame height — on a phone screen that face is thumbnail-sized and loses connection.
- **Crop through limbs, not at joints.** Cut mid-forearm or mid-chest; a frame edge exactly at the wrist, elbow, or neck looks amputated.

### Lookroom & eyeline
- Look **into the lens**, not at your own preview. On a phone, the camera is at the top — eyes drift down to the screen and read as "avoiding eye contact."
- If you face slightly off-axis (interview style), leave lookroom: more empty space on the side you're facing.

### Depth layering
Flat subject-against-wall footage reads amateur. Build three layers:
1. **Foreground** (optional): something soft/out-of-focus at a frame edge — a plant leaf, a doorframe, an object on a desk.
2. **Subject:** you, sharply focused.
3. **Background:** at least 1–1.5 m behind you, with visible depth cues (a hallway receding, shelves, a practical lamp). Never stand flat against a wall — shadows land on it and the shot flattens.
- Your real environment is a free production designer: a workspace, tools of your trade, or anything relevant to the topic framed over your shoulder adds authenticity and authority no studio backdrop can.

### Reserving space for text
- Compose knowing text will exist. If captions go center-low, keep that band visually quiet (no busy pattern, no bright highlights behind where white text will sit).
- When a big text block occupies the top, shift yourself slightly low in frame; when text is mid-frame, offset yourself to one side (still inside the right-rail safe zone).

### Leading lines & angles
- Use environment lines (hallways, table edges, shelving, architectural lines) to point toward the subject.
- Slight **low angle** (camera at chest height angled up ~5°) reads confident/authoritative. Slight **high angle** reads casual/vloggy. Dead-level at eye height is the neutral default.
- Never shoot from below chin level at close range — the underside-of-face angle is unflattering on every human.

---

## 4. The First Frame & Hook Visuals (0–1.5s)

The first frame is your thumbnail, your ad, and your retention gate. Design it deliberately.

### Frame-one rules
- **Frame 1 must already be interesting.** No fade-from-black, no logo sting, no channel intro, no "hey guys" empty frame. The video starts *mid-motion, mid-scene, or mid-claim*.
- Start with **motion already happening**: a hand entering frame, an object being revealed, a walk-toward-camera already in progress. A static human who then starts moving reads as buffering.
- The hook text should be **on screen within the first 0.3s** (effectively frame 1), largest text in the whole video (see §5 sizing).
- **Test at thumbnail size:** shrink frame 1 to ~150 px tall. Can you still read the text and identify the subject? If not, redesign.

### Visual curiosity devices
- **Partial reveal:** show the *result* or the *problem* before context — the finished product, the broken thing, the shocking number — before you appear.
- **Unexplained object:** something in frame the viewer can't immediately parse buys 2–3 seconds of watch time.
- **Before/after tease:** flash the "after" for 0.5s first, then cut to the "before" and let the video be the journey back.
- **Pattern interrupt:** an unusual first frame (extreme close-up, dutch tilt, unexpected location) outperforms a standard talking-head opener — but only if the rest of the video pays it off.

### What to never do in second 1
- Fades, dissolves, or animated logo intros.
- Black frames or white frames (the algorithm's auto-thumbnail may grab them).
- Small text, watermarked stock footage, or a title card with no human/subject.

---

## 5. Typography & On-Screen Captions

Text is watched on mute, on a 6-inch screen, in sunlight, for 0.8 seconds. Every choice below serves that reality.

### Font selection
- **Heavy geometric or grotesque sans-serifs only.** Safe, proven picks: **Montserrat ExtraBold/Black, Archivo Black, Inter Black, Poppins Bold, Bebas Neue** (condensed — good for one-word slams, poor for sentences).
- Never: thin weights, serifs, scripts, condensed fonts for body captions, or novelty fonts. If a stroke is thinner than ~4 px at final size it shimmers and vanishes on compression.
- **Two fonts maximum per video** (usually: one for hook/headers, one for running captions), and they should be the *same two fonts in every video you ever post* (see §11 consistency).

### Size floor (on the 1080×1920 canvas)
- **Running captions:** minimum ~90 px cap height (~5% of frame height). Comfortable default: 100–110 px.
- **Hook text:** 2–3× the caption size — 200–300 px. It should feel almost uncomfortably big in the editor; it will feel right on a phone.
- **Never below 70 px for anything** the viewer must read. Legal-fine-print-sized text says "skip me."

### Chunking & line rules
- **Max 5–7 words on screen at once** for running captions. One phrase, one thought.
- **Max 2 lines** per caption block; 1 line preferred. Three lines = a paragraph = a scroll.
- Break lines at natural speech pauses, never mid-phrase ("this habit is / costing you money" ✓, "this habit / is costing you money" ✗).
- Center-aligned for captions. Left-aligned only for list overlays.

### Contrast treatment — pick ONE per video and keep it
1. **Stroke/keyline:** white text, black outline 8–12 px. The TikTok-native look. Works on any background.
2. **Drop shadow:** white text, shadow at 60–80% opacity, offset 0 px, blur 15–25 px (a soft glow-shadow, not a hard 45° offset — hard offsets look 2010).
3. **Background plate:** text on a solid rounded-corner box (brand color or black at 75–90% opacity). Most legible; slightly more "produced" feel. Padding inside the box: ~0.4× the cap height on all sides; corner radius ~20–24 px.
- White text is the default. Black text only on genuinely bright, uncluttered backgrounds — and still give it a white keyline.

### Emphasis & highlighting
- **One accent color** for keyword highlighting (see §6). Highlight 1–2 words per caption max — the number, the pain word, the payoff word ("this mistake costs you **$400** a year").
- Emphasis options, strongest to subtlest: color change → background-plate color flip → size bump (~15%) → bold-to-heavier weight. Never underline (reads as a link), never more than one emphasis device on the same word.
- **ALL CAPS** for hooks and short slams; **sentence case** for longer captions (all-caps paragraphs are slower to read). Add tracking of +2 to +5% to all-caps text; never negative tracking on heavy weights.

### Caption animation & timing
- **Pop-in per phrase** (scale 80→100% over 4–6 frames with a slight overshoot) or **karaoke word-highlight** (words appear/color as spoken). Both proven. Typewriter effects are too slow for shorts.
- Captions must be **frame-accurate to the voice**. A caption that leads or lags the audio by more than ~3 frames feels dubbed.
- Each caption block stays on screen long enough to be **read twice** at a normal pace (~0.35s per word, minimum 0.8s per block).
- Kill all caption text during pure-visual moments (a reveal, a before/after wipe) — text competes with the money shot.

### Punctuation & emoji
- Skip end-of-line periods in captions (they add visual noise); keep question marks and exclamation points (max one "!").
- Emoji: 0–1 per caption block, only when it adds meaning (🔥 on a bold claim, 💸 on a cost claim). Emoji as bullet points in list overlays is fine. Never a row of three emoji.

---

## 6. Color System

### Build a 3-color identity and never deviate
- **Base (60%):** your dominant environment tone — usually neutral (the real world: walls, furniture, clothing).
- **Secondary (30%):** a supporting brand tone used in text plates, lower-thirds, end cards.
- **Accent (10%):** ONE loud color for keyword highlights, arrows, circles, progress bars. This is the color viewers should associate with you.
- Apply **60-30-10** to every designed frame (end cards, text-heavy frames, thumbnails).
- Complementary pairs (blue/orange, teal/coral, purple/yellow) give maximum pop for the accent. If you already have brand colors, use those — consistency beats theory.

### Text contrast minimums
- Aim for **≥ 4.5:1 contrast** between text and whatever is behind it (WCAG AA). Practically: white text + dark stroke/plate clears this on any footage.
- Never rely on the footage staying dark/light behind text — footage moves. This is why every caption gets a stroke, shadow, or plate (§5), no exceptions.

### Grading baseline
- **Keep contrast.** Lifted, milky shadows (the faded "film look") lose viewers on small bright screens. Set a true black point and a true white point.
- **Saturation slightly above neutral** (+5–10%) — the feed is a wall of competing color; flat footage disappears. Do not push into neon skin.
- **Protect skin tones:** grade the shot, then check skin against memory (not against the vectorscope alone). Orange-teal grading on a talking head must stay subtle or you look seasick.
- **One grade per video.** Cutting between a warm A-cam and a cool B-roll clip reads as a mistake. Match all clips to a single reference frame before creative grading.
- Save your grade as a **preset/LUT and reuse it forever** — grade consistency is brand consistency.

### Backgrounds & wardrobe
- Wardrobe should contrast with the background (dark shirt / light background or vice versa). Avoid fine stripes and tight checks — they moiré on camera and shimmer after compression.
- Avoid wearing your accent color — it kills the highlight system's pop.
- Pick a signature wardrobe style (or literal signature garment) and repeat it — it becomes part of your visual identity.

---

## 7. Lighting

### The default setup (talking head, ~$0–150)
- **Key light:** the main light, 45° off camera axis, slightly above eye level, aimed down ~15°. A window with sheer curtains is a perfect free key. If buying: one soft LED panel or a bulb-in-softbox.
- **Fill:** bounce, not a second light — a white wall, foam board, or just the room. Fill should be 1–2 stops below key (visible soft shadow on the far cheek = dimension; no shadow = flat passport photo).
- **Back/rim light (the pro tell):** a small light behind and above you, opposite the key, skimming your hair and shoulder line. This separates you from the background more than anything else. A cheap RGB tube or even a lamp works.
- **Background practicals:** a warm lamp or LED strip in the background layer adds depth and color interest for ~$20.

### Non-negotiable rules
- **One color temperature per scene.** Pick daylight (5600K) or tungsten (3200K) and make every source match — including the window. Mixed blue-window + orange-lamp on a face is the most common amateur giveaway. Set the camera's white balance manually to match; never leave it on auto (it drifts mid-clip).
- **No bare overhead lights as the key.** Ceiling lights carve raccoon-eye shadows and a nose shadow onto the upper lip. Turn them off or overpower them with your key.
- **Never sit with a bright window behind you** unless you're deliberately silhouetting. The camera exposes for the window and your face goes muddy.

### Outdoors / on location
- **Open shade is your studio:** the shadow side of a building, under an awning, inside a doorway. Soft, even, flattering.
- **Overcast is a gift** — the whole sky is a softbox. Shoot the talky parts on those days if you can.
- Avoid harsh noon sun on faces (hard shadows, squinting, blown highlights). If unavoidable: put the sun **behind** the subject (backlight) and expose for the face; the sky blows out — acceptable.
- Dim or cramped locations: a small on-camera LED or a light aimed at the ceiling (bounce) beats direct harsh light. Some grit is authentic — but the face must always read.
- **Golden hour (first/last hour of sun)** makes any exterior shot look expensive. Schedule outdoor b-roll for it when possible.

---

## 8. Camera & Image Quality

### Capture settings (phone or camera)
- **4K/30 capture, 1080×1920 delivery.** The 2× resolution surplus lets you punch in up to ~200% in the edit with zero quality loss — this is how one static camera becomes a two-camera shoot (§9).
- **Shutter ≈ 1/60 at 30fps** (the 180° rule: shutter = 2× frame rate). Faster shutters make motion stuttery; on phones, use a camera app with manual control if you can, or don't fight it.
- **Lock exposure and focus** (tap-and-hold on phones) before rolling. Auto-exposure pumping mid-take is unfixable in post.
- **Turn off** auto-HDR "scene enhancement" modes for talking heads — they flatten faces and cause grade-resistant footage. Record in a standard profile unless you genuinely grade log footage.

### Lens choice & distortion
- Phone lenses: **1× main lens** at ~arm's-length-plus reads natural. **0.5× ultrawide** at close range bulges the nose and stretches the frame edges — use it only for environment/POV shots, never a close talking head. **2–3× tele** from farther back is the most flattering face rendering if you have light and a tripod.
- Keep the subject out of the outer 15% of an ultrawide frame — edge distortion warps bodies.

### The unglamorous fundamentals
- **Wipe the lens on your shirt before every single clip.** A greasy phone lens produces the hazy bloom that instantly marks footage as amateur. This is the highest ROI habit in this entire document.
- **Stabilization:** locked-off tripod for talking heads; deliberate handheld with elbows tucked for walk-and-talks and location tours (slight motion = energy and authenticity; wobble = nausea). Use the phone's built-in stabilization; gimbals only if you already own one.
- Shoot **b-roll clips of at least 8–10 seconds** even if you'll use 2 — you need handles for speed ramps and cut choices.
- Record in the phone's **highest bitrate option** (e.g., HEVC high efficiency off / ProRes on if storage allows) — compression happens twice more before viewers see it (your export + the platform).

---

## 9. Motion, Pacing & Edit Rhythm

### The retention pulse
- **Something visual must change every 1.5–3 seconds:** a cut, a punch-in, a caption pop, a b-roll insert, a graphic, a zoom. Not chaos — rhythm. Watch your draft and tap a finger at each visual event; gaps longer than 3 seconds are where viewers leave.
- Front-load: the first 10 seconds should change nearly every 1–1.5s; you can relax to 3s intervals once the viewer is invested.

### Punch-ins instead of jump cuts
- When you cut a pause out of a single-camera take, **change the scale 10–20%** on one side of the cut (100% → 115%, then back). The frame change legitimizes the cut. Alternate between your "wide" (100%) and "tight" (115–130%) crops like a two-camera interview.
- Small rotations (±1°) or a slight reposition also sell a cut; identical-frame jump cuts read as stutters.

### Zoom psychology
- **Push-in (slow zoom toward)** = emphasis, tension, "listen to this part." Use on key claims. Keep it subtle: 100→108% over 2–3 seconds.
- **Snap zoom (instant punch)** = comedy beat or shock emphasis.
- **Pull-out** = reveal (start tight on a detail, widen to show context — perfect for before/after and "look at the whole thing" moments).
- Every static clip longer than 3 seconds should have at least a 3–5% drift (slow scale or position ease) — imperceptible, but the frame never feels dead.

### Transitions
- **Hard cuts win. Use them 95% of the time.** Cross-dissolves, wipes, spins, and glitch packs read as 2016 YouTube.
- The three acceptable exceptions, used at most once or twice per video:
  1. **Whip pan** — camera whips off subject A, cut mid-blur, whips onto subject B. Great for location changes.
  2. **Match cut** — a hand closes a lid → cut → a hand opens a different lid; shapes/motion align across the cut.
  3. **Mask/wipe reveal** — a passing object (a person walking through frame, a door) wipes to the next scene. Also the canonical **before/after wipe** (§10).
- **Cut on action:** cut while a hand is mid-motion, not after it settles. Motion across the cut hides the seam.

### Speed
- **Speed ramps** (slow → fast → slow within one clip) add production value to b-roll: ramp fast through the boring middle of a movement, slow on the moment of impact/reveal.
- Timelapse for long processes (a build, a setup, a transformation): shoot locked-off, play at 800–2000%, hold the final result at normal speed for 1.5s.
- Slow motion only from true 60fps footage, and only on moments that deserve savoring — a satisfying snap, a pour, a reveal.

---

## 10. B-Roll & Overlay Design

### Coverage ratio
- For talking-head-driven videos, aim to cover **30–50% of the runtime with b-roll** over the continuing voice. Full-screen face for 45 straight seconds underperforms the identical audio with cutaway coverage.
- Every noun you say is a b-roll prompt: name a thing, show the thing. Literal beats clever.

### Picture-in-picture (PiP)
- Keep yourself visible during screen/product footage with a PiP: a rounded-rect (~24 px radius) or circle, **280–360 px wide**, bottom-left or top-left corner (inside safe zones), with a 4–6 px stroke in your accent color or a soft shadow to lift it off the footage.
- PiP face must still be lit and legible — don't PiP a dark webcam blob.

### Screenshots & screen recordings
- Never paste a raw full screenshot. Style it: crop to the relevant region, place on your brand-color or dark background, **rounded corners 24–32 px, soft drop shadow (0 offset, 40 px blur, 40% opacity)**, scale so the relevant text is readable at phone size.
- **Animate a slow zoom-pan** (Ken Burns) across any static image on screen longer than 2 seconds.
- Redact anything sensitive (names, addresses, phone numbers, account details) with a solid brand-color bar — not a blur, which can be reversed and looks messier.

### Annotations
- Circle/arrow/underline callouts in the **accent color only**, stroke weight 8–12 px, animated on (draw-on or pop-in over 4–6 frames) rather than blinking into existence.
- One annotation on screen at a time. Two arrows = the viewer looks at neither.

### Before/after
- **Split-screen:** vertical stack (before on top, after on bottom) fits 9:16 naturally; label each half with a small caps tag ("BEFORE" / "AFTER") in consistent corner positions.
- **Wipe:** hold the before shot 1s, wipe left-to-right (or top-to-bottom) to the after — shoot both from a **tripod at the identical position** or the effect dies. Mark tripod feet with tape for shoots that span hours.
- **Flash-cut compare:** before/after/before/after at 8-frame intervals for a punchy ending beat.
- Always hold the final "after" a beat longer than feels necessary — it's the payoff frame.

### Proof shots
- Receipts, stats dashboards, readouts, results: shoot or screenshot them close, in focus, held steady 1.5s+, and boost with a subtle zoom. Numbers are the most rewatched frames — make them legible.

---

## 11. Graphics, Branding & Consistency

### The consistency doctrine
Every video you post should be recognizable as yours **with the sound off, in half a second**. That comes from repeating: the same 2 fonts, the same 3 colors, the same caption style, the same grade, the same watermark position, the same end-card layout. Novelty goes in the *content*; the *design system* never changes.

### Watermark
- Small handle/logo, **top-left or top-right corner inside safe zones** (≈ x 70–90, y 260 on the left), **35–45% opacity**, white or single-color version (never the full-color logo — too loud).
- Height ≈ 40–50 px. It should be findable, not readable at a glance.

### Lower-thirds
- Use once, early (2–4s in), to say who you are: name + one-line credibility ("Alex • 10 yrs in the industry"). Slide-in from the left, hold 2.5–3s, slide out.
- Design: accent-color tab or bar + name in your header font, ~60 px cap height — deliberately smaller than captions so it doesn't compete.

### End frame / CTA (final 1–2 seconds)
- One designed, reusable end card: solid brand background, your face or logo, **one** CTA ("Follow for more" / "Send this to someone who needs it"), your handle. Center-frame, giant text, nothing in the bottom 420 px.
- **Max 2 seconds.** Long outros crater your completion rate, and completion rate feeds distribution. Better yet: deliver the CTA as a caption over the final content beat and skip the card entirely on shorter videos.
- Never end with "like and subscribe" boilerplate visuals — end on the payoff, CTA riding on top.

### Progress & list devices
- Multi-point videos ("3 mistakes you're making with ___"): a persistent small counter chip ("1/3") top-center or a thin accent-color progress bar (6–8 px) along the very top edge. Both signal "this is structured and short," which holds viewers.
- Each list item gets an identical title-card treatment (same position, animation, style) — the repetition is the design.

### Template everything
- Build one master editing project per format (talking-head explainer, location tour, before/after) with the safe-zone overlay, caption presets, watermark, end card, and grade already in place. Every new video starts from the template. This is the difference between 4 hours and 40 minutes per edit — and it enforces consistency automatically.

---

## 12. Platform-Specific Visual Differences

Post the same 9:16 master everywhere, with these per-platform adjustments:

### TikTok
- **Native-raw wins.** Slightly less polish is a feature: handheld energy, in-app-style text (their Classic font vibe), trend-aware visuals. Over-produced footage can *underperform* here.
- Text style can lean toward TikTok's built-in caption look — viewers read it as "one of us."
- The right-rail engagement icons are used constantly here — be extra strict about the 120 px right margin.

### Instagram Reels
- **Most polish-tolerant platform.** Aesthetic-forward: your grade, wardrobe, and background quality matter most here.
- **Design the cover:** Reels shows in the profile grid cropped to 3:4 (and 1:1 contexts). Choose/design a cover frame whose subject and title text sit in the **center 1080×1080** of the 1080×1920 frame; add a title in your header font. A consistent cover template makes your grid look like a series.
- Reels' caption overlay is the tallest (bottom ~420 px) — the strictest bottom safe zone of the three.

### YouTube Shorts
- The **title text below the video** does discovery work the on-screen visuals don't have to. But the Shorts shelf shows a raw first frame — frame 1 still must pass the thumbnail-size test (§4).
- Shorts viewers tolerate slightly longer, more tutorial-shaped content — pacing can breathe closer to the 3s interval end of the pulse.
- Shorts can convert to your long-form channel: visual branding here should match your long-form thumbnails' style (same fonts/colors) if you have one.

### Cross-posting hygiene
- **Never post a TikTok-watermarked export to Reels or Shorts** — both platforms detect and suppress watermarked reuploads. Export a clean master from your editor; upload natively to each platform.
- Export settings for the master: **1080×1920, H.264, High profile, 12–16 Mbps VBR, AAC 320 kbps audio, Rec.709 color space, 30fps.** (HEVC/H.265 is fine if your editor's H.264 banding is bad, but H.264 uploads are the safest cross-platform.)
- Re-check text against each platform's safe zones if you ever move captions per platform (usually unnecessary if you designed to the universal box in §2).

---

## 13. Accessibility & Readability

- **Captions are always on.** 60–85% of short-form is watched muted or in captions-preferred contexts. A video without burned-in or platform captions forfeits most of its audience. Burned-in styled captions (§5) + platform auto-captions enabled = both bases covered.
- **Colorblind-safe accents:** avoid red-vs-green as your only distinction (before/after labels, good/bad indicators). Blue/orange is the most colorblind-robust complementary set. Pair color with a shape or label ("✗/✓", "BEFORE/AFTER") — never color alone.
- **Readable-twice rule** (§5): every text block stays up long enough to read twice. Viewers who need one read get comfort; slow readers get the message at all.
- **No strobe:** avoid full-frame flashes faster than 3 per second (photosensitivity risk, and platforms may limit distribution). Flash-cut compares (§10) at 8-frame intervals sit safely under this.
- **Don't rely on tiny detail:** if the payoff is a number on a screen, punch in until it fills a third of the frame width. Design for a 6-inch screen at arm's length in daylight — the worst realistic viewing condition.

---

## 14. Pre-Publish Visual QC Checklist

Run this on every video before export/upload:

- [ ] **Safe-zone pass:** toggle the overlay — no faces, text, or CTAs in the platform UI bands (esp. bottom 420 px, right 130 px).
- [ ] **Frame-1 test:** scrub to the first frame, shrink to thumbnail size — subject identifiable, hook text readable, no black/blank frame.
- [ ] **Mute test:** watch the whole video with sound off — does it still make sense and hold attention? (This is how most people will see it.)
- [ ] **Text-speed test:** can you comfortably read every caption twice before it leaves?
- [ ] **Caption sync:** captions land within ±3 frames of the spoken words.
- [ ] **Pulse check:** no visual gap longer than ~3 seconds without a cut/zoom/text/graphic change.
- [ ] **Grade consistency:** all clips match; skin tones look human; true blacks present.
- [ ] **Brand pass:** correct 2 fonts, correct 3 colors, watermark in position, end card ≤ 2s.
- [ ] **Contrast pass:** every caption survives its busiest background moment (scrub behind each text block).
- [ ] **Redaction pass:** no names, addresses, plates, or private details visible in any footage.
- [ ] **Lens/focus pass:** no hazy bloom, no missed-focus clips that slipped through.
- [ ] **Export:** 1080×1920, H.264 12–16 Mbps, Rec.709, 30fps, clean master (no platform watermarks).
- [ ] **Per-platform:** Reels cover frame chosen (center-crop safe); Shorts title written; native upload to each platform.

---

## Quick-Reference Card

| Element | Spec |
|---|---|
| Canvas | 1080 × 1920 (shoot 4K) |
| Working area | Center ~65%; bottom 420 px is the platform's |
| Eyes | Top third-line (y ≈ 640) |
| Caption size | 90–110 px cap height, max 5–7 words, max 2 lines |
| Hook text | 200–300 px, on screen at frame 1 |
| Fonts | 2, forever (e.g., Archivo Black + Inter Black) |
| Colors | 3 (60-30-10); one accent for all highlights |
| Text contrast | ≥ 4.5:1 via stroke, shadow, or plate — always |
| Visual change | Every 1.5–3 s |
| Punch-in cuts | 10–20% scale change per cut |
| Transitions | Hard cuts; whip/match/mask rarely |
| Grade | One preset, contrast intact, skin protected |
| White balance | Manual; one color temp per scene |
| Watermark | Top corner, 35–45% opacity, ~45 px |
| End card | ≤ 2 s, one CTA, center-frame |
| Export | H.264, 12–16 Mbps, Rec.709, 30fps, no watermarks |
