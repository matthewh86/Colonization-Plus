# Changelog

Each release is a patcher for your own copy of Sid Meier's Colonization (DOS 3.0, GOG or Steam). Item ids are the project's work-item ids.

## rel59 (2026-11-13)

First published patcher. It contains all work finished up to rel59 (257 items):

#### Stability & saves
- Native units visible in the fog of war (B20)
- Score multiplier overflows on very high scores (B17)
- Unlimited saves with readable names (Q1)
- Rolling autosaves (Q2)
- X1 chain in upper memory (UMB) (T17)
- More room for X1 gates (T19)
- Long play crashes with evm0012 (B42)
- MODX loader refuses saves above 0x2000 bytes (T22)
- Loadable code modules (T23)
- Build-time check for relocated words (T25)
- Lost City Rumour counters are not reset or saved (B37)
- Cold code into on-demand modules (T24)
- More upper memory for T21 (T24b)
- Text-width function overflows its 80-byte buffer (B48)
- 128 KB of upper memory with EMS off (T26a)
- Sound effects without EMS (T26b)
- Shared hook dispatcher (one gate for many hooks) (T24c)
- No score after winning the War of Independence (mod regression since T17) (B53)
- Large maps: all-computer games freeze in the 1580s (B71)
- Large Americas: computer turn loops forever (postal roads?) (B72)
- Check: no other mod hook can crash the way B71 did (B73)
- Old saves: one outdated section stops the rest from loading (B77)
- rel59: computer powers found only half as many colonies (B78)
- A message box showed the message file's header instead of a message (B83)
- Hard crash: electing a Founding Father, then clicking another Congress office (B85)

#### REF & independence
- The REF always targets the same colony (A4c)
- Independence rework, stage 1: the War of Succession replaced by three revolution events (F3)

#### Combat
- Units destroyed instead of demoted (R11)
- Beaten REF Regulars are deleted instead of demoted (R11b)
- Explorer's early attack reduction is stronger than Discoverer's (R77)
- Invincible island colonies (amphibious assaults) (E4)
- AI and REF amphibious assaults (E4b)
- Captured colonists (F23)
- Uprisings in occupied colonies (F24)

#### Ships & movement
- Long land routes ignore roads and lakes (A1a)
- Ships take straight-line paths past enemy warships (A1b)
- Units detour around non-blocking units (A1d)
- Map connectivity data missing at diagonals (B15)
- Attach / Detach: land units moving as a group (F28)
- Convoy members: wagons and armed units only (F28c)
- Goto path preview (F97)

#### Natives & missions
- The skill a village teaches can change (R67)
- Esc in the Incite Indians nation menu picks England (B25)
- Raid horse grab tests the wrong pile (B28)
- Large Americas: native villages crowd the coast (B69)
- Other map sizes, stage 3: more native villages than 84 (F10c)
- More native tribes (stages 0 to 2: Inuit, Haida, Mapuche, Guarani; their villages on the America maps) (F99)
- Test fix: Large-map village count check (not a game bug) (B76)

#### Trade routes & wagons
- Warehouse reserve and export levels (Q16)
- Automatic loading tops up goods already aboard first (Q27)
- Wagon convoys with an escort (F28b)
- Manual loading tops up a part-filled hold only (Q27b)
- Warehouse keep levels only with a Warehouse (B46)

#### Colonies & production
- Lumber Factory (a factory level after the Lumber Mill) (F15)
- On-the-job learning only works for your first expert (R45)
- Expert Teacher (the unused Teacher profession) (F51)
- Colony-built ships cost less (F22)
- A new colony starts with one house (chosen) (F26)
- Abandoned colonies keep their buildings (F25)
- A colonist dropped on the Lumber Factory does nothing (B24)
- Chapel, a first level before the Church (F27)
- Colony work area has no outline at 12 and 20 squares (B44)
- Abandoned colonies still produce (B45)
- Opening the Jobs menu resets the colonist's turns in the job (B26)
- Out-of-ore warning compares the wrong amounts (B35)
- Construction list loses the current project (B40)
- Jesuit worker cannot "leave as Colonist" in the first four colonies (B38)
- Founding a colony needs a Pioneer with 50 tools (F52)
- One ton over the warehouse cap is not removed (B36)
- Extra goods framework (17th good: Letters) (T21)
- Pioneer tools prompt and Europe top-up (F56)
- Postal service, stage 1 (F53)
- Postal service, phase 1: abstract Letters (F53b)
- Postal Service art (F59)
- Postal phase 2: Extend and Service network orders (F53c)
- Export chains groundwork (F60a)
- Extra goods, full version (T21b)
- Lumber Factory art (F57)
- Computer players founding colonies under F52 (40 tools) (B51)
- Rename the Chocolatier building to Chocolatier's House (F62b)
- Abandoned colonies become Neutral (F105)
- Goods prices up to 30, and every good's price rebalanced (F107)
- Captured colonists: 'not loyal yet' marker and limits (F106)

#### Europe, taxes & the Crown
- Custom House ignores boycotts (R3)
- Nation rebalance (F6)
- Unique units (Fluyt, East Indiaman, Native Allies, Conquistadors) on a unit-variant framework (F6b)
- Unique units of Portugal, Russia, Denmark and Sweden (Nau, Cossacks, Marineregimentet, Carolean Infantry) (F6c)
- Unique units' follow-up (colony ships, Native Allies colony rule, Colonopedia, computer land units) (F6b2)
- Computer powers count the East Indiaman and mounted Native Allies as armed (F6b3)
- Computer powers' docks colonists become unique units (veterans only) (F6b4)
- Combat analysis lines for the unique units' rules (F6b5)
- The King's wedding count is shared by all nations (R40)
- Smuggling message overflowed its 80-character buffer (B43)
- Dragging a ship in the Europe boxes cancels its orders (B32)
- Europe price pressure flips direction past a ratio of 32767 (B39)
- Each European power's own home port on the Europe screen (F64)
- Europe market rework for 8 powers (home markets) (F63)
- Price groups don't match the Strategy Guide (R19)

#### AI & diplomacy
- Europeans attack while at peace (A3)
- A European power you have not met attacks your ships (A3b)
- AI treaty cancellation shows no message; refused cash offer loses its tone (B29)
- Break Treaty during the cooldown does nothing (B31)
- Cancel-peace message names the nations in the wrong order (B47)
- AI turn hangs when a founder cannot pay the 40 tools (B52)

#### Interface & information
- Colonopedia lacked Town Hall / Colonial Assembly entries (B21)
- National anthems (Q26)
- Randomized colony names (Q20)
- Music from MIDI files in a MUSIC folder (Q28)
- Go to Port picker drops the last colony at 20, 30 or 40 colonies (B27)
- Hall of Fame ignores a 6th-place retirement (B33)
- Goods icons in the village panel (F54)
- Disband in view mode changes the active unit (B41)
- Skip the new-game voyage slideshow (F19b)
- Goods bar on the box grid (B50)
- Reroll the colony name with a die in the founding name box (Q20b)
- National anthems as loud as the other tunes (Q28b)
- Unit shields in the power's map colour, rebels' corner triangle (F55)
- Optional mouse scheme ('Right-Click Moves') (Q30)
- Multi-unit selection by click-and-drag (Q30 mouse scheme) (Q31)
- Skippable closing animation (Q5)
- Intro skipping: logo click skips the whole intro; ship-loading scene ignores clicks on its first slide (B68)
- Show Borders works only when the whole map is revealed (B70)
- Goods bar: two rows switched with Up / Down instead of a sideways scroll (F96)
- Goods rows: click anywhere on the tile to switch rows (F96b)
- Goto path: interaction icon centred on its tile (F97b)
- Colony screen: dead-zone clicks for a selected colonist (F104)
- Colonizopedia: the Game Concepts section can't be opened (B74)
- Europe goods bar: prices of 20+ run into each other (B75)
- Colonizopedia: new goods' experts and terrain bonuses missing; terrain professions out of goods-bar order (B79)
- Chapel: 'building full' message says three colonists; the Chapel holds one (B80)
- Europe: the AUDIENCE button disappears after selling goods off a ship (B81)
- Orders menu: order and visibility of the mod's new orders (B82)
- Map screen colony summary doesn't show the new goods (B84)

#### Founding Fathers
- Founding Father selection screen (F50)
- Hernan Cortes: royal fifth plus the tax (F34)
- William Brewster: servants come back (F35)
- George Washington: promotion chance (F37)
- Peter Minuit: native land at a quarter price (F38)
- Benjamin Franklin: foreign intervention comes sooner (F32)
- La Salle: whole rivers, river bonus, no stockades (F33)
- Hernando de Soto: bigger rumour gold, scouts see further (F36)
- La Salle reveals rivers from the colonies' work areas (F33b)
- Washington promotes at 25% before and 50% after the Declaration (F37b)
- Adam Smith: factories for everyone, Smith's factories make 1.75 goods per raw good (F29)
- Peter Stuyvesant: Custom House for everyone, 15% fee without him (F30)
- Jan de Witt: foreign-colony trade at peace for everyone, better prices and intelligence (F31)
- Drake: prize money for privateers (F40)
- John Paul Jones: a stronger navy (F41)
- Jean de Brebeuf: calmer tribes (F42)
- 65 Founding Fathers: framework (F43)
- Coronado: live intelligence on foreign colonies (F39)
- Unique Founding Fathers (F21)

#### Map generation
- Hidden fifth world setting (hill-and-mountain scatter) (M3)
- Four seasons from 1700 (F65)
- Seasonal home ports (F66)
- Animated sea on the Europe screen (F67)
- Large Americas map (70 x 90) (F10d)
- Large Americas follow-ups (forests, map choice text, landfalls) (F10e)
- Pine Stand: new art (F61b)

#### Nations & big features
- Eight European powers (Portugal, Russia, Denmark, Sweden) (F13)
- National bonuses of Portugal, Russia, Denmark and Sweden (F13b)
- Each nation's own monarch and throne room (F88)
- New Game nation screen: powers Off / Computer / Human, with watch mode (F8a)
- Cheat menu: the four new powers (F98)

#### Testing
- Memory test: "VICEROY's PSP not in the MCB chain" in the war session (T13)
- Faster test suite (T27)
- Faster integration (T28)
- integrate.py keeps the other side's regen.py hunks (T28b)
- X1 segment room (low X1 area, dispatch + boot window, 24 modules) (T29)
- integrate.py space check counts the merged branch (T28c)
- rel28 full-suite failures: r3 and b5giveup (Tests28)
- Low X1 area usable for code (T29b)
- Integration tooling: check_space module records, skipped items, gate_map union (T28d)
- Keystone hex-read bug (gen_mod.Ks16) (REL29)
- Narrower pre-merge gate, regen stability (T30)
- integrate handles modtab.py conflicts and x1lo growth (T31)
- Keystone: retry on assembler errors too (T32)
- Bigger module directory, XMS module cache, second transient slot (T33)
- Postal network rules: Service units per 4 colonies, route groups, capture splits (F53c2)
- Rename Letters to Mail (F68)
- Indigo to Dye chain (F60)
- The fourth Mail button (F53b2)
- Unique units follow-up (Fluyt, East Indiaman, Conquistador, Native Allies) (F6b6)
- A meeting with an original power changed the new powers' colours on screen (B54)
- Free X1 room: move cold resident X1 code into modules (T35)
- Fog of war (F69)
- Postal network reach (F53e)
- Postal correspondence (Home, Foreign, Native) (F53d)
- Pine Resin to Naval Stores chain (F61)
- New figures for the Indigo Planter and Master Dyer (F60b)
- New units and experts in their natural place in lists (F72)
- Units in Map Order (Game Options switch) (F73)
- Labor Advisor counted the new experts under the wrong professions (B55)
- Cacao to Chocolate chain (F62)
- Module code is 8086-clean (no 386 address forms) (T34)
- Export-chain workshops as founding choices (F70)
- Thinned forests and Oasis irrigation (F75)
- In-game jukebox (F76)
- Native raids burn every house; the Carpenter's Yard (F77)
- Tar chain levels: Tar Burner's House, Tar Works, Naval Stores Factory (F80)
- The Continental Congress chamber and 65 full-length fathers (F49)
- Tabs in the build list, the profession menu and the Train list (F78)
- Leader portraits for the eight powers (F13d)
- Meetings with the new powers show blank king and country names (B56)
- Founding Father selection screen in the game's own look (F79)
- Goods in the original's order on the goods bars (F71)
- Paged goods lists in the display order (F71b)
- Colony and Trade Reports in the display order (F71c)
- Map square info lists the new crops' yields on plain squares (B59)
- The jukebox is empty (B57)
- The jukebox's Silence setting does nothing (B58)
- Portugal's mission cross is black (B61)
- Cossack plunder 5%, at most 50 gold (F87)
- The 1492 audience greets a Russian player with the Tsar (F81)
- The new skills' names follow the game's skill / expert pattern (B60)
- The unique land units' Colonopedia pages show the foot and the mounted unit (B62)
- The unique units' Colonopedia pages without purchase and production costs (B63)
- A destroyed village's muskets stay with the tribe (R21b)
- Natives offer tiny 2-ton gifts when your storage is nearly full (R22)
- Trade Founding Fathers' effects (F44)
- Portugal, Russia, Denmark and Sweden have no banner in the throne room (B64)
- Module cache leaked across a program handover (B65)
- Audience with the King (F11)
- Peaceful independence path (F4)
- Exploration Founding Fathers' effects (F45)
- Military Founding Fathers' effects (F46)
- Political Founding Fathers' effects (F47)
- Religious Founding Fathers' effects (F48)
- Dye chain: a Dyemaker's House level (F82)
- The father's biography on the Founding Father screen (F83)
- Entering an unmet village or colony keeps the unit's remaining moves (F84)
- Choose the colony square's secondary crop (F85)
- Carolean Infantry: stronger, attack bonus 20% (F86)
- Upper memory room for the rel53 batch (T37)
- reserve_space can lower IMG_LO for a low block (T38)
- Small and Normal map sizes (stage 1) (F10)
- Quieter notifications: a Messages list in Game Options (Q7)
- Hovering over a unit shows its route (F89)
- Founding Father figures: one body height, 19 redrawn (F91)
- Upper memory room for Large maps and the fathers rebalance (T39)
- Large maps (70 x 90) (F10b)
- Founding Fathers rebalance (first pass) (F90)
- Founding Fathers balance, second pass (F92)
- Distinct Founding Father figures (F93)
- Education Adviser report (Q12)
- Production Adviser report (Q12b)
- Naval Adviser report redrawn (Q12c)
- Save names for Portugal / Russia / Denmark / Sweden games (B66)
- Founding Father screen: the effect in the small font (F94)
- Congress offices: seven officers, the sitting after each election, foreign trade (F95a)
- Congress offices: the Treasurer's factories and Custom House, the President's Declaration (F95b)
- Congress offices: Continentals, the postal network, the Cathedral, the colleges (F95c)
- Crash memory dump for troubleshooting (T41)
- Smarter merge tests: only what the changes touch; full suite on request (T42)
- Free up memory for the next big features (T43)
- Test game windows stay behind other windows (T46)
- rel59 gate: 8 failing suites triaged and fixed before promotion (T47)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel60 (2026-11-14)

Changes since rel59 (work released in rel60, 26 items):

#### Stability & saves
- End of Turn threw the game back to the intro logo, then a hard crash (Russia, Spring 1506) (B87)

#### Ships & movement
- Attach for every land unit, Convoy as an order of its own (F109)

#### Natives & missions
- The Arawak hold the lower Amazon and South America's north coast (F110)
- Leader portraits for the four new tribes (F112)
- The Mapuche and the Guarani take over villages on the original America map (CPM9)

#### Colonies & production
- Colony screen: two quarters with room for two more building chains (T44)
- Profession menu: the new field jobs had no yield off a square (B88)
- Profession menu: the new workshop jobs show what they would make (CPM5)
- Jeweller: Silver into Jewellery (F100)
- Rancher: works the Stable for more horses (F102)
- Foreman: boosts the whole colony's production (F103)

#### AI & diplomacy
- Stronger computer powers (stage 1: expansion and fair founders) (F58)

#### Interface & information
- Dragging a colonist over the empty Warehouse spot popped 'Build a Warehouse' and dropped the drag (B86)
- Audience with the King: shown in the throne room (B89)
- Profession menu: the professions in the order of the goods bar (F108)
- Founding Father selection: no office name on the portraits (F114)

#### Map generation
- Map Editor: Large maps and the new bonuses (stages 1 to 3) (F10f)
- Map Editor: place villages and arrival squares (CPM3)
- The game refuses a map larger than 70 x 90 with a clear message (CPM12)
- Maps smaller than 48 x 60 are checked (CPM14)

#### Nations & big features
- Each nation's America has a name in its own language (F111)
- Nation select: a click on a nation's flag only moves the highlight (F113)

#### Testing
- Conventional memory: free room for the waiting cards (CPM11)
- Release merge: run the generators side by side and the four checks once per batch (CPM7)
- rel60 gate: t41emu and cpm3 fail on the merged build (CPM16)
- Guides: working parallel streams without conflicts, and how to add each kind of content (CPM2)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel62 (2026-11-14)

Changes since rel60 (work released in rel61 to rel62, 4 items):

#### Colonies & production
- Craftsman: Ore and Lumber into Trade Goods (F101)
- Goods list: room for twelve extra goods (needed for Gold and Coinage) (CPM10)

#### Map generation
- Map Editor test f10f: 'bonuses, loaded again' sometimes draws one square more than expected (CPM17)

#### Testing
- Upper memory: room for the wider goods list and the next chains (CPM13)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel63 (2026-11-15)

Changes since rel62 (work released in rel63, 2 items):

#### REF & independence
- Computer powers fight their own War of Independence (F3 stage 2: one war at a time) (F3b)

#### AI & diplomacy
- Attitude between the European powers (CPM21 stage 1) (CPM22)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel64 (2026-11-15)

Changes since rel63 (work released in rel64, 1 items):

#### Nations & big features
- Hot-seat multiplayer, stage 1: 2-8 human powers on one PC (F8)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel65 (2026-11-15)

Changes since rel64 (work released in rel65, 1 items):

#### Colonies & production
- Gold and Coinage: a gold resource, the Moneyer and the Mint line; the Silver Miner renamed (CPM8)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel66 (2026-11-16)

Changes since rel65 (work released in rel66, 2 items):

#### REF & independence
- Intervention force for every rebel, human or computer (CPM20)

#### Testing
- Custom art survey: what the mod drew, and how a hand-painted piece comes back (CPM15)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel67 (2026-11-16)

Changes since rel66 (work released in rel67, 7 items):

#### Colonies & production
- The Expert Teacher costs 2400 to train in Europe (CPM41)
- The Mail button in every colony (CPM37)
- Postal Service options unlock by the network's best postal building (CPM38)

#### AI & diplomacy
- Eight powers' expansion: more colonies and an earlier second colony (steps 1-5) (F13c)

#### Interface & information
- Goods bar: no hover label on the spinner or an empty box (CPM23)
- Nation Select: the coloured frame follows the selected nation (CPM26)

#### Nations & big features
- Russia sees no 'Discovery of the Pacific Ocean' woodcut (CPM28)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel68 (2026-11-16)

Changes since rel67 (work released in rel68, 3 items):

#### Ships & movement
- Go To preview for the square next to the unit (CPM29)
- Go To preview no longer hides units (CPM30)

#### Testing
- ColDump's crash watch ends with the game (CPM44)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel69 (2026-11-16)

Changes since rel68 (work released in rel69, 9 items):

#### Colonies & production
- Expert names by one rule (Head Teacher, Head Postmaster, Master Foreman, Expert planters) (CPM40)
- Colony screen: buildings stop 1 pixel short of the screen edge (CPM60)
- Colony screen: the Mail tab's explanation in white, with links (CPM55)

#### AI & diplomacy
- Computer powers found their first colony early on a site with forest (CPM34)

#### Interface & information
- Colonizopedia: the new goods' conversion line in the original yellow style (CPM56)
- Colonizopedia: Trade Goods shows the Craftsman and its base goods (CPM57)
- Goods bar keys: Enter / Up / Down change row and keep the box, Left / Right round the row (CPM58)

#### Nations & big features
- Hot-seat: every Human power is asked its own leader name (CPM54)

#### Testing
- Custom art export for hand redraw, and the way back in (CPM45)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel71 (2026-11-18)

Changes since rel69 (work released in rel70 to rel71, 21 items):

#### Stability & saves
- Turn skipped, the date stuck after Spring 1539 (game_loop's code changed in memory) (CPM81)
- rel70 gate: f30, f73, r3 and t21b fail (CPM110)

#### Colonies & production
- Unit upkeep in gold each turn (CPM62)
- The Well line (Well, Cistern, Aqueduct) (CPM59)

#### Europe, taxes & the Crown
- Trade at allied powers' home ports (CPM42)

#### AI & diplomacy
- Computer player's Merchantman sails in circles after it loses its colony (CPM73)

#### Interface & information
- The Colony Adviser explains a disloyal colonist's refusal (CPM68)
- Spectate (CPM31)
- Sound switches in the Jukebox (CPM32)
- Message Options (CPM33)
- Foreign units flash into view in the fog during the computer turn (CPM86)
- Religious Adviser reworked: crosses needed, next immigrant, per-colony churches (CPM46)
- Labor Adviser reworked: a 'where colonists work' first page (CPM47)
- Colony Adviser reworked: one screen, a row per colony (CPM48)
- Main title screen redone, with carved signboards and the mod version (CPM51)

#### Founding Fathers
- Peter Minuit made native land free (no totems, no prompt) (CPM101)

#### Testing
- Module directory room for 64 modules (CPM80)
- Room for more buildings: ids past 64 and table rows past 62 (CPM66)
- Catch stale layouts and missing space reservations before merge (CPM108)
- Every game run gets its own TEMP, working folder and profile folder, kept with the results (CPM109)
- Test DOSBox windows are shown by default, also outside hub jobs (CPM106)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel81 (2026-11-22)

Changes since rel71 (work released in rel72 to rel81, 50 items):

#### Stability & saves
- End of a round dropped the game back to the intro (rel72-preview2) (CPM135)
- rel73-preview1: two hard crashes (code-damage guard on the map, invalid opcode in the colony screen) (CPM143)

#### Combat
- Taking a colony from a power in debt handed the debt to the captor (CPM125)
- A nation's only colony gets a defence bonus, so early aggression is harder (CPM128)

#### Natives & missions
- Native villages teach too narrow a range of skills (Resin Tapper at 5 of 5 villages) (CPM74)

#### Trade routes & wagons
- Load (L) tops up a part-filled hold instead of saying the holds are full (CPM91)

#### Colonies & production
- Thinning a forest or founding a colony on one asks first when a bonus would move away (CPM82)
- Every pioneer action that would remove a bonus asks for confirmation (CPM83)

#### AI & diplomacy
- Computer powers start with more units on higher difficulties (CPM127)

#### Interface & information
- Skip Turn can be undone by clicking the unit again (CPM90)
- The turn's price changes in Europe are listed together in one box (CPM97)

#### Founding Fathers
- Founding Father selection: the Confirm? frame confirms, and a white box marks the chosen candidate (CPM98)
- The Foreign Affairs adviser lists the Founding Fathers the computer powers elected, in one box (CPM95)

#### Testing
- No local paths in tracked files; ComfyUI for the art scripts from the hub node (CPM65)
- Crash watch: record player input so crashes can be replayed (CPM113)
- ColDump keeps a log of the player's actions so a game can be replayed (CPM88)
- ColDump shows its version in the tray tooltip and right-click menu (CPM89)
- Exact replay from launch: the watch records the whole game and copies the saves before it starts (CPM139)
- Gate preflight: run the three regen checks in parallel and reuse a passed result (CPM131)
- Replay: per-turn state hash and save image beside the input log (CPM114)
- Stream gates use the open release's integration base as since, not master (CPM132)
- Harness and DOSBox config edits pick a representative in-game set in stream gates (CPM133)

#### Changes
- reserve_space: the X1 room line ignores the boot area (CPM119)
- Gates skip the retry phase when many suites fail (CPM134)
- integrate.py: per-item regen fails a branch that shifts the low blocks (CPM122)
- Smart gate selects t25reloc when a branch declares reloc_ok hits (CPM87)
- ColDump reports flag game code changed in memory (CPM85)
- f6b34 is flaky: a colonist sometimes leaves the docks unarmed (CPM136)
- Autosave rotation deleted a missing COLONY14 (CPM84)
- Disloyal mark: no leftover bar on the blink; top right of the unit tile (CPM75)
- Colony screen: selection box left below the stockade (CPM76)
- Jeweller's House as a colony founding choice (CPM104)
- Colonizopedia: the Mail article in sections (CPM102)
- A computer power that loses its last colony comes back from Europe (CPM126)
- War of Succession transfer clears the loser's CPM126 slot (CPM144)
- Colony screen: no 'Trees' tooltip over the trees (CPM78)
- Rebellion messages show the military adviser portrait (CPM129)
- Ships told to go to Europe do not head for the nearest High Seas (CPM153)
- Cheat: edit a colony's buildings (CPM197)
- Cheat: edit terrain (CPM198)
- Hard crash from professions menu again (CPM202)
- ColDump replay: @UNITFLAG box after the turn-2 START snapshot (CPM124)
- Load cargo (L) fills part-filled holds before taking the most valuable good (CPM176)
- Native Mail correspondence counts only tribes 0-7 (F99 tribes 8-11 missed) (CPM147)
- New orders are hidden in View Mode (Postal Network, Dig Irrigation) (CPM159)
- Support mousewheel scrolling (CPM196)
- Colony screen: Next and Previous buttons cycle between the colonies (CPM193)
- Colonizopedia terrain entries: Irrigation and Thinning bonuses written like the others (CPM181)
- Mini jukebox from a music-note icon by the Colonizopedia button (CPM187)
- Dragging goods from the colony's goods bar added a byte into low memory (CPM220)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel82 (2026-11-23)

Changes since rel81 (work released in rel82, 3 items):

#### Changes
- A selection box dragged around nothing unselected the unit (CPM173)
- The Naval Adviser warns of a ship idle in Europe at the end of a turn (CPM194)
- Jukebox: natural variation of the MIDI songs (CPM195)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel83 (2026-11-23)

Changes since rel82 (work released in rel83, 3 items):

#### Changes
- Postal Adviser report (CPM39)
- Create Unit cheat: the units the mod added (CPM199)
- Terrain changes stay hidden until the tile is seen again (CPM175)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel84 (2026-11-23)

Changes since rel83 (work released in rel84, 3 items):

#### Changes
- tools/hub_plugin.py: add GATE and gate_args (CPM215)
- Postal texts: @POSTUNIT and @POSTSERVE no longer match the Mail code (CPM146)
- Indian Adviser reworked: a row per tribe with villages, missions, mood and arms (CPM49)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel85 (2026-11-23)

Changes since rel84 (work released in rel85, 8 items):

#### Changes
- Intro: the drum track keeps playing under the flag-planting music (CPM93)
- The combined popups should have newlines and highlight (CPM151)
- Price changes and foreign FF elections on new lines, highlighted (CPM154)
- msgkeys suite counts DEBUG.TXT keys as GAME.TXT keys (CPM224)
- Foreign Affairs reworked: all 8 powers on one screen (CPM50)
- Foreign Affairs: drop the old per-power pages after the overview (CPM232)
- A colony adviser popup when captured units and colonies become loyal (CPM164)
- Loadable module table: raise MAX_MODULES (CPM227)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel86 (2026-11-23)

Changes since rel85 (work released in rel86, 3 items):

#### Ships & movement
- Units path past unexplored terrain when the cost is the same (CPM152)

#### Interface & information
- Foreign Affairs overview: a Founding Fathers count per power (CPM236)

#### Testing
- cpm227space check 3 fails on every branch since rel85 (CPM240)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel87 (2026-11-23)

Changes since rel86 (work released in rel87, 2 items):

#### Interface & information
- A divider between Center View and Show Borders (CPM167)
- A divider between Spectate and Retire (CPM169)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

## rel88 (2026-11-24)

Changes since rel87 (work released in rel88, 2 items):

#### Interface & information
- The no-unit Attach / Convoy message has the explorer adviser (CPM172)

#### Testing
- The patcher installs ColDump and starts the crash watch from GOG Galaxy or Steam (CPM251)

#### Installing
Download the Patcher .exe below, run it and pick your Colonization folder. It checks the game files, backs up the originals in COLMOD_BACKUP and can restore them. It contains only the mod's changes, not the game.

From rel88 the patcher also installs ColDump, the crash report tool. With the two boxes ticked (the default) it adds a "Colonization mod" shortcut that starts the crash watch and the game, and a small Windows start-up helper that starts the watch when the game is launched from GOG Galaxy or Steam. Untick them to skip either; Restore removes them again.
