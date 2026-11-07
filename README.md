[English](README.md) | [简体中文](README-ch.md)
# Kitchen Disco

A hand-drawn, one-key rhythm cooking game. Follow the music and use the Space bar to chop, coat, stir, bake, and pipe cream, turning each beat into a cooking action.

## Getting Started

1. On a Windows PC, open the `builds/level-01` folder and double-click `kitchen-disco.exe`. The playable build includes its game resources; you do not need to install Godot.
2. After the opening animation, the game takes you directly to level selection. Press Space or Enter to skip the opening.
3. Click a level card to play:
   - **Prologue / Crispy Chicken Strips**: an approximately 55-second tutorial, recommended for first-time players.
   - **Level 1 / Fruit Cream Cake**: an approximately 60-second cooking challenge.
4. The game uses English on first launch. To change the language, click the gear in the bottom-right corner of level selection and choose **English** or **简体中文** under **Language**. Your choice is saved.

Start with the prologue and play with sound enabled, preferably using headphones. Settings let you adjust master volume, music, sound effects, and timing offset, as well as switch between fullscreen and windowed mode.

## Controls

Cooking uses only the Space bar. Use the mouse to select levels and click menu buttons.

| Action | Input |
| --- | --- |
| Tap | Press Space once as a beat arrives; each tap note requires a separate press |
| Hold | Press and hold Space at the start, then release at the end |
| Pause | Press Esc during gameplay |
| Resume | Click Continue on the pause screen, or press Enter |
| Retry | Press R during gameplay, or click Try again on the results screen |
| Return to level selection | Click Level select |
| Toggle mute | Press M during gameplay |

### Reading the Rhythm Cues

- **Ingredient and utensil outlines**: a highlighted outer outline shrinks toward the target. Act when it lines up with the target. When several targets appear, follow their numbered order.
- **Stirring around the bowl**: during the stirring passages in Milk & Oil, Flour, and Yolks, the whisk moves clockwise around a track inside the bowl. Up to three upcoming markers appear on the track. Press Space as the whisk head passes each marker. Pressing the key does not reset the whisk's position.
- **Hold notes**: cyan cues indicate holds. Press at the start, watch the progress bar and outline, and release at the end. Releasing the key does not play an additional sound effect.

Successful actions trigger a drum hit and visual feedback. If the audible beat and the displayed timing seem out of sync, pause, open Settings, and adjust **Timing offset**.

## Gameplay Overview

### Prologue Crispy Chicken Strips

The first approximately 14 seconds demonstrate tapping and holding. When **YOUR TURN!!!** appears, the playable section begins.

Follow the music to cut chicken, coat the strips, fry them, and drain the oil before serving. Cut strips remain on the board, and the food changes as you coat and fry it. This level contains 40 tap notes and 8 hold notes.

### Level 1 Fruit Cream Cake

Follow a one-minute track to make a cake: separate the eggs, stir milk and oil, add flour, add yolks, whip the egg whites, fold the mixtures together, pour the batter into a mold, bake, pipe cream, and add fruit.

The level contains 67 notes: 47 taps and 20 holds. The segmented progress bar along the bottom shows the current cooking step and your progress through the track. Holds advance the corresponding animations. Finished cream rosettes remain on the cake, and fruit decorations land as you complete their notes.

### Scoring and Feedback

- **Perfect**: accurate timing.
- **Good**: a successful action with a small timing error.
- **Miss**: a missed note or an incorrectly timed hold start or release.

Consecutive successful actions build your combo; a miss breaks it. When the music ends, the results screen shows your performance and lets you retry or return to level selection. The cake level also displays Perfect, Good, and Miss counts, your highest combo, and a review of your dish, and saves your best score.

---

This guide describes the current Windows demo. Earlier project notes are preserved in the [development history in Chinese](Docs/README历史开发记录.md).
