# Bhuntu vs. Bhuntey ko buda — Nepal Road Rush

A personalized arcade road racer for Kajal and Sulav. Two photo-headed karts, traffic that speeds up, a 90-second showdown, and Endless High Score mode.

## Controls

Phone: hold the arrow buttons to steer, brake to slow, and tap the moves. Laptop: arrow keys steer, down brakes, A slaps, S kicks, C sends Chuppa, Space boosts, H horns, and P pauses.

Kajal's mode has tougher traffic and a stronger rival. Slaps and kicks work when the rival is close; Chuppa distracts them. Collect hearts, dodge buses, watch goats, and pass traffic closely for bonuses. Three hearts per run. A momo can restore a heart.

Records are stored locally in the current browser, separately by player and mode. There is no online leaderboard. Photos decorate the karts, roadside ads, and end screen. The original synthesized soundtrack starts after a tap.

## Hosting

This self-contained index.html embeds all assets, styles, scripts, and original music synthesis. No build or CDN needed. Publish the main branch root with GitHub Pages; retain .nojekyll.

Editable source: outputs/nepal-love-race. Rebuild: node work/build-race.mjs.
