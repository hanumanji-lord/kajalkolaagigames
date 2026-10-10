# Bhuntu & Buda Arcade

Personal games for Kajal (Bhuntu) and Sulav (Bhuntey ko buda).

- **Jhyam Championship:** tap the timing window to slap or dodge. Perfect hits earn streak bonuses. Faster markers and shrinking windows raise the difficulty.
- **Chuppa Archery:** time heart-tipped arrows and defensive dodges, with flying arrows and animated photo reactions.
- **Nepal Road Rush:** the complete race with escalating traffic, turbo, horn, slap, kick, kiss, roadside photo ads and Endless mode.
- **Dashain Love Quest:** the original five challenges, ten memories, love letter and cute rewards.

New duels support a computer rival or two people taking turns on one phone. Kajal's solo mode is harder; local mode gives both people the same difficulty. Scores save locally in each browser, separately by game, player and play mode. No online multiplayer or shared leaderboard.

On phones tap the main duel button; on laptops use Space or Enter. P pauses. Music and original synthesized sound effects begin after a tap and can be muted.

## Hosting

Publish the main branch root using GitHub Pages. index.html is the hub; race.html and quest.html contain the two classics. Each page embeds its assets. Retain .nojekyll.

Editable new-game source: outputs/arcade-hub. Build all three pages with node work/build-arcade.mjs.
