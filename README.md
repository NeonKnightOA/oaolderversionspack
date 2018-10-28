# OpenArena Older Versions Mappack

This repository holds older versions of OpenArena maps. It's no secret that OA players like these older versions rather than the newer ones. It's also a fact that these versions hold several problems as well, such as bad/missing gametype support (i.e. CTF maps only supporting CTF) so these "improved" old versions aim to fix these problems as well as any extra bugs and glitches.

## Considerations

* The maps have different names, so not to clash with the current ones. For example, am_galmevish from 0.8.1, the map name is 081am_galmevish; am_underworks from 0.8.5 is 085am_underworks and so on...
* These versions are considered non-official versions, and as such, aren't officially supported nor are we going to include them in official releases. If anything, we want to move on from the "ugly" visuals which already makes OA gaming's favourite punchbag.

## Current map list

* am_galmevish (0.8.1)
* am_underworks (0.8.5)
* am_underworks2 (0.8.5)
* ctf_compromise (0.7.7)
* ctf_gate1 (0.8.1)
* ctf_inyard (0.7.7)
* fan (0.7.1)
* hydronex (0.7.1)
* oa_bases5 (0.7.1)
* oa_minia (0.7.7)
* oasago2 (0.7.1)
* oasago2 (0.8.5)
* ps37ctf (0.8.1)
* slimefac (0.7.7)

## General changes (some maps may had these before)

* Location messages added for teamgames.
* Music added.
* Level titles corrected to mirror their OA 0.8.8 counterparts.
* Some rebuilding needed because they contained errors.
* New levelshots.
* Intermission points.
* info_player_start changed to info_player_deathmatch. Every info_player_deathmatch has the "initial" flag set to 1.
* CTF-based maps have support for every CTF-based gametype: CTF, Overload, CTF Elimination, Elimination and Double Domination.
* CTF-based maps with a central area also support One Flag CTF and Harvester.
* FFA-based maps have support for FFA, LMS, and depending on their size, TDM, Tourney, Elimination and Possession (OA3).

## Map-specific changes

### am_galmevish (0.8.1)

* Supported gametypes: FFA, LMS, Tournament, Harvester, Possession.
* 4/10/17: Added support for Possession.
* 4/10/17: Recreated the map with detail brushes, the older brushes just became structural caulked brushes. Should perform better... in spite of its poorly optimized layout.
* 7/10/17: Added support for Harvester.

### am_underworks (0.8.5)

* Supported gametypes: FFA, LMS, Tournament, Possession.
* 7/10/17: Added support for Possession.

### am_underworks2 (0.8.5)

* Supported gametypes: FFA, LMS, Team Deathmatch, Elimination, Domination, Possession.
* 7/10/17: Added support for Possession.

### ctf_compromise (0.7.7)

* Supported gametypes: CTF, One Flag CTF, Harvester, Overload, Elimination, CTF Elimination, Double Domination.
* 7/10/17: Properly tagged key objectives for teamgames.

### ctf_gate1 (0.8.1)

* Supported gametypes: CTF, One Flag CTF, Harvester, Overload, Elimination, CTF Elimination, Double Domination.
* The map works properly in every gametype.
* 7/10/17: Properly tagged key objectives for teamgames.

### ctf_inyard (0.7.7)

* Supported gametypes: CTF, One Flag CTF, Harvester, Overload, Elimination, CTF Elimination, Double Domination.
* BSPC compilation problem solved by way of botclipping.
* HoMs at the courtyard area fixed. Previously, many glitches were seen.
* Clipping at the central area fixed. Some gameplay may change because of this.
* 7/10/17: Properly tagged key objectives for teamgames.

### fan (0.7.1)

* Supported gametypes: FFA, LMS.
* 6/10/17: Improved bot playing. Bots now won't throw themselves to the pit as often as before.
* 6/10/17: Added more spawnpoints, in order to prevent telefragging.

### hydronex (0.7.1)

* Supported gametypes: CTF, One Flag CTF, Harvester, Overload, Elimination, CTF Elimination, Double Domination.
* Map now editable in newer editors such as GTKRadiant 1.5.0 and NetRadiant 1.6.0.
* Lighting fixed.
* Imbalance with boxes solved.
* Glitches with misaligned walls fixed.
* 6/10/17: Added more spawnpoints (previously only 4 per team, now 10)
* 6/10/17: Clipped ramps.
* 6/10/17: Some minor optimizations.
* 7/10/17: Properly tagged key objectives for teamgames.

### oa_bases5 (0.7.1)

* Supported gametypes: CTF, One Flag CTF, Harvester, Overload, Elimination, CTF Elimination, Double Domination.
* Map now editable in newer editors such as GTKRadiant 1.5.0 and NetRadiant 1.6.0.
* 6/10/17: Added more spawnpoints for team games.
* 6/10/17: Fixed bad texture scaling.
* 6/10/17: Fixed overbright ambient lighting.
* 7/10/17: Properly tagged key objectives for teamgames.

### oa_minia (0.7.7)

* Supported gametypes: FFA, LMS, Tournament, Elimination, Double Domination, Possession.
* 7/10/17: Added support for Possession.
* 7/10/17: Backport of support for Double Domination and Elimination from 0.8.8 minia.
* 28/10/18: Leak fix, more changes pending.

### oasago2 (0.7.1 & 0.8.5 versions)

* Supported gametypes: CTF, One Flag CTF, Harvester, Overload, Elimination, CTF Elimination, Double Domination.
* Better gametype support (including Possession)
* Replaced those uber-tris torches with lower tris ones (HUGE performance boost, less tris to render)
* Now it compiles!
* New levelshot.
* A bit of rework regarding lighting.
* 7/10/17: Properly tagged key objectives for teamgames.
- TO-DO: Improvement of the performance in both versions.

### ps37ctf (0.8.1)

* Supported gametypes: CTF, One Flag CTF, Harvester, Overload, Elimination, CTF Elimination, Double Domination.
* Fixed map leaks originated by use of wrong textures.
* 7/10/17: Properly tagged key objectives for teamgames.

### slimefac (0.7.7)

* Supported gametypes: FFA, LMS, Tournament.
* 7/10/17: Added support for Possession.
