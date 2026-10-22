# 🚑 Bernie's Disaster Relief English Studio
### Interactive Transcript, Lexicon Sanctuary & Field Homework Portal

**Student:** Bernie (Bernarda) — Humanitarian Aid & Disaster Relief Coordinator (Buenos Aires, Argentina 🇦🇷)  
**Tutor:** Louie (Lewis O'Shea)  
**Live GitHub Pages Deployment:** [https://log210788.github.io/bernie/](https://log210788.github.io/bernie/)

---

## 🌟 Overview & Architecture

This repository contains the personalized **Peaceful Interactive Transcript & Vocabulary Sanctuary** web application (`index.html`) alongside structured Markdown lesson plans and quick-reference cheat sheets tailored to Bernie's real-world disaster relief operations.

### Key Pillars (from `TEMPLATE_INSTRUCTIONS_FOR_AI.md`):
1. **Full Cleaned Transcript (00:00 – 53:22):** Every spoken turn organized into 6 chronological chapters with exact timestamps, instant search, speaker filtering, and Web Speech audio playback.
2. **Forensic Speech-to-Text Corrections:** Automated note-taker mishearings (hearing *"Bernie"* as *"Benny"*, *"shortage of water"* as *"shorter the water"*, *"injuries"* as *"adventure"*, *"whistle"* as *"weekly / silver"*) are cleanly fixed and flagged with toggleable `✨ Fixed` badges.
3. **48 Inline Vocabulary Items & Sticky Spotlight:** Flagged terms with IPA phonetics, Argentine Spanish operational equivalents, definitions, and Tippy.js popover cards.
4. **Vocabulary Dictionary Tab:** Searchable 48-item lexicon with a "Jump to Transcript" button that scrolls smoothly and pulses the target turn with a golden glow.
5. **Strengths & Phrasing Polishes Tab:** 6 celebrated natural expressions Bernie used brilliantly, followed by 6 gentle phrasing polishes and the complete ASR correction log.
6. **Tactical Field Protocols Tab:** 4 in-depth operational analyses covering:
   - *Perimeter Safety & The Urgent Imperative*
   - *Acoustic Search & The Silence Discipline*
   - *Safe Zone vs. Shelter (Field Logistics)*
   - *Verbal Grounding & Psychological First Aid*
7. **Peaceful Practice Sanctuary:** Flippable flashcard deck with pronunciation, a 6-question field decision quiz with canvas confetti, and roleplay preparation missions.
8. **Calming Atmosphere:** Built-in procedural Web Audio API ambient soundscapes (Gentle Breeze, Soft Rain, Warm Hearth) and adjustable HTML5 Canvas falling leaves.

---

## 📚 Repository Structure

- [`index.html`](./index.html): Self-contained single-page interactive application (Tailwind CSS, Lucide icons, GSAP, Tippy.js, Canvas-Confetti, Web Audio API).
- [`.nojekyll`](./.nojekyll): Ensures GitHub Pages bypasses Jekyll build steps.
- [`field-cheat-sheet.md`](./field-cheat-sheet.md): Offline mobile quick-reference cheat sheet for field deployments.
- [`lesson-01-emergency-disaster-relief.md`](./lesson-01-emergency-disaster-relief.md): Lesson 1 notes & exercises.
- [`lesson-02-triage-logistics-sitrep.md`](./lesson-02-triage-logistics-sitrep.md): Lesson 2 notes & exercises.
- [`lesson-03-crowd-safety-locating-victims.md`](./lesson-03-crowd-safety-locating-victims.md): Lesson 3 notes & exercises.
- [`transcripts/`](./transcripts/): Raw conversation transcripts from automated note-takers.
- [`push.bat`](./push.bat): One-click deployment script to GitHub Pages.
