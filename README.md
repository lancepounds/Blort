# BLORT: The Gumphastic Yawn Parade

A side-scrolling platformer where the story makes no sense on purpose, but the game design does.

You play **General Mustardseed Gumbo**, a sentient whistle-shaped sock, on his way to "the End of the Beginning."

> The plot is allowed to lie to the player; the controls are not.

## Play

Open `index.html` in any modern web browser. There is nothing to install.

Play online: **https://lancepounds.github.io/Blort/**

Jump to the new level's selection: **https://lancepounds.github.io/Blort/#large-small-desert**

## Levels

| Level | What happens |
|---|---|
| **1-1 Permit to Toast** | The Municipal Breakfast District. Whistle Blast, the two-ink Official Stamp, the Apology Crab, Deputy Spoons, and the mini-boss Deputy Spoon Prime. |
| **1-2 The Annex of Unnecessary Confrontations** | Sock Stretch, Emergency Pocket, and four mini-bosses: Baron von Lint, Chairman Waffle, General Crumb, and Form 1040-Ω. |
| **2-1 The Department of Outdoor Indoors** | A forest inside an office building. Approve leafy elevators, forbid a filing cabinet to file its river, dodge Ceiling Horses and their falling office supplies, silence Loud Rectangles while they shout procedural instructions, defeat the Executive Loud Rectangle during Quiet Hours, and exit into Tuesday. |
| **3-1 Tuesday** | Treat a weekday as a place. Whistle three clocks past lunch, evade the newly impatient clouds, and locate Wednesday. |
| **4-1 The Large Small Desert** | Giant cardboard mesas, three folding horizons, increasingly wide ravines, and tumbleweed paperwork. Stamp each hinge APPROVED, walk onto the unfolded approach, then use Sock Stretch at its striped handle. Whistle stops the fans and pauses the rolling forms; FORBIDDEN ink parks the forms. Reach the small exit after all three approvals. |

Every completion screen offers **Play This Level Again** and **Return to Level Select**. You can also open **Level Select** from the pause menu at any point. Browsing keeps the current run paused, with a **Resume** button to return to it; starting a level begins a fresh run. Tuesday now continues into the desert. The desert starts with the Official Stamp and Sock Stretch, so it can also be played directly from level select. Checkpoints follow each ravine, and horizon approvals persist after falls.

A readable **Next step** panel above the game follows each level's puzzles and confrontations. Stamp puzzles show the ink they need and tell you when to switch ink. The opening tutorial uses this panel too.

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

On phones and tablets, large on-screen buttons appear under the game in two rows: movement, Jump, and Whistle above the unlocked abilities. Stamp, Switch ink, Stretch, and Pocket appear as you collect their abilities. Buttons are disabled while paused. They can also be turned on for desktop in Play settings.

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

## Playable worlds

- 1-1 Permit to Toast — Municipal Breakfast District
- 1-2 The Annex — four unnecessary confrontations
- 2-1 Outdoor Indoors — office forest and filing-cabinet river
- 3-1 Tuesday — whistle three clocks past lunch, evade impatient clouds, and locate Wednesday
- 4-1 The Large Small Desert — unfold the horizon, stretch across ravines, and use the small exit

