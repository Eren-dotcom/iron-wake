# Iron Wake: Strike Fleet

High-definition 2D & vector naval warship combat simulator. One HTML file, everything procedural, no network required, no dependencies.

**Play:** open `index.html` in any modern browser (or serve the folder over HTTPS). Click **Weigh Anchor** to start.

## The game

Command one of three warships across Kestrel Straits — DDG-79 Aegis Vanguard Destroyer, PT-88 Stealth Corvette, or BB-92 Sovereign Battleship — through endless escalating waves: Kirov cruisers, Akula submarines, fast gunboats, sea mines, coastal railgun fortresses, strike aircraft, and the Kraken Leviathan Super-Dreadnought boss.

- **4 camera perspectives:** 2D Chart, 2D Broadside, HD Chase, HD Bridge (keys 1–4 / Space)
- **3 playable ships**, **4 sea states:** Dusk, Typhoon, Night, Arctic
- **Weapons & systems:** rotating deck turrets, VLS cruise missiles, torpedoes, Aegis EMP, smoke & chaff, sonar ping, ASROC depth salvo, Seahawk drone, escort frigates, carrier airstrike
- **Economy & upgrades:** earn credits from kills, spend on Railgun, Hull/Aegis, Turbine and CIWS/Sonar upgrade tracks; dock at Port Kestrel to repair and rearm
- **Forgiving loop:** hull zero triggers emergency damage control and redeployment — no hard game over, the fight continues
- Keyboard, mouse and touch controls; generated Web Audio sound (no audio files)

## Tech

- Single self-contained `index.html` (~180 KB) — Canvas 2D + WebGL2, all art, terrain, sound and AI generated in code at runtime
- Zero external assets, zero network calls, works fully offline
- World generation runs in a Web Worker; graceful fallback to 2D views if WebGL2 is unavailable

## Controls (summary)

Mouse aim · Click main guns · A/D or arrows rudder · F / right-click VLS missile · B torpedo · E Aegis EMP · R smoke & chaff · Shift flank speed · Z sonar · X ASROC · U Seahawk · I escort orders · O airstrike · K cycle sea · P pause · ? in-game Naval Manual
