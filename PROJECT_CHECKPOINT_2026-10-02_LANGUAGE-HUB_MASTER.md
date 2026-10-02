# LANGUAGE-HUB--LEARNING · MASTER PROJECT CHECKPOINT

**Date:** 2026-10-02  
**Current completed track:** LANGUAGE SKILLS → Reading + Listening  
**Architecture standard:** Area → Sub-skill → Micro-skill → Detail

---

## 1. PROJECT PURPOSE

The project is being built as a professional language-learning hub with three main platforms:

1. 📚 Language Skills
2. ⚙️ Language Systems
3. 🎯 Language Competence

The goal is not merely to list topics. Each platform must eventually open progressively deeper learning layers so the student can see:

**What is it? → Why does it matter? → What do I learn? → What do I practise? → What micro-skill do I build? → What do I finally gain?**

---

# 2. GLOBAL UI / NAVIGATION STANDARD

The following navigation model is established as the project standard and must be preserved across pages:

- Professional MB logo
- Home button
- 📚 Language Skills
- ⚙️ Language Systems
- 🎯 Language Competence
- Floating circular navigation buttons
- Previous / Next navigation where a page belongs to a sequence
- Clean, compact, professional layout
- Avoid unnecessary page clutter
- Deep information should be progressively revealed rather than dumped onto one page

---

# 3. LANGUAGE SKILLS · CURRENT STATUS

The Language Skills platform is the current active learning-skill area.

The four major skills are:

1. Reading
2. Listening
3. Speaking
4. Writing

## Current progress

| Skill | Status |
|---|---|
| Reading | Structure developed through Area → Sub-skill → Micro-skill architecture |
| Listening | Structure developed through Area → Sub-skill → Micro-skill architecture |
| Speaking | Not yet developed |
| Writing | Not yet developed |

---

# 4. READING · CURRENT CHECKPOINT

Reading has been developed first and serves as the main architectural reference.

## Reading hierarchy

**Reading**
→ 16 Areas
→ Sub-skills
→ Micro-skills
→ Micro-skill Detail

The Reading structure was deliberately expanded so that the final visible level is not just a label: each level has its own explanation and purpose.

### Required information model

For each Area:
- Area title
- Area explanation
- Area purpose / role in reading development

For each Sub-skill:
- Sub-skill title
- Its own explanation
- What it trains
- Why it matters
- What the learner should do / gain

For each Micro-skill:
- Specific micro-skill name
- Clickable entry
- Dedicated detail layer
- Explanation of the micro ability
- Learning / mastery purpose

### Reading Full Map UI standard

Reading's Full Micro-Skills Map uses a clean progressive Dropdown / Accordion model:

**Area ▾**
→ **Sub-skill ▾**
→ **Micro-skills**

Default state is closed to keep the page clean.

This Reading Full Map presentation is the visual standard to reproduce for Listening and later skills.

### Important Reading issue already tracked

At one point the live Reading page appeared to show two `Open Full Micro-Skills Map` links although the GitHub source contained one. This must remain a known verification concern until live rendering is confirmed if it reappears.

---

# 5. LISTENING · CURRENT CHECKPOINT

Listening has now been built using the same deep architecture as Reading.

## Listening hierarchy

**Listening**
→ **16 Areas**
→ **64 Sub-skills**
→ **320 Micro-skills**
→ **Micro-skill Detail**

The target architecture is:

**Area → Sub-skill → Micro-skill → Detail**

## Listening Areas

The master map contains 16 major areas, including:

1. Listening Foundations
2. Literal Comprehension
3. Gist & Main Idea
4. Listening for Detail
5. Prediction & Anticipation
6. Inference & Implication
7. Vocabulary & Grammar in Speech
8. Organisation & Discourse
9. Speaker Purpose & Intention
10. Tone, Attitude & Stance
11. Multiple Speakers & Interaction
12. Critical Listening
13. Note-taking & Synthesis
14. Speed, Fluency & Real-time Processing
15. Listening Strategies & Task Management
16. Listening-to-Response Transfer

The master file is:

`LISTENING_MICRO_SKILLS_MASTER.md`

It contains the Area → Sub-skill → Micro-skill hierarchy.

## Listening Full Map UI

Listening Full Micro-Skills Map was changed to match Reading's cleaner architecture:

- 16 Areas are Dropdown / Accordion sections.
- Each Area opens to reveal its Sub-skills.
- Each Sub-skill is itself a Dropdown / Accordion.
- Micro-skills appear inside the opened Sub-skill.
- Micro-skills are clickable.
- Clicking a Micro-skill leads to its Detail page.
- All sections are closed by default.
- The page no longer displays the entire information tree at once.
- Floating navigation is preserved.

### Current Listening Full Map file

`listening-micro-skills.html`

### Important technical fix completed

The Full Map initially showed:

`Unable to load the master map.`

The cause was the JavaScript/master-map loading/parsing path. The page was corrected so it loads `LISTENING_MICRO_SKILLS_MASTER.md` and generates the nested Dropdown structure.

Latest known fix commit:

`25b6b5c9aa792937a28c29b8023ce1ec3c12aa46`

The Listening Full Map was successfully restored after that fix.

---

# 6. LISTENING FILES / PATHS

Known core Listening files:

- `listening.html`
- `listening-area.html`
- `listening-micro-skills.html`
- `listening-micro-detail.html`
- `LISTENING_MICRO_SKILLS_MASTER.md`

Representative drill-down path:

**Listening Master**
→ `01 · Listening Foundations`
→ `Sound Discrimination`
→ Micro-skills
→ `Phoneme Discrimination`
→ Micro-skill Detail

The Area links were changed to direct links so the drill-down does not depend unnecessarily on JavaScript-generated navigation.

---

# 7. WHAT HAS BEEN COMPLETED

## Platform structure

- Three main platforms established.
- Global navigation concept established.
- Floating circular navigation standard established.
- Previous / Next navigation standard established.

## Reading

- 16-Area architecture established.
- Sub-skill layer established.
- Micro-skill layer established.
- Micro-skill detail concept established.
- Clean Dropdown Full Map established as the visual reference.
- Reading architecture is currently treated as the baseline model.

## Listening

- 16-Area architecture established.
- 64 Sub-skill target structure established.
- 320 Micro-skill target structure established.
- Micro-skill detail pathway established.
- Direct Area navigation fixed.
- Full Map converted to clean nested Dropdowns.
- Full Map loading bug fixed.
- Floating navigation retained.

---

# 8. WHAT REMAINS

## Language Skills

### Listening

The structural map is currently in place, but the next deeper phase should be quality/content expansion and verification:

- Verify all 16 Areas individually.
- Verify all Sub-skill pages individually.
- Verify all Micro-skill links individually.
- Ensure each Area has its own proper explanation.
- Ensure each Sub-skill has its own proper explanation.
- Ensure each Micro-skill has meaningful detail rather than placeholder text.
- Ensure the Detail pages explain what the micro-skill does, why it matters, how it is practised, and what mastery looks like.
- Verify Previous / Next navigation throughout the Listening hierarchy.
- Verify mobile/responsive presentation if needed.

### Speaking

Not yet built.

When started, use the same architecture:

**Speaking → Areas → Sub-skills → Micro-skills → Detail**

Do not simply copy Reading/Listening labels; the actual speaking-learning architecture must be designed specifically for speaking.

### Writing

Not yet built.

When started, use the same deep architecture but design the Areas/Sub-skills/Micro-skills specifically for writing development.

---

# 9. NEXT MAJOR PHASE

Do NOT jump randomly between skills.

Recommended sequence:

1. Stabilise and verify Listening.
2. Build Speaking from zero using the established architecture.
3. Build Writing using the same architectural standard.
4. Return to Language Systems.
5. Develop Language Competence.
6. Then expand individual micro-skills into full learning/assessment/practice systems.

---

# 10. CORE DESIGN RULE FOR FUTURE WORK

The project must always be built **layer by layer**.

Never present a flat list when a deeper educational hierarchy is intended.

Correct model:

**Platform**
↓
**Skill**
↓
**Area**
↓
**Sub-skill**
↓
**Micro-skill**
↓
**Micro-skill Detail**
↓
**Practice / Application / Mastery**

Every level should answer its own educational question.

The student should always know:

- Where am I?
- What am I learning here?
- Why am I learning it?
- What exactly should I be able to do?
- What is the next level?
- What have I gained after mastering this level?

---

# 11. CURRENT PROJECT STATE

**Reading:** architectural reference / substantially developed.  
**Listening:** architectural build complete; verification and content-depth work remain.  
**Speaking:** pending.  
**Writing:** pending.  
**Language Systems:** pending.  
**Language Competence:** pending.

**Current stopping point:** Listening Full Micro-Skills Map is working again with the clean Reading-style Dropdown architecture.

**Next session should begin from this checkpoint, not from scratch.**
