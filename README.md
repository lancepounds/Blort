# BLORT: The Gumphastic Yawn Parade

A side-scrolling platformer where the story makes no sense on purpose, but the game design does.

You play **General Mustardseed Gumbo**, a sentient whistle-shaped sock, on his way to "the End of the Beginning."

> The plot is allowed to lie to the player; the controls are not.

## Play

Open `index.html` in any modern web browser. There is nothing to install.

Once GitHub Pages is turned on for this repository, the game is also playable at:
`https://<your-username>.github.io/<repository-name>/`

## Levels

| Level | What happens |
|---|---|
| **1-1 Permit to Toast** | The Municipal Breakfast District. Whistle Blast, the two-ink Official Stamp, the Apology Crab, Deputy Spoons, and the mini-boss Deputy Spoon Prime. |
| **1-2 The Annex of Unnecessary Confrontations** | Sock Stretch, Emergency Pocket, and four mini-bosses: Baron von Lint, Chairman Waffle, General Crumb, and Form 1040-Ω. |
| **2-1 The Department of Outdoor Indoors** | A forest inside an office building. Approve leafy elevators, forbid a filing cabinet to file its river, dodge Ceiling Horses and their falling office supplies, silence Loud Rectangles while they shout procedural instructions, defeat the Executive Loud Rectangle during Quiet Hours, and exit into Tuesday. |

## Controls

| Action | Keys |
|---|---|
| Move | Arrow keys or A / D |
| Jump | Space, W, Z or Up |
| Whistle Blast | X or J |
| Stamp / salute | C or K |
| Switch stamp ink (Approved / Forbidden) | V or L |
| Sock Stretch | S, I or Down |
| Use Emergency Pocket | E or U |
| Sound on / off | M |

On phones and tablets, large on-screen buttons appear under the game. They can also be turned on for desktop in Play settings.

## Accessibility: Relaxed mode

Relaxed mode is the default. It is designed so the game can be played without holding keys or precise timing:

- **Tap to walk**: tap an arrow once to walk, again to stop.
- **Edge brake**: walking stops automatically at ledges.
- **Easy jumps**: full-height jumps with no holding and generous timing.
- **No failing**: enemies bounce you back; falls return you to safe ground.
- **Long reach**: the whistle and stamp work from farther away.
- **Game speed**: 100%, 75% or 50%.

Every option can be changed on its own in the Play settings panel below the game, even mid-level. Settings are saved in the browser.

## Project status

This is a vertical slice built from the BLORT Planned Unit / Game Development Document (Version 1.0, August 2026). See the document's section 11.1 for the full Minimum Viable Game scope.

## Technical notes

- Single file: `index.html` (HTML, CSS and JavaScript, drawn on a canvas).
- No build step and no dependencies. Fonts load from Google Fonts with system fallbacks.
