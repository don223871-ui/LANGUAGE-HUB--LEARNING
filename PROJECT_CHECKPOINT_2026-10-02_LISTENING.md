# PROJECT CHECKPOINT · 2026-10-02 · LISTENING

## Project
LANGUAGE-HUB--LEARNING

## Architecture Established
- Main platforms: Language Skills, Language Systems, Language Competence.
- Floating circular navigation is required across pages: MB logo, Home, Language Skills, Language Systems, Language Competence, Previous, Next.
- Skills use the hierarchy: Skill → Area → Sub-skill → Micro-skill → Micro-skill Detail.
- Each level must retain its own explanation and purpose.
- Micro-skills are clickable and open their own detail page.
- Full Micro-Skills Maps use compact dropdown/accordion presentation; default state is collapsed to keep pages clean.

## Reading Status
- Reading is the reference/model architecture.
- Reading has 16 Areas and the Area → Sub-skill → Micro-skill drill-down model.
- Reading Full Micro-Skills Map uses the clean dropdown/accordion style.
- Reading explanations must never be removed when adding Micro-skill layers.

## Listening Status
- Listening Master Map contains 16 Areas.
- Each Area contains 4 Sub-skills.
- Micro-skill master architecture is represented as 16 Areas → 64 Sub-skills → 320 Micro-skills.
- listening.html links each of the 16 Areas to listening-area.html.
- listening-area.html supports Area → Sub-skill → Micro-skill → Detail navigation.
- listening-micro-skills.html now uses nested dropdowns: Area dropdown → Sub-skill dropdown → clickable Micro-skills.
- All dropdowns are collapsed by default for a clean professional page.
- Micro-skills link to listening-micro-detail.html.
- Floating navigation is preserved.

## Latest Listening UI Commit
- `f510508fe6db5a3da0a62a47e801fff22b71e03b`
- File: `listening-micro-skills.html`

## Design Rule Going Forward
Listening Full Map must visually follow Reading Full Map: clean, compact, hierarchical, collapsible, and never dump all information onto the page at once.

## Remaining Work
- Verify the live GitHub Pages rendering of the new Listening Full Map.
- Continue refining Listening Area/Sub-skill/Micro-skill explanations where needed.
- After Listening is fully validated, proceed to Speaking, then Writing, using the same architecture and navigation rules.
