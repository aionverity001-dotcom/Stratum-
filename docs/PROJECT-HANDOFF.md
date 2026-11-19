# Mandal App / Stratum recovery handoff

## Repository and project identity
- Destination repository: https://github.com/aionverity001-dotcom/Stratum-
- Default branch at recovery: main
- Recovery work is being staged on a separate branch so the existing main branch remains untouched.
- Historical working package name: `mandal-app-vite-upgrade`
- Historical package version: `0.2.0`
- Historical Vite dependency: `^5.4.0`
- An earlier working name, `flutter-ripple`, was proposed in September 2026 but was not the settled project name.
- The project name later associated with the repository is Stratum.

## Recovered Vite project inventory
The September 2, 2026 conversation contains user-supplied source for:
- `package.json`
- `vite.config.js`
- `index.html`
- `src/main.js`
- `src/styles.css`
- `src/modules/ui.js`
- `src/modules/store.js`
- `src/modules/renderer.js`
- `src/modules/storage.js`
- `src/modules/utils.js`

The original Vite source was pasted into a prior conversation. The current Library does not contain those individual source files in a recoverable form, so this branch does not pretend to reproduce their contents. The prior assistant identified `src/modules/audio.js` as imported/referenced but not supplied. Its expected interface was discussed as `start()`, `stop()`, `sample()`, and `summarize()`.

Known behavior and architecture from that source:
- Pointer-oriented interaction and browser-native rendering.
- Session state separated into store, renderer, UI, storage, and utility modules.
- Local persistence key: `mandal-app-sessions-v2`.
- Audio input lifecycle was identified as needing careful start/stop cleanup.
- Structural mapping was intended to remain deterministic and not assign emotion, diagnosis, or meaning to a person.

## Earlier handoff materials
Prior project conversations refer to a PRD, developer task list, UX/UI brief, practitioner guide, geometry model, privacy and anti-overuse principles, and a Launch Bridge Packet. The prior handoff also described an Obsidian-to-GitHub-to-Garden publishing pipeline and metadata-driven publishing.

The original standalone packet files were not located in the current Library or connected Dropbox search during this recovery. This document records the known contents and provenance; it is not a claim that the original packet documents have been recovered verbatim.

## Recovered prototype
A recovered document from the Library contains a single-file HTML/CSS/JavaScript voice-input prototype and accompanying tree-ring archive notes. The embedded HTML is incomplete at the end of the recovered text, so it is retained as a recovery artifact rather than presented as a runnable build.

The prototype describes:
- Microphone input with live canvas feedback.
- Session-to-geometric-output transformation.
- Session view and accumulated master view.
- Optional local session persistence.
- PNG export and session deletion controls.

## UI material
A separate September 14, 2026 paste contains a coherent CSS block for a dark responsive canvas interface, floating panels, a view toggle, voice control, and modal. The same paste also contains unrelated injected page material after the CSS block. Only the standalone CSS section is archived in this branch.

## Current website direction
The newer public-facing project direction is a layered interactive scrapbook / mind-map / choose-your-path story space. It gathers artifacts, photographs, writing, research, AI conversations, projects, travel, and lived events. Navigation follows recognition and association as well as chronology. Some artifacts open a small note; others open a deeper collection or interactive world. Visitors follow their own paths through the same source material.

Visual direction from the November 2026 conversation:
- Handmade 80s/90s punk and photocopied-zine language.
- Black and white as the base, with small, occasional color accents for interaction.
- Flyers, tickets, clippings, stickers, notes, photographs, and layered collage.
- Irreverent, darkly funny, warm, and human.
- Dense and exploratory, with navigation that remains legible.

## Recovery gaps
1. The verbatim Vite source files from the September 2 conversation need to be restored from that conversation or a local copy.
2. `audio.js` was not included in the original pasted source.
3. The original PRD, UI brief, developer task list, practitioner guide, and Launch Bridge Packet have not yet been recovered as separate source documents.
4. No deployed website URL was found in the accessible project records. A prior conversation says the GitHub repository was empty when created; no live URL was supplied there.
5. The current Stratum repository previously contained only its README and initial commit. No application implementation was found in it during this recovery.

## Import rule
Keep recovered originals, reconstructed notes, and newly written implementation clearly separated. Do not silently replace historical source with reconstructed code. Preserve provenance and note incomplete artifacts.
