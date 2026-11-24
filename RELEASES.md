# Release history

Every Colonization+ release, newest first: when it was made, whether a patcher was published, and the work items it brought (from the project's Completed Work log; the ids in brackets are the project's work-item ids). [CHANGELOG.md](CHANGELOG.md) has the notes of the published patchers.

- **Published**: a patcher you can download from the GitHub release named in the entry.
- **Not published**: an internal test build; no download.
- Release numbers that do not appear (rel5, rel11, rel12, rel14, rel16) were never made: their work went into the next release. rel16 and rel17 were released together as rel17c; rel24c and rel25c are the rebuilt rel24 and rel25.
- Work done before rel1 (2026-10-22 to 2026-10-26) is listed at the end.
- Each item is listed under the release its Completed Work entry names. A few items changed only the project's tests or documents outside a release and are not listed.

79 releases from rel1 to rel88, 19 of them published.

## rel88 (2026-11-24)

Published: [rel88 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel88).

2 items:

- The no-unit Attach / Convoy message has the explorer adviser (CPM172)
- The patcher installs ColDump and starts the crash watch from GOG Galaxy or Steam (CPM251)

## rel87 (2026-11-23)

Published: [rel87 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel87).

2 items:

- A divider between Center View and Show Borders (CPM167)
- A divider between Spectate and Retire (CPM169)

## rel86 (2026-11-23)

Published: [rel86 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel86).

3 items:

- Units path past unexplored terrain when the cost is the same (CPM152)
- Foreign Affairs overview: a Founding Fathers count per power (CPM236)
- cpm227space check 3 fails on every branch since rel85 (CPM240)

## rel85 (2026-11-23)

Published: [rel85 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel85).

8 items:

- Intro: the drum track keeps playing under the flag-planting music (CPM93)
- Foreign Affairs reworked: all 8 powers on one screen (CPM50)
- Foreign Affairs: drop the old per-power pages after the overview (CPM232)
- The combined popups should have newlines and highlight (CPM151)
- Price changes and foreign FF elections on new lines, highlighted (CPM154)
- A colony adviser popup when captured units and colonies become loyal (CPM164)
- Loadable module table: raise MAX_MODULES (CPM227)
- msgkeys suite counts DEBUG.TXT keys as GAME.TXT keys (CPM224)

## rel84 (2026-11-23)

Published: [rel84 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel84).

3 items:

- Postal texts: @POSTUNIT and @POSTSERVE no longer match the Mail code (CPM146)
- Indian Adviser reworked: a row per tribe with villages, missions, mood and arms (CPM49)
- tools/hub_plugin.py: add GATE and gate_args (CPM215)

## rel83 (2026-11-23)

Published: [rel83 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel83).

3 items:

- Terrain changes stay hidden until the tile is seen again (CPM175)
- Postal Adviser report (CPM39)
- Create Unit cheat: the units the mod added (CPM199)

## rel82 (2026-11-23)

Published: [rel82 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel82).

3 items:

- A selection box dragged around nothing unselected the unit (CPM173)
- Jukebox: natural variation of the MIDI songs (CPM195)
- The Naval Adviser warns of a ship idle in Europe at the end of a turn (CPM194)

## rel81 (2026-11-22)

Published: [rel81 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel81).

1 item:

- Dragging goods from the colony's goods bar added a byte into low memory (CPM220)

## rel80 (2026-11-22)

Not published (internal test build).

3 items:

- Colony screen: Next and Previous buttons cycle between the colonies (CPM193)
- Colonizopedia terrain entries: Irrigation and Thinning bonuses written like the others (CPM181)
- Mini jukebox from a music-note icon by the Colonizopedia button (CPM187)

## rel79 (2026-11-22)

Not published (internal test build).

3 items:

- Native Mail correspondence counts only tribes 0-7 (F99 tribes 8-11 missed) (CPM147)
- Support mousewheel scrolling (CPM196)
- New orders are hidden in View Mode (Postal Network, Dig Irrigation) (CPM159)

## rel78 (2026-11-21)

Not published (internal test build).

3 items:

- Hard crash from professions menu again (CPM202)
- Load cargo (L) fills part-filled holds before taking the most valuable good (CPM176)
- ColDump replay: @UNITFLAG box after the turn-2 START snapshot (CPM124)

## rel77 (2026-11-21)

Not published (internal test build).

5 items:

- Ships told to go to Europe do not head for the nearest High Seas (CPM153)
- Colony screen: no 'Trees' tooltip over the trees (CPM78)
- Rebellion messages show the military adviser portrait (CPM129)
- Cheat: edit a colony's buildings (CPM197)
- Cheat: edit terrain (CPM198)

## rel76 (2026-11-20)

Not published (internal test build).

13 items:

**Stability & saves**

- Autosave rotation deleted a missing COLONY14 (CPM84)

**Colonies & production**

- Jeweller's House as a colony founding choice (CPM104)

**AI & diplomacy**

- A computer power that loses its last colony comes back from Europe (CPM126)
- War of Succession transfer clears the loser's CPM126 slot (CPM144)

**Interface & information**

- Colony screen: selection box left below the stockade (CPM76)
- Colonizopedia: the Mail article in sections (CPM102)
- Disloyal mark: no leftover bar on the blink; top right of the unit tile (CPM75)

**Testing**

- reserve_space: the X1 room line ignores the boot area (CPM119)
- ColDump reports flag game code changed in memory (CPM85)
- Smart gate selects t25reloc when a branch declares reloc_ok hits (CPM87)
- integrate.py: per-item regen fails a branch that shifts the low blocks (CPM122)
- Gates skip the retry phase when many suites fail (CPM134)
- f6b34 is flaky: a colonist sometimes leaves the docks unarmed (CPM136)

## rel75 (2026-11-19)

Not published (internal test build).

6 items:

- rel73-preview1: two hard crashes (code-damage guard on the map, invalid opcode in the colony screen) (CPM143)
- A nation's only colony gets a defence bonus, so early aggression is harder (CPM128)
- Computer powers start with more units on higher difficulties (CPM127)
- Replay: per-turn state hash and save image beside the input log (CPM114)
- Stream gates use the open release's integration base as since, not master (CPM132)
- Harness and DOSBox config edits pick a representative in-game set in stream gates (CPM133)

## rel74 (2026-11-19)

Not published (internal test build).

4 items:

- Taking a colony from a power in debt handed the debt to the captor (CPM125)
- Native villages teach too narrow a range of skills (Resin Tapper at 5 of 5 villages) (CPM74)
- Exact replay from launch: the watch records the whole game and copies the saves before it starts (CPM139)
- Gate preflight: run the three regen checks in parallel and reuse a passed result (CPM131)

## rel73 (2026-11-18)

Not published (internal test build).

3 items:

- End of a round dropped the game back to the intro (rel72-preview2) (CPM135)
- The turn's price changes in Europe are listed together in one box (CPM97)
- The Foreign Affairs adviser lists the Founding Fathers the computer powers elected, in one box (CPM95)

## rel72 (2026-11-18)

Not published (internal test build). Merged into master on 2026-11-18; its game build reached the master build with rel73's promotion.

9 items:

**Trade routes & wagons**

- Load (L) tops up a part-filled hold instead of saying the holds are full (CPM91)

**Colonies & production**

- Thinning a forest or founding a colony on one asks first when a bonus would move away (CPM82)
- Every pioneer action that would remove a bonus asks for confirmation (CPM83)

**Interface & information**

- Skip Turn can be undone by clicking the unit again (CPM90)

**Founding Fathers**

- Founding Father selection: the Confirm? frame confirms, and a white box marks the chosen candidate (CPM98)

**Testing**

- No local paths in tracked files; ComfyUI for the art scripts from the hub node (CPM65)
- Crash watch: record player input so crashes can be replayed (CPM113)
- ColDump keeps a log of the player's actions so a game can be replayed (CPM88)
- ColDump shows its version in the tray tooltip and right-click menu (CPM89)

## rel71 (2026-11-18)

Published: [rel71 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel71).

11 items:

**Colonies & production**

- The Well line (Well, Cistern, Aqueduct) (CPM59)

**Europe, taxes & the Crown**

- Trade at allied powers' home ports (CPM42)

**AI & diplomacy**

- Computer player's Merchantman sails in circles after it loses its colony (CPM73)

**Interface & information**

- Foreign units flash into view in the fog during the computer turn (CPM86)
- Religious Adviser reworked: crosses needed, next immigrant, per-colony churches (CPM46)
- Labor Adviser reworked: a 'where colonists work' first page (CPM47)
- Colony Adviser reworked: one screen, a row per colony (CPM48)
- Main title screen redone, with carved signboards and the mod version (CPM51)

**Testing**

- Catch stale layouts and missing space reservations before merge (CPM108)
- Every game run gets its own TEMP, working folder and profile folder, kept with the results (CPM109)
- Test DOSBox windows are shown by default, also outside hub jobs (CPM106)

## rel70 (2026-11-17)

Not published (internal test build). Merged into master on 2026-11-17 without a promote commit of its own.

10 items:

**Stability & saves**

- Turn skipped, the date stuck after Spring 1539 (game_loop's code changed in memory) (CPM81)
- rel70 gate: f30, f73, r3 and t21b fail (CPM110)

**Colonies & production**

- Unit upkeep in gold each turn (CPM62)

**Interface & information**

- The Colony Adviser explains a disloyal colonist's refusal (CPM68)
- Spectate (CPM31)
- Sound switches in the Jukebox (CPM32)
- Message Options (CPM33)

**Founding Fathers**

- Peter Minuit made native land free (no totems, no prompt) (CPM101)

**Testing**

- Module directory room for 64 modules (CPM80)
- Room for more buildings: ids past 64 and table rows past 62 (CPM66)

## rel69 (2026-11-16)

Published: [rel69 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel69).

9 items:

**Colonies & production**

- Expert names by one rule (Head Teacher, Head Postmaster, Master Foreman, Expert planters) (CPM40)
- Colony screen: buildings stop 1 pixel short of the screen edge (CPM60)
- Colony screen: the Mail tab's explanation in white, with links (CPM55)

**AI & diplomacy**

- Computer powers found their first colony early on a site with forest (CPM34)

**Interface & information**

- Colonizopedia: the new goods' conversion line in the original yellow style (CPM56)
- Colonizopedia: Trade Goods shows the Craftsman and its base goods (CPM57)
- Goods bar keys: Enter / Up / Down change row and keep the box, Left / Right round the row (CPM58)

**Nations & big features**

- Hot-seat: every Human power is asked its own leader name (CPM54)

**Testing**

- Custom art export for hand redraw, and the way back in (CPM45)

## rel68 (2026-11-16)

Published: [rel68 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel68).

3 items:

- Go To preview for the square next to the unit (CPM29)
- Go To preview no longer hides units (CPM30)
- ColDump's crash watch ends with the game (CPM44)

## rel67 (2026-11-16)

Published: [rel67 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel67).

7 items:

- The Expert Teacher costs 2400 to train in Europe (CPM41)
- The Mail button in every colony (CPM37)
- Postal Service options unlock by the network's best postal building (CPM38)
- Eight powers' expansion: more colonies and an earlier second colony (steps 1-5) (F13c)
- Goods bar: no hover label on the spinner or an empty box (CPM23)
- Nation Select: the coloured frame follows the selected nation (CPM26)
- Russia sees no 'Discovery of the Pacific Ocean' woodcut (CPM28)

## rel66 (2026-11-16)

Published: [rel66 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel66).

2 items:

- Intervention force for every rebel, human or computer (CPM20)
- Custom art survey: what the mod drew, and how a hand-painted piece comes back (CPM15)

## rel65 (2026-11-15)

Published: [rel65 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel65).

2 items:

- Gold and Coinage: a gold resource, the Moneyer and the Mint line; the Silver Miner renamed (CPM8)
- Play copies: a preview made with --version leaves a second identical copy in '<name> Versions' (CPM27)

## rel64 (2026-11-15)

Published: [rel64 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel64).

1 item:

- Hot-seat multiplayer, stage 1: 2-8 human powers on one PC (F8)

## rel63 (2026-11-15)

Published: [rel63 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel63).

2 items:

- Computer powers fight their own War of Independence (F3 stage 2: one war at a time) (F3b)
- Attitude between the European powers (CPM21 stage 1) (CPM22)

## rel62 (2026-11-14)

Published: [rel62 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel62).

2 items:

- Goods list: room for twelve extra goods (needed for Gold and Coinage) (CPM10)
- Map Editor test f10f: 'bonuses, loaded again' sometimes draws one square more than expected (CPM17)

## rel61 (2026-11-14)

Not published (internal test build).

2 items:

- Craftsman: Ore and Lumber into Trade Goods (F101)
- Upper memory: room for the wider goods list and the next chains (CPM13)

## rel60 (2026-11-14)

Published: [rel60 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel60).

26 items:

**Stability & saves**

- End of Turn threw the game back to the intro logo, then a hard crash (Russia, Spring 1506) (B87)

**Ships & movement**

- Attach for every land unit, Convoy as an order of its own (F109)

**Natives & missions**

- The Arawak hold the lower Amazon and South America's north coast (F110)
- Leader portraits for the four new tribes (F112)
- The Mapuche and the Guarani take over villages on the original America map (CPM9)

**Colonies & production**

- Colony screen: two quarters with room for two more building chains (T44)
- Profession menu: the new field jobs had no yield off a square (B88)
- Profession menu: the new workshop jobs show what they would make (CPM5)
- Jeweller: Silver into Jewellery (F100)
- Rancher: works the Stable for more horses (F102)
- Foreman: boosts the whole colony's production (F103)

**AI & diplomacy**

- Stronger computer powers (stage 1: expansion and fair founders) (F58)

**Interface & information**

- Dragging a colonist over the empty Warehouse spot popped 'Build a Warehouse' and dropped the drag (B86)
- Audience with the King: shown in the throne room (B89)
- Profession menu: the professions in the order of the goods bar (F108)
- Founding Father selection: no office name on the portraits (F114)

**Map generation**

- Map Editor: Large maps and the new bonuses (stages 1 to 3) (F10f)
- Map Editor: place villages and arrival squares (CPM3)
- The game refuses a map larger than 70 x 90 with a clear message (CPM12)
- Maps smaller than 48 x 60 are checked (CPM14)

**Nations & big features**

- Each nation's America has a name in its own language (F111)
- Nation select: a click on a nation's flag only moves the highlight (F113)

**Testing**

- Conventional memory: free room for the waiting cards (CPM11)
- Release merge: run the generators side by side and the four checks once per batch (CPM7)
- rel60 gate: t41emu and cpm3 fail on the merged build (CPM16)
- Guides: working parallel streams without conflicts, and how to add each kind of content (CPM2)

## rel59 (2026-11-13)

Published: [rel59 on GitHub](https://github.com/matthewh86/Colonization-Plus/releases/tag/rel59). The first published patcher: it contains all the work of the releases below.

19 items:

**Stability & saves**

- Old saves: one outdated section stops the rest from loading (B77)
- rel59: computer powers found only half as many colonies (B78)
- A message box showed the message file's header instead of a message (B83)
- Hard crash: electing a Founding Father, then clicking another Congress office (B85)

**Natives & missions**

- More native tribes (stages 0 to 2: Inuit, Haida, Mapuche, Guarani; their villages on the America maps) (F99)
- Test fix: Large-map village count check (not a game bug) (B76)

**Colonies & production**

- Abandoned colonies become Neutral (F105)
- Goods prices up to 30, and every good's price rebalanced (F107)
- Captured colonists: 'not loyal yet' marker and limits (F106)

**Interface & information**

- Colonizopedia: the Game Concepts section can't be opened (B74)
- Europe goods bar: prices of 20+ run into each other (B75)
- Colonizopedia: new goods' experts and terrain bonuses missing; terrain professions out of goods-bar order (B79)
- Chapel: 'building full' message says three colonists; the Chapel holds one (B80)
- Europe: the AUDIENCE button disappears after selling goods off a ship (B81)
- Orders menu: order and visibility of the mod's new orders (B82)
- Map screen colony summary doesn't show the new goods (B84)

**Testing**

- Free up memory for the next big features (T43)
- Test game windows stay behind other windows (T46)
- rel59 gate: 8 failing suites triaged and fixed before promotion (T47)

## rel58 (2026-11-11)

Not published (internal test build).

22 items:

**Stability & saves**

- Large maps: all-computer games freeze in the 1580s (B71)
- Large Americas: computer turn loops forever (postal roads?) (B72)
- Check: no other mod hook can crash the way B71 did (B73)

**REF & independence**

- Independence rework, stage 1: the War of Succession replaced by three revolution events (F3)

**Ships & movement**

- Goto path preview (F97)

**Natives & missions**

- Large Americas: native villages crowd the coast (B69)
- Other map sizes, stage 3: more native villages than 84 (F10c)

**Colonies & production**

- Rename the Chocolatier building to Chocolatier's House (F62b)

**Interface & information**

- Intro skipping: logo click skips the whole intro; ship-loading scene ignores clicks on its first slide (B68)
- Show Borders works only when the whole map is revealed (B70)
- Goods bar: two rows switched with Up / Down instead of a sideways scroll (F96)
- Goods rows: click anywhere on the tile to switch rows (F96b)
- Goto path: interaction icon centred on its tile (F97b)
- Colony screen: dead-zone clicks for a selected colonist (F104)

**Map generation**

- Large Americas map (70 x 90) (F10d)
- Large Americas follow-ups (forests, map choice text, landfalls) (F10e)
- Pine Stand: new art (F61b)

**Nations & big features**

- Each nation's own monarch and throne room (F88)
- New Game nation screen: powers Off / Computer / Human, with watch mode (F8a)
- Cheat menu: the four new powers (F98)

**Testing**

- Crash memory dump for troubleshooting (T41)
- Smarter merge tests: only what the changes touch; full suite on request (T42)

## rel57 (2026-11-10)

Not released on its own: this set went out with rel58.

## rel56 (2026-11-09)

Not published (internal test build).

5 items:

- Founding Father screen: the effect in the small font (F94)
- Congress offices: seven officers, the sitting after each election, foreign trade (F95a)
- Congress offices: the Treasurer's factories and Custom House, the President's Declaration (F95b)
- Congress offices: Continentals, the postal network, the Cathedral, the colleges (F95c)
- Player patcher for GOG and Steam copies (T18)

## rel55 (2026-11-09)

Not published (internal test build).

8 items:

- Save names for Portugal / Russia / Denmark / Sweden games (B66)
- Education Adviser report (Q12)
- Production Adviser report (Q12b)
- Naval Adviser report redrawn (Q12c)
- Founding Fathers rebalance (first pass) (F90)
- Founding Fathers balance, second pass (F92)
- Distinct Founding Father figures (F93)
- Large maps (70 x 90) (F10b)

## rel54 (2026-11-08)

Not published (internal test build).

6 items:

- reserve_space can lower IMG_LO for a low block (T38)
- Upper memory room for Large maps and the fathers rebalance (T39)
- Founding Father figures: one body height, 19 redrawn (F91)
- Small and Normal map sizes (stage 1) (F10)
- Quieter notifications: a Messages list in Game Options (Q7)
- Hovering over a unit shows its route (F89)

## rel53 (2026-11-08)

Not published (internal test build).

14 items:

**Stability & saves**

- Module cache leaked across a program handover (B65)
- Upper memory room for the rel53 batch (T37)

**REF & independence**

- Peaceful independence path (F4)

**Combat**

- Carolean Infantry: stronger, attack bonus 20% (F86)

**Colonies & production**

- Dye chain: a Dyemaker's House level (F82)
- Choose the colony square's secondary crop (F85)

**Europe, taxes & the Crown**

- Audience with the King (F11)

**Interface & information**

- Entering an unmet village or colony keeps the unit's remaining moves (F84)

**Founding Fathers**

- Exploration Founding Fathers' effects (F45)
- Military Founding Fathers' effects (F46)
- Political Founding Fathers' effects (F47)
- Religious Founding Fathers' effects (F48)
- The father's biography on the Founding Father screen (F83)

**Nations & big features**

- Portugal, Russia, Denmark and Sweden have no banner in the throne room (B64)

## rel52 (2026-11-08)

Not published (internal test build).

7 items:

- A destroyed village's muskets stay with the tribe (R21b)
- Natives offer tiny 2-ton gifts when your storage is nearly full (R22)
- Colony and Trade Reports in the display order (F71c)
- The new skills' names follow the game's skill / expert pattern (B60)
- The unique land units' Colonopedia pages show the foot and the mounted unit (B62)
- The unique units' Colonopedia pages without purchase and production costs (B63)
- Trade Founding Fathers' effects (F44)

## rel51 (2026-11-07)

Not released on its own: this set went out with rel52.

8 items:

- Portugal's mission cross is black (B61)
- Goods in the original's order on the goods bars (F71)
- Paged goods lists in the display order (F71b)
- Map square info lists the new crops' yields on plain squares (B59)
- The jukebox is empty (B57)
- The jukebox's Silence setting does nothing (B58)
- The 1492 audience greets a Russian player with the Tsar (F81)
- Cossack plunder 5%, at most 50 gold (F87)

## rel50 (2026-11-06)

Not released on its own: this set went out with rel52.

3 items:

- Founding Father selection screen in the game's own look (F79)
- Leader portraits for the eight powers (F13d)
- Meetings with the new powers show blank king and country names (B56)

## rel49 (2026-11-07)

Not published (internal test build).

3 items:

- Tar chain levels: Tar Burner's House, Tar Works, Naval Stores Factory (F80)
- Tabs in the build list, the profession menu and the Train list (F78)
- The Continental Congress chamber and 65 full-length fathers (F49)

## rel48 (2026-11-05)

Not published (internal test build).

2 items:

- Native raids burn every house; the Carpenter's Yard (F77)
- In-game jukebox (F76)

## rel47 (2026-11-05)

Not published (internal test build).

2 items:

- Export-chain workshops as founding choices (F70)
- Thinned forests and Oasis irrigation (F75)

## rel46 (2026-11-05)

Not published (internal test build).

2 items:

- Cacao to Chocolate chain (F62)
- Module code is 8086-clean (no 386 address forms) (T34)

## rel45 (2026-11-05)

Not published (internal test build).

5 items:

- Pine Resin to Naval Stores chain (F61)
- New figures for the Indigo Planter and Master Dyer (F60b)
- New units and experts in their natural place in lists (F72)
- Units in Map Order (Game Options switch) (F73)
- Labor Advisor counted the new experts under the wrong professions (B55)

## rel44 (2026-11-04)

Not published (internal test build).

1 item:

- Postal correspondence (Home, Foreign, Native) (F53d)

## rel43 (2026-11-03)

Not published (internal test build).

2 items:

- Fog of war (F69)
- Postal network reach (F53e)

## rel42 (2026-11-03)

Not published (internal test build).

1 item:

- Free X1 room: move cold resident X1 code into modules (T35)

## rel41 (2026-11-03)

Not published (internal test build).

4 items:

- Indigo to Dye chain (F60)
- The fourth Mail button (F53b2)
- Unique units follow-up (Fluyt, East Indiaman, Conquistador, Native Allies) (F6b6)
- A meeting with an original power changed the new powers' colours on screen (B54)

## rel40 (2026-11-03)

Not published (internal test build).

2 items:

- Postal network rules: Service units per 4 colonies, route groups, capture splits (F53c2)
- Rename Letters to Mail (F68)

## rel39 (2026-11-03)

Not published (internal test build).

1 item:

- Bigger module directory, XMS module cache, second transient slot (T33)

## rel38 (2026-11-02)

Not published (internal test build).

2 items:

- Postal phase 2: Extend and Service network orders (F53c)
- Export chains groundwork (F60a)

## rel37 (2026-11-02)

Not published (internal test build).

2 items:

- Postal service, phase 1: abstract Letters (F53b)
- Postal Service art (F59)

## rel36 (2026-11-01)

Not published (internal test build).

1 item:

- Price groups don't match the Strategy Guide (R19)

## rel35 (2026-11-01)

Not published (internal test build).

2 items:

- Combat analysis lines for the unique units' rules (F6b5)
- Animated sea on the Europe screen (F67)

## rel34 (2026-11-01)

Not published (internal test build).

3 items:

- Computer powers count the East Indiaman and mounted Native Allies as armed (F6b3)
- Computer powers' docks colonists become unique units (veterans only) (F6b4)
- Coronado: live intelligence on foreign colonies (F39)

## rel33 (2026-11-01)

Not published (internal test build).

2 items:

- Unique units' follow-up (colony ships, Native Allies colony rule, Colonopedia, computer land units) (F6b2)
- Keystone: retry on assembler errors too (T32)

## rel32 (2026-10-31)

Not published (internal test build).

3 items:

- Unique units (Fluyt, East Indiaman, Native Allies, Conquistadors) on a unit-variant framework (F6b)
- Unique units of Portugal, Russia, Denmark and Sweden (Nau, Cossacks, Marineregimentet, Carolean Infantry) (F6c)
- National bonuses of Portugal, Russia, Denmark and Sweden (F13b)

## rel31 (2026-10-31)

Not published (internal test build).

3 items:

- 65 Founding Fathers: framework (F43)
- Unique Founding Fathers (F21)
- integrate handles modtab.py conflicts and x1lo growth (T31)

## rel30 (2026-10-31)

Not published (internal test build).

10 items:

**Stability & saves**

- No score after winning the War of Independence (mod regression since T17) (B53)

**Europe, taxes & the Crown**

- Europe market rework for 8 powers (home markets) (F63)

**Interface & information**

- Skippable closing animation (Q5)

**Founding Fathers**

- Adam Smith: factories for everyone, Smith's factories make 1.75 goods per raw good (F29)
- Peter Stuyvesant: Custom House for everyone, 15% fee without him (F30)
- Jan de Witt: foreign-colony trade at peace for everyone, better prices and intelligence (F31)
- Drake: prize money for privateers (F40)
- John Paul Jones: a stronger navy (F41)
- Jean de Brebeuf: calmer tribes (F42)

**Testing**

- Narrower pre-merge gate, regen stability (T30)

## rel29 (2026-10-31)

Not published (internal test build).

5 items:

- Multi-unit selection by click-and-drag (Q30 mouse scheme) (Q31)
- Seasonal home ports (F66)
- Low X1 area usable for code (T29b)
- Integration tooling: check_space module records, skipped items, gate_map union (T28d)
- Keystone hex-read bug (gen_mod.Ks16) (REL29)

## rel28 (2026-10-31)

Not published (internal test build).

7 items:

- AI turn hangs when a founder cannot pay the 40 tools (B52)
- Unit shields in the power's map colour, rebels' corner triangle (F55)
- Optional mouse scheme ('Right-Click Moves') (Q30)
- Four seasons from 1700 (F65)
- X1 segment room (low X1 area, dispatch + boot window, 24 modules) (T29)
- integrate.py space check counts the merged branch (T28c)
- rel28 full-suite failures: r3 and b5giveup (Tests28)

## rel27 (2026-10-30)

Not published (internal test build).

5 items:

- Reroll the colony name with a die in the founding name box (Q20b)
- National anthems as loud as the other tunes (Q28b)
- La Salle reveals rivers from the colonies' work areas (F33b)
- Washington promotes at 25% before and 50% after the Declaration (F37b)
- integrate.py keeps the other side's regen.py hunks (T28b)

## rel26 (2026-10-30)

Not published (internal test build).

3 items:

- Shared hook dispatcher (one gate for many hooks) (T24c)
- Each European power's own home port on the Europe screen (F64)
- Faster integration (T28)

## rel25c (2026-10-30)

Not published (internal test build).

10 items:

**Stability & saves**

- Investigate a bigger upper-memory block (EMS off) (T26)
- 128 KB of upper memory with EMS off (T26a)
- Sound effects without EMS (T26b)

**Colonies & production**

- Postal service, stage 1 (F53)
- Extra goods, full version (T21b)
- Lumber Factory art (F57)
- Computer players founding colonies under F52 (40 tools) (B51)

**Interface & information**

- Goods bar on the box grid (B50)

**Nations & big features**

- Eight European powers (Portugal, Russia, Denmark, Sweden) (F13)

**Testing**

- Faster test suite (T27)

## rel24c (2026-10-30)

Not published (internal test build).

11 items:

**Stability & saves**

- More upper memory for T21 (T24b)
- Text-width function overflows its 80-byte buffer (B48)

**Colonies & production**

- Extra goods framework (17th good: Letters) (T21)
- Pioneer tools prompt and Europe top-up (F56)

**Founding Fathers**

- Hernan Cortes: royal fifth plus the tax (F34)
- William Brewster: servants come back (F35)
- George Washington: promotion chance (F37)
- Peter Minuit: native land at a quarter price (F38)
- Benjamin Franklin: foreign intervention comes sooner (F32)
- La Salle: whole rivers, river bonus, no stockades (F33)
- Hernando de Soto: bigger rumour gold, scouts see further (F36)

## rel23 (2026-10-29)

Not published (internal test build).

8 items:

- Cold code into on-demand modules (T24)
- Convoy members: wagons and armed units only (F28c)
- One ton over the warehouse cap is not removed (B36)
- AI treaty cancellation shows no message; refused cash offer loses its tone (B29)
- Break Treaty during the cooldown does nothing (B31)
- Cancel-peace message names the nations in the wrong order (B47)
- Disband in view mode changes the active unit (B41)
- Skip the new-game voyage slideshow (F19b)

## rel22 (2026-10-29)

Not published (internal test build).

32 items:

**Stability & saves**

- Long play crashes with evm0012 (B42)
- MODX loader refuses saves above 0x2000 bytes (T22)
- Loadable code modules (T23)
- Build-time check for relocated words (T25)
- Lost City Rumour counters are not reset or saved (B37)

**Combat**

- AI and REF amphibious assaults (E4b)
- Captured colonists (F23)
- Uprisings in occupied colonies (F24)

**Ships & movement**

- Attach / Detach: land units moving as a group (F28)

**Natives & missions**

- Esc in the Incite Indians nation menu picks England (B25)
- Raid horse grab tests the wrong pile (B28)

**Trade routes & wagons**

- Wagon convoys with an escort (F28b)
- Manual loading tops up a part-filled hold only (Q27b)
- Warehouse keep levels only with a Warehouse (B46)

**Colonies & production**

- A colonist dropped on the Lumber Factory does nothing (B24)
- Chapel, a first level before the Church (F27)
- Colony work area has no outline at 12 and 20 squares (B44)
- Abandoned colonies still produce (B45)
- Opening the Jobs menu resets the colonist's turns in the job (B26)
- Out-of-ore warning compares the wrong amounts (B35)
- Construction list loses the current project (B40)
- Jesuit worker cannot "leave as Colonist" in the first four colonies (B38)
- Founding a colony needs a Pioneer with 50 tools (F52)

**Europe, taxes & the Crown**

- The King's wedding count is shared by all nations (R40)
- Smuggling message overflowed its 80-character buffer (B43)
- Dragging a ship in the Europe boxes cancels its orders (B32)
- Europe price pressure flips direction past a ratio of 32767 (B39)

**Interface & information**

- Music from MIDI files in a MUSIC folder (Q28)
- Go to Port picker drops the last colony at 20, 30 or 40 colonies (B27)
- Hall of Fame ignores a 6th-place retirement (B33)
- Goods icons in the village panel (F54)

**Founding Fathers**

- Founding Father selection screen (F50)

## rel21 (2026-10-28)

Not released on its own: this set went out with rel22.

## rel20 (2026-10-28)

Not published (internal test build).

5 items:

- More room for X1 gates (T19)
- Invincible island colonies (amphibious assaults) (E4)
- Automatic loading tops up goods already aboard first (Q27)
- A new colony starts with one house (chosen) (F26)
- Abandoned colonies keep their buildings (F25)

## rel19 (2026-10-28)

Not published (internal test build).

2 items:

- Colony-built ships cost less (F22)
- Nation rebalance (F6)

## rel18 (2026-10-28)

Not published (internal test build).

2 items:

- X1 chain in upper memory (UMB) (T17)
- Warehouse reserve and export levels (Q16)

## rel17c (2026-10-28)

Not published (internal test build).

15 items:

**Stability & saves**

- Unlimited saves with readable names (Q1)
- Rolling autosaves (Q2)

**REF & independence**

- The REF always targets the same colony (A4c)

**Combat**

- Beaten REF Regulars are deleted instead of demoted (R11b)
- Explorer's early attack reduction is stronger than Discoverer's (R77)

**Ships & movement**

- Long land routes ignore roads and lakes (A1a)
- Ships take straight-line paths past enemy warships (A1b)
- Units detour around non-blocking units (A1d)

**Natives & missions**

- The skill a village teaches can change (R67)

**Colonies & production**

- On-the-job learning only works for your first expert (R45)
- Expert Teacher (the unused Teacher profession) (F51)

**Europe, taxes & the Crown**

- Custom House ignores boycotts (R3)

**AI & diplomacy**

- Europeans attack while at peace (A3)
- A European power you have not met attacks your ships (A3b)

**Map generation**

- Hidden fifth world setting (hill-and-mountain scatter) (M3)

## rel15 (2026-10-27)

Not published (internal test build).

3 items:

- Score multiplier overflows on very high scores (B17)
- Units destroyed instead of demoted (R11)
- Map connectivity data missing at diagonals (B15)

## rel13 (2026-10-27)

Not published (internal test build).

1 item:

- Paul Revere: muskets are used up, and colony defenders get a bonus (R73)

## rel10 (2026-10-27)

Not published (internal test build).

1 item:

- Allow abandoning stockaded colonies (F1)

## rel9 (2026-10-27)

Not published (internal test build).

2 items:

- France's native bonus is mostly a rounding effect (R79)
- New pictures for the Colonial Assembly and the Capitol (F20)

## rel8 (2026-10-27)

Not published (internal test build).

1 item:

- Brewster removes the guaranteed every-fourth specialist (R74)

## rel7 (2026-10-27)

Not published (internal test build).

2 items:

- Defender choice ranks only the low byte of defence strength (R80)
- Pocahontas makes small alarm rises vanish (R75)

## rel6 (2026-10-27)

Not published (internal test build).

3 items:

- Refusing the native peace treaty is permanent (R61)
- Skip the opening slideshow with any key or mouse click (F19)
- Memory test: "VICEROY's PSP not in the MCB chain" in the war session (T13)

## rel4 (2026-10-27)

Not published (internal test build).

1 item:

- Remove the wagon-train cap (Q19)

## rel3 (2026-10-27)

Not published (internal test build).

1 item:

- Map overlay: colony work areas and native land (F18)

## rel2 (2026-10-27)

Not published (internal test build).

2 items:

- Lumber Factory (a factory level after the Lumber Mill) (F15)
- Randomized colony names (Q20)

## rel1 (2026-10-27)

Not published (internal test build).

3 items:

- Native units visible in the fog of war (B20)
- Colonopedia lacked Town Hall / Colonial Assembly entries (B21)
- National anthems (Q26)

## Before rel1 (2026-10-22 to 2026-10-26)

Not published. The first fixes, features and decisions, made before the numbered releases began (98 items):

**Stability & saves**

- Reloading an autosave replays the AI turn (B3)
- Unit cap causes stalemates and lost purchases (B7)
- Ending the turn after burning a native capital crashes mod builds (B18)
- Mod hooks crash under memory pressure (DANGER popups, garbage prompts) (T1)
- Measure how much the new-code block can grow (memory budget) (T7)
- Random numbers differed from the original game (B19)

**REF & independence**

- REF lands ships where troops can't get off (B4)
- Sinking every REF Man-o-War stalls the war (B5)
- REF with no regulars surrenders immediately (B6)
- Intervention threshold is fixed per difficulty (R20)
- After the intervention, everyone gets the King's bombard bonus (R56)
- Tory uprising size is taken from the wrong colony (R78)

**Combat**

- "They back down if you are 3x stronger" wraps in a byte (A9)
- AI combat odds ignore easy-level and main-colony modifiers (A10)
- Accurate combat analysis (Q11)
- Fortification and veteran bonuses don't follow the rules shown (R7)
- Bigger navy makes your ships lose more (R9)
- Whole ship stack sinks when the defender loses (R10)
- Defender selection passes a nation number as a unit number (R57)
- Damaged artillery is never repaired (R58)
- Combat-streak RNG (B1)

**Ships & movement**

- Diagonal moves skip warship slowdown (A2)
- Ships left in an abandoned colony crash the game (B8)
- Passengers hop between ships (E1)
- 'Go to Europe' skips a sea-lane move (R5)
- Pacific crossing is no slower than the Atlantic (R6)
- Man-o-War sees only 1 square (R43)
- Ship type does not change the voyage to Europe (R41)

**Natives & missions**

- Hiring a rival against a tribe uses the wrong tribe (A8)
- Refusing natives food corrupts another tribe's record (B16)
- Remember native village information (Q9)
- Reparations always take furs and can make them negative (R36)
- Jesuit pioneer turns back into a missionary when out of tools (R47)
- Natives can raid a colony after losing the attack (R52)
- A brave losing to artillery forces the raid through (R53)
- Jesuits get no heresy bonus (check looks for a Master Cotton Planter) (R62)
- Every mission in the tribe helps the heresy attacker (R63)
- Burning a capital clears another tribe's grudges (R64)
- Native capitals start at ordinary size (R69)
- "Come visit us" after the peace treaty reads the wrong table (R70)
- Spain's better treasure odds are ignored (R60)
- Heresy against a native capital uses the capital flag (4) as a shift count (R82)

**Trade routes & wagons**

- Creating a 12th trade route breaks the game (B10)
- Trade routes say why they stop (Q13)
- Raise the trade-route limit (Q18)
- Trade routes never unload boycotted goods (R1)
- Can't set up wagon routes for boycotted goods (R2)
- "Don't sell the same goods twice" compares the wagon number (R66)

**Colonies & production**

- Pioneer 'pre-charge' (E2)
- Depleting resources drain together (R14)
- Non-prime silver yield ignores roads and rivers (R15)
- Distillery limits not enforced (R16)
- Carpenter's shop can hold more than 3 workers (R17)
- Hammer and bell overflow is thrown away (R18)
- Lake fisherman gives misleading 'need docks' message (R34c)
- Colony on pine resource yields no lumber (R34d)
- Schoolhouse lessons go to a random pupil (R44)
- Major rivers add no extra food (R48)
- A depleted Silver Deposit mines better than a plain mountain (R50)
- Clearing a forest gives a flat 20 lumber without a Lumber Mill (R51)
- Survey: unused building art (Town Hall levels, a Lumber Mill factory) (S2)
- Inefficient-government warning and penalty round differently (Q23)
- Raise unit and colony caps (Q17)
- Larger colony work area (unused Town Hall levels) (F12)
- Capitol as the fourth Town Hall level (F17)

**Europe, taxes & the Crown**

- Equipment stripped in Europe sells untaxed (R4)
- Artillery price rises on 'No' (R34a)
- 'Sell Tools' on the docks always pays for 100 tools (R35)
- Losing the King's frigate reads the tax cut past the price table (R37)
- The Tea Party good is not random (R38)
- England's market ages faster (R39)
- Boycott warning only checks the first hold (Q22)

**AI & diplomacy**

- "Withdraw from our colonies" demand fires without cause (A6)
- Independent rival's withdrawal request has its answers swapped (A7)
- Jan de Witt trade: the foreign colony never loses the goods (R76)
- Jan de Witt trade: the foreign nation never pays the gold (R81)

**Interface & information**

- End-of-turn confirmation on by default (Q3)
- Don't swallow keypresses during goto moves (Q4)
- Consistent unit cycling on stacked tiles (Q8)
- Better DOSBox setup (Q21)
- Colopedia and hint texts that misstate the rules (Q25)

**Founding Fathers**

- Henry Hudson does not boost the colony square's furs (R49)

**Map generation**

- Second forest band is generated, then thrown away (M4)
- Mountain scatter flattens inland mountains (M5)
- Hill scatter reuses leftover odds (M6)
- Rows 2-3 from the poles lose hills and rivers (M7)
- America map turns two islands into lone mountains (M9)
- Aztec and Tupi share a village site on the America map (M10)

**Testing**

- Flaky suite tests block promotion (r58, r57, b5follow) (T9)
- Lost menu clicks still fail suite runs (r35 European Status) (T10)
- Test DOSBoxes outlive a killed test run (T11)
- q9 test fails ~1 run in 4 (chief kills the scout) (T12)
- Test saves start after the introductory popups (T2)
- Test drivers: state checks at every step, and faster tests (T3)
- Document every test scenario (T4)
- Run DOSBox tests in parallel (T5)
- Keep builds, tests and experiments separate from the master build (T6)
- Rare mid-game hang: no End of Turn and no unit waiting (T8)
