# Siege of Frostfall

An original ice-world tower-defense game. One file (`index.html`), no dependencies, no external assets:
all art is drawn procedurally on a canvas and all sound is synthesised with WebAudio.

Open `index.html` in any modern desktop or mobile browser (or serve the folder statically).

## Features
- 3 missions (10 / 14 / 18 waves), the last with two entrances; star ratings and unlocks saved in localStorage
- 5 turrets x 3 upgrade levels: Blaster, Cryo (slow), Missile (splash, ground only), Ion Coil (chain, ignores armour), Heavy (ground only)
- 5 enemy types incl. flying drones, armoured striders and a boss titan; flat armour reduction rewards the right turret choice
- Orbital Strike and Cryo Field abilities, early-wave-call bonus, wave-clear bonus, 1x/2x/3x speed, pause, sell, target modes
- Touch: tap a turret, tap a tile to preview, tap again to build. Mouse: click to build. Scales to any screen size / DPR

Keys: `1-5` build, `U` upgrade, `S` sell, `N` call wave, `P`/Space pause, `F` speed, `O` orbital, `C` cryo, `Esc` cancel.
