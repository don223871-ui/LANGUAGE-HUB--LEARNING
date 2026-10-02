# LANGUAGE-HUB--LEARNING · SKILLS COMPLETION CHECKPOINT

**Date:** 2026-10-02

## PROJECT DIRECTION

The Language Hub contains three main platforms:

1. 📚 Language Skills
2. ⚙️ Language Systems
3. 🎯 Language Competence

Current priority: complete the four Language Skills before moving deeper into the other two platforms.

---

# LANGUAGE SKILLS

The four core skills are:

- Reading
- Listening
- Speaking
- Writing

Current status:

| Skill | Status |
|---|---|
| Reading | Built / structured / mapped |
| Listening | Built / structured / mapped |
| Speaking | Remaining |
| Writing | Remaining |

---

# 1 · READING

Reading is the first completed architectural reference for the Skills platform.

### Architecture

**Reading → 16 Areas → Sub-skills → Micro-skills → Micro-skill Detail**

### Reading requirements established

- Every Area has its own explanation.
- Every Sub-skill has its own explanation.
- Micro-skills are explicitly defined and clickable.
- Micro-skill detail pages provide the deeper learning layer.
- Full Map uses nested Dropdown / Accordion presentation.
- Default state is closed to keep the page clean.
- Floating circular navigation is preserved.
- Previous / Next navigation is part of the page system.
- The student moves progressively rather than seeing a flat information dump.

### Reading Full Map visual standard

**Area ▾ → Sub-skill ▾ → Micro-skills → Detail**

This is the UI/UX reference for Listening and future Skills.

### Important Reading checkpoint

A duplicate `Open Full Micro-Skills Map` display issue was encountered during development. The source was verified to contain one instance, and this should remain a verification point if it reappears on the live Pages deployment.

---

# 2 · LISTENING

Listening has now been brought to the same deep architectural level as Reading.

### Architecture

**Listening → 16 Areas → 64 Sub-skills → 320 Micro-skills → Detail**

### 16 Listening Areas

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

### Listening hierarchy

Each Area contains 4 Sub-skills.

Each Sub-skill contains 5 Micro-skills.

Therefore:

**16 Areas × 4 Sub-skills = 64 Sub-skills**

**64 Sub-skills × 5 Micro-skills = 320 Micro-skills**

### Listening Full Map

The Full Micro-Skills Map was deliberately redesigned to match Reading:

- 16 Areas are collapsed Dropdowns.
- Opening an Area reveals its Sub-skills.
- Each Sub-skill is another collapsed Dropdown.
- Opening a Sub-skill reveals its Micro-skills.
- Micro-skills are clickable.
- Clicking a Micro-skill opens its Detail page.
- Everything is closed by default.
- The page remains compact and professional.
- Floating circular navigation remains available.

### Technical issue already solved

The Listening Full Map previously displayed:

`Unable to load the master map.`

The master-map loading/parsing path was corrected and the nested Dropdown map restored.

Latest known successful fix commit:

`25b6b5c9aa792937a28c29b8023ce1ec3c12aa46`

### Listening poster / visual reference

A complete Listening Skill Tree poster was generated showing:

**Platform → Skill → Area → Sub-skill → Micro-skill → Detail → Practice → Mastery**

The final poster corrected two visual issues from the first version:

- Added the MB / Mohammad Bakhshandeh Learning & Knowledge Hub branding/logo.
- Corrected the duplicated/misnumbered Area 14 so the sequence is correctly 01–16.

The poster is a visual reference only; the GitHub web architecture remains the authoritative project structure.

---

# 3 · SPEAKING · NEXT

Speaking has NOT yet been built.

When we start Speaking, do not create a shallow topic list.

Use the established deep architecture:

**Speaking → Area → Sub-skill → Micro-skill → Detail → Practice → Mastery**

The Speaking Areas must be designed specifically around the real abilities required to become a strong speaker, not copied mechanically from Reading or Listening.

For every Area, define:

- What the learner is developing
- Why it matters
- What the learner must be able to do
- Sub-skills
- Micro-skills
- Observable mastery outcomes
- Practical transfer

The Full Map should use the same clean nested Dropdown model.

---

# 4 · WRITING · AFTER SPEAKING

Writing has NOT yet been built.

Use the same deep architecture:

**Writing → Area → Sub-skill → Micro-skill → Detail → Practice → Mastery**

Writing Areas must be designed specifically around the real writing process and transferable written communication abilities.

Do not reduce Writing to grammar, essay templates, or exam tricks.

For every Area, define:

- What ability is being built
- Why it matters
- What the learner should understand
- What the learner should practise
- What micro-skills make up the ability
- What successful performance looks like
- How the ability transfers into authentic writing

Full Map presentation must match the clean Reading/Listening Dropdown standard.

---

# GLOBAL DESIGN RULES PRESERVED

## Navigation

Every relevant page should preserve:

- Professional MB logo
- Home
- 📚 Language Skills
- ⚙️ Language Systems
- 🎯 Language Competence
- Circular floating buttons
- Previous / Next where sequential navigation applies

## Information architecture

Never flatten the learning architecture.

Required progression:

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
**Detail**
↓
**Practice**
↓
**Mastery**

## Educational rule

Each layer must answer its own question:

- What is this?
- Why does it matter?
- What exactly does it train?
- What should the student do?
- What ability should result?
- How does it connect to the next layer?

## UI rule

Keep pages:

- clean
- compact
- professional
- hierarchical
- progressively expandable
- visually consistent
- free from unnecessary information overload

---

# CURRENT STOPPING POINT

**Reading:** completed as the architectural reference.

**Listening:** completed as the second fully structured skill; Full Map working with clean nested Dropdowns.

**Speaking:** next major build.

**Writing:** follows Speaking.

After Speaking and Writing are structurally complete, the project can move to:

**Language Systems → Language Competence**

---

# NEXT SESSION

Start with:

## SPEAKING

Build it step by step:

1. Define the Speaking architecture.
2. Define all major Areas.
3. Define Sub-skills under every Area.
4. Define Micro-skills under every Sub-skill.
5. Define detailed learning explanations.
6. Build the web pages.
7. Build the Full Micro-Skills Map with nested Dropdowns.
8. Add / verify floating navigation.
9. Verify every drill-down path.
10. Create the project checkpoint before moving to Writing.

**Do not lose the Reading/Listening architecture or UI standards while building Speaking.**
