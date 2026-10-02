# LANGUAGE HUB — PROJECT CHECKPOINT

**Date:** 2026-10-02
**Repository:** `don223871-ui/LANGUAGE-HUB--LEARNING`
**Status:** Architecture established; Reading drill-down is in progress and is NOT yet marked complete.

## 1. PROJECT PURPOSE

Build a professional, student-facing Language Learning Hub in which language learning is organised hierarchically rather than as flat lists.

Core principle:

`Platform → Main Area → Sub-area → Sub-skill → Micro-skill → Learning / Practice / Assessment / Transfer`

The learner should always move one layer deeper by clicking, with no jumping directly from a master list to an undifferentiated long page.

## 2. TOP-LEVEL PLATFORMS

The Home page currently uses three main learning platforms:

1. 📚 **Language Skills**
2. ⚙️ **Language Systems**
3. 🎯 **Language Competence**

These are the three major routes of the Hub.

## 3. GLOBAL NAVIGATION STANDARD

The intended navigation is present throughout the platform design and must be preserved on every page:

- Professional circular **MB / mb logo**
- **Home**
- **📚 Language Skills**
- **⚙️ Language Systems**
- **🎯 Language Competence**
- Floating circular **Previous** button
- Floating circular **Next** button

The navigation is intended to remain compact, professional and floating rather than occupying large page space.

## 4. LANGUAGE SKILLS — CURRENT STRUCTURE

Language Skills contains four core skills:

- 📖 Reading
- 🎧 Listening
- 🗣️ Speaking
- ✍️ Writing

The current development priority is **Reading**.

Listening, Speaking and Writing have NOT yet been developed to the same deep level and remain future work.

## 5. READING — MASTER ARCHITECTURE

Reading is being designed as a true drill-down learning architecture.

Current intended hierarchy:

`Reading → 16 Master Areas → Sub-skills → Micro-skills → Detailed Learning Architecture`

The 16 Reading Master Areas are:

01. **Reading Foundations**
02. **Literal Comprehension**
03. **Main Idea & Gist**
04. **Supporting Details**
05. **Skimming**
06. **Scanning**
07. **Vocabulary in Context**
08. **Inference & Implication**
09. **Reference & Cohesion**
10. **Text Organisation**
11. **Writer's Purpose**
12. **Tone, Attitude & Stance**
13. **Fact, Opinion & Claim**
14. **Argument & Evidence**
15. **Critical Reading**
16. **Response & Synthesis**

## 6. READING — IMPORTANT DESIGN DECISION

A previous version incorrectly presented Reading as a long static page containing all sub-skills.

That approach is rejected.

The correct model is:

### LEVEL 1
**Reading Master Map**

The learner sees the 16 Areas as clickable cards.

### LEVEL 2
**Individual Reading Area**

Clicking an Area opens only that Area and displays its Sub-skills as clickable cards.

### LEVEL 3
**Individual Sub-skill**

Clicking a Sub-skill opens its own learning page.

### LEVEL 4
**Micro-skills**

The Sub-skill must then be broken into smaller teachable components.

### LEVEL 5
**Full Learning Detail**

Each Micro-skill / learning component should eventually explain:

- What it is
- Why it matters
- What the learner needs to learn
- What the learner actually does
- How to practise it
- Typical difficulties / errors
- How mastery is checked
- Expected learner outcome
- Transfer to other skills
- Appropriate progression / level where relevant

## 7. CURRENT READING FILES / WORK ALREADY DONE

### `reading.html`
Updated as the Reading Master Map.

Its purpose is now to present the **16 clickable Reading Areas** rather than a flat content dump.

Navigation concept:

`Reading → choose one of 16 Areas`

### `reading-area-01.html`
Created for:

**01 · Reading Foundations**

It currently contains clickable Sub-skill cards for:

- 01.1 Word Recognition
- 01.2 Word Segmentation
- 01.3 Sentence Processing
- 01.4 Reading Fluency

Navigation:

`Reading → Reading Foundations → Sub-skill`

## 8. READING FOUNDATIONS — CURRENT SUB-SKILLS

The first Area has been opened one layer deeper.

### 01.1 Word Recognition
Focus: recognising written words accurately and increasingly automatically.

### 01.2 Word Segmentation
Focus: identifying boundaries between words and meaningful written units.

### 01.3 Sentence Processing
Focus: building meaning from words, grammar and relationships within a sentence.

### 01.4 Reading Fluency
Focus: reading connected text with appropriate accuracy, pace and phrasing.

These are currently the reference model for how the remaining Reading Areas should be structured.

## 9. CONTENT MODEL FOR EVERY SUB-SKILL

Every Sub-skill should eventually use a consistent professional learning template:

1. **What is it?**
2. **Why does it matter?**
3. **What does the student learn?**
4. **What does the student actually do?**
5. **How is it practised?**
6. **Common difficulties / errors**
7. **How is mastery checked?**
8. **Transfer / application**
9. **Final learning outcome**

This is not merely a definition page. It is intended to function as a student learning route.

## 10. WHAT IS STILL MISSING

### Reading — HIGH PRIORITY

The following must still be completed before Reading can be marked **COMPLETE**:

- Build Area 02 page
- Build Area 03 page
- Build Area 04 page
- Build Area 05 page
- Build Area 06 page
- Build Area 07 page
- Build Area 08 page
- Build Area 09 page
- Build Area 10 page
- Build Area 11 page
- Build Area 12 page
- Build Area 13 page
- Build Area 14 page
- Build Area 15 page
- Build Area 16 page

For EACH Area:

- Identify all appropriate Sub-skills
- Make every Sub-skill clickable
- Create the Sub-skill learning page
- Expand each Sub-skill into Micro-skills
- Add detailed explanations
- Add practice route
- Add mastery / assessment route
- Add transfer / outcome
- Maintain floating navigation
- Verify every link and remove all 404 errors

## 11. READING COMPLETION RULE

Reading must NOT be labelled **COMPLETE** merely because the 16 Area cards exist.

Reading becomes **COMPLETE** only when:

`16 Areas → all Sub-skills → all Sub-skill pages → Micro-skill architecture → learning explanations → practice → mastery → transfer → navigation → link verification`

are all implemented.

## 12. FUTURE WORK AFTER READING

Once Reading is genuinely complete and verified:

### Language Skills
- Listening
- Speaking
- Writing

Each will use the same hierarchical model.

Then develop:

### Language Systems
The detailed system architecture will be designed separately.

### Language Competence
The detailed competence architecture will be designed separately.

## 13. WORKING PRINCIPLE FOR FUTURE DEVELOPMENT

Do not flatten the platform.

Always build **layer by layer**:

`HOME`
↓
`PLATFORM`
↓
`MAIN AREA`
↓
`SUB-AREA`
↓
`SUB-SKILL`
↓
`MICRO-SKILL`
↓
`LEARNING DETAILS`
↓
`PRACTICE`
↓
`MASTERY / ASSESSMENT`
↓
`TRANSFER`

## 14. IMPORTANT PROJECT MEMORY

The current agreed visual model is:

- Professional
- Compact
- Clean
- Student-facing
- Not visually busy
- Circular floating navigation
- MB logo
- Previous / Next on internal pages
- Clickable hierarchical cards
- No giant flat information dumps

The most important architectural rule established in this project is:

> **The learner should never be forced to face the whole curriculum at once. Each page reveals the next layer, and each layer is clickable.**

## 15. CURRENT CHECKPOINT STATUS

**Overall Project:** 🟡 In Development

**Top-level Platforms:** 🟢 Established

**Language Skills:** 🟢 Established

**Reading Master Map:** 🟢 Established

**Reading Area 01:** 🟡 Started / model established

**Reading Areas 02–16:** 🔴 Remaining

**Complete Reading Sub-skill architecture:** 🔴 Remaining

**Listening:** 🔴 Not started at deep level

**Speaking:** 🔴 Not started at deep level

**Writing:** 🔴 Not started at deep level

**Language Systems:** 🔴 Not started at deep level

**Language Competence:** 🔴 Not started at deep level

---

## NEXT STEP

Do **not** jump to Listening yet.

Continue Reading systematically from **Area 02 → Area 16**, using Area 01 as the structural reference, and complete the entire Reading hierarchy before declaring Reading finished.
