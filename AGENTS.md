# Project Guidance

## Project

This repository contains an unofficial, non-commercial Rusty Lake / Cube Escape fan ARG currently titled **Rusty Lake Archive: Case 23**.

The experience is a static, old-web-style investigation site. The player begins with Laura Vanderboom's 1971 death and reconstructs Rusty Lake lore through newspapers, police records, medical files, property records, family trees, archived pages, and diegetic puzzles.

Read `docs/rusty-lake-case23-outline.md` before making narrative, puzzle, information-architecture, or implementation changes.

## Non-negotiable narrative rules

- The player remains an outside investigator. Do not reveal that the player is chosen by the Lake, named in an archive, tracked, or personally responsible for canon events.
- The archive website was created by ordinary people who did not understand the supernatural truth. Its public copy must use rational archival language.
- Do not assign Laura's death a single definitive murderer unless later official canon explicitly confirms one.
- Do not change the established outcomes of Laura, Dale, William, Aldous, Jakob, Caroline, Mr Owl, Mr Crow, Harvey, or the Eilander and Vanderboom families.
- Distinguish every lore statement as one of:
  1. explicit canon,
  2. strong implication,
  3. fan-created connective material.
- Fan-created documents may bridge gaps but must not silently overwrite canon.
- Do not copy the television-station, high-dimensional-observer, human-base-station, or cognition-overwrite concepts from *The Strange Advertisement Investigation*.

## Experience rules

- Core loop: discover anomaly → extract search term → find related record → solve a diegetic puzzle → revise the current theory.
- Required solutions must be supported by at least two discoverable clues.
- Source inspection, brute force, or manually guessing URLs may unlock optional secrets but must not block the main path.
- Provide progressive hints after inactivity; never permanently fail or destroy progress.
- Introduce a new page form, mechanic, or major interpretation roughly every 7–10 minutes.
- The visual style may imitate an early-2000s archive site, but navigation, search, progress tracking, zooming, contrast, and mobile use must remain clear.
- Prefer static implementation and local progress storage. Do not add paid APIs, live LLM calls, analytics, authentication, or a backend without explicit approval.

## Repository layout

- `docs/`: design documents, canon tables, site maps, clue matrices, and scripts.
- `src/`: website source.
- `assets/`: original or properly licensed images, audio, fonts, and scans.

## Validation

For each new chapter or puzzle, verify:

1. What the player currently believes.
2. What evidence changes that belief.
3. What page or search term becomes available next.
4. Whether the solution is deterministic and fairly clued.
5. Whether it respects the canon/fan boundary.
6. Whether a first-time player can proceed without an external walkthrough.

Preserve unrelated user changes. Keep commits focused and report the files and checks used.

