# Bhuntu & Buda Arcade

Personal games for Kajal (Bhuntu) and Sulav (Bhuntey ko buda).

- **Jhyam Championship:** attack with perfect timing while the rival automatically blocks or dodges. Dramatic animated photo reactions, randomized Nepali brags, and escalating difficulty.
- **Chuppa Archery:** attack with heart-tipped arrows, automatic rival defense, flying kisses and exaggerated photo reactions.
- **Maya Dash:** a three-lane Nepal endless runner with jumping, sliding, traffic, heart coins, roadside photo ads and rising speed.
- **Nepal Road Rush:** the complete race with escalating traffic, turbo, horn, slap, kick, kiss, roadside photo ads and Endless mode.
- **Dashain Love Quest:** the original five challenges, ten memories, love letter and cute rewards.

The arcade is for long-distance play: attack the computer rival, then copy a score challenge link for your other half to beat. The duels award rival points for successful defense or your misses. Kajal's duel mode is harder. Personal bests save locally in each browser. Challenge links carry the score; there is no real-time multiplayer or shared online leaderboard.

On phones tap the duel button, or swipe/use buttons in Maya Dash. On laptops use Space/Enter for timing and arrow keys for running. P pauses. Original cartoon sound effects start after a tap; background music in the new games is muted. SFX can be switched off.

## Hosting

Publish the main branch root using GitHub Pages. index.html is the hub; race.html and quest.html contain the two classics. Each page embeds its assets. Retain .nojekyll.

Editable new-game source: outputs/arcade-hub. Build all three pages with node work/build-arcade.mjs.
