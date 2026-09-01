# INSAN CRICKET

Original 3D cricket career prototype from **INSAN CREATIONS**.

Not affiliated with Cricket 24/26, EA, IPL, BCCI, ICC, or any licensed league.

**Play:** after GitHub Pages is on — `https://sl8722569-ux.github.io/insan-cricket/web/`

Local: open `web/index.html` (needs internet for Three.js / Tailwind CDN).

The playable build is expanded from the user's `INSAN_CRICKET_3D_PREMIUM_GAMEPLAY_FIXED-1.html` (preserved in `original/`).

v2.2: High-poly procedural players (dense spheres/cylinders, PBR skin, 5 fingers, facial features) scaled by GFX preset. Live **P2P multiplayer** via PeerJS public broker — create/join a room code; host runs the match engine. Not a photoreal WCC3 mesh pipeline and not an INSAN-hosted dedicated game server (GitHub Pages is static). See `server/README.md`.

v2.1 (Part 5): Continue Match restores the exact innings (v4 snapshot). Shot-map analytics (zones, dots, boundaries, dismissal vs bowling). Franchise desk: value, 2-year contracts, transfer, bonuses, strategy. Google save is honest (no OAuth client). In-game QA harness `web/tests.html` → `?demo=qa`. Proof in `proof/` part5.

v2.0 (Part 4): Formats T20–Test including custom 30/60/90 Test overs. Difficulty BEGINNER→LEGEND changes timing windows and tactics, not cheat stats. Batting aim cursor with assistance levels. Shot map wagon wheel feeds bowling plans. Career opponents generated from the player's town/district/state/nation (not a forced Mansa XI vs Rampura XI picker). Test follow-on, declaration, 80-over new ball, sessions, ball wear. Walkout + intro. INSAN Shield group table / NRR / knockout / Super Over. Proof in `proof/` part4.

v1.9 (Part 3 career): Town start as PLAYER — not captain. Trials can pass/fail/partial. Selection, dropping, mail, INSAN Sports bulletin, living world NPCs, fitness/workload, adaptive bowling/batting/captain AI from scouted deliveries, career records and Hall of Fame. Proof in `proof/` part3.

v1.8 (Part 2 gameplay engine): Named shots (defence through reverse-sweep/scoop/ramp/power) with timing and power that change placement, edges and wickets. Perfect timing is not an automatic six. Pace vs spin variations are style-locked. 3D fielders move, keeper stands up to spin, running between wickets with YES/WAIT/2/3/DIVE. Live HUD and full batting/bowling scorecard both read the same match state. All-out and chase end the innings correctly. Proof in `proof/` (batting, bowling, scorecard, fielding).

v1.7 (Part 1 match flow): Continue-to-toss no longer drops back to the menu. Pause saves the innings; Continue Match restores it. Playing XI shows C/VC/WK/roles. Cinematic toss with named captains and Heads/Tails. Scrollable main menu (Quick Play, Career, Tournament, Franchise, Practice, Multiplayer, Custom, Continue Match, Settings).

Download (GitHub Releases):
- `INSAN-CRICKET-Android-WebCompanion.zip` — Android PWA pack (Chrome → Add to Home screen)
- `INSAN-CRICKET-Android.apk` — WebView companion, sideload, not Play Store
- `INSAN-CRICKET-Web.zip` — browser copy of the game

Still a browser Three.js prototype — not photoreal WCC3 / Real Cricket 24.
