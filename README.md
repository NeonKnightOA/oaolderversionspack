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
* oasago2 (0-7-1-0.8.5)
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

### oa_bases5 (0.7.1)

* Map now editable in newer editors such as GTKRadiant 1.5.0 and NetRadiant 1.6.0.

### am_galmevish (0.8.1)

* The map had a problem which screwed q3map2 compilation. It's fixed.

### ctf_gate1 (0.8.1)

* The map works properly in every gametype.

### ctf_inyard (0.7.7)

* BSPC compilation problem solved by way of botclipping.
* HoMs at the courtyard area fixed. Previously, many glitches were seen.
* Clipping at the central area fixed. Some gameplay may change because of this.

### hydronex (0.7.1)

* Map now editable in newer editors such as GTKRadiant 1.5.0 and NetRadiant 1.6.0.
* Lighting fixed.
* Imbalance with boxes solved.
* Glitches with misaligned walls fixed.

### slimefac (0.7.7)

### ps37ctf (0.8.1)

### am_underworks (0.8.5)

### oasago2 (0.7.1 - used 0.8.5 version)

* Better gametype support (including Possession)
* Replaced those uber-tris torches with lower tris ones (HUGE performance boost, less tris to render)
* Now it compiles!
* New levelshot.
* A bit of rework regarding lighting.
