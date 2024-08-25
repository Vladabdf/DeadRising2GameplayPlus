# Vladabdf's Edits to Dead Rising 2

> ## Pick only one download, as both modify the same binary file in the game.

---

## Visual changes made

### Download [here](https://github.com/Vladabdf/DeadRising2GameplayPlus/releases/tag/visualOnly).

> Place ![](./images/file.svg) `datafile.big` inside your ![](./images/folder.svg) `Dead Rising 2/data` folder. Overwrite when asked.

| Effect | Disabled | Altered | Description |
|--------|----------|---------|-------------|
| Depth of Field | :heavy_check_mark: | - | Disable low quality background blur of the world. |
| Game world fog | :heavy_check_mark: | - | Likely made to mask item pop-in on the original Xbox 360 hardware the game was made for. Not needed, even on weaker PC hardware. | 
| Screen vignette | :heavy_check_mark: | - | Cinematic, or whatever. Should always be a toggle rather than forced; now it's gone. |
| Game blur effects | :heavy_check_mark: | - | Even with the in-game toggle off, many blur effects remain. Not all are disabled, but most distracting or intense blur effects are gone. | 
| Luminance variation | - | :heavy_check_mark: | This game is notorious for wildly shifting luminence coverage depending on exactly which spot Chuck is located in every map. Now it will be consistent per-map, rather than highly dynamic or universally uniform. **[Currently WIP]** |
| Light exposure variation | - | :heavy_check_mark: | In conjunction with luminance variation, the game dynamically shifts exposure based on where Chuck is located in every map. Now it will be consistent per-map, rather than highly dynamic or universally uniform. **[Currently WIP]** |
| Field of View | - | :heavy_check_mark: | Default FOV is narrow. Now it's not. |
| TBD | - | - | - |

### Luminance and exposure variation require extensive testing, and thus my fixes for them will not be published for some time. Please be patient, and for a look into comparison images, go [here](comparisons.md).

---

## Additional gameplay changes

### Download [here](https://github.com/Vladabdf/DeadRising2GameplayPlus/releases/tag/gameplayPlus).

> Place ![](./images/file.svg)`datafile.big` inside your ![](./images/folder.svg)`Dead Rising 2/data` folder. Overwrite when asked.
>> *Includes all graphical changes mentioned above*

| Change | Implemented? | Description |
|--------|--------------|-------------|
| Combo weapon magazines | :heavy_check_mark: | Combo weapons now have magazine assignments. There was an attempt at logic toward them. Please take a look [here](./notes/combo.md). |
| TBD | - | - |

---

## Credit to:
* Gibbed Dead Rising 2 Tools
	* Copyright (c) 2011 Rick (rick 'at' gibbed 'dot' us)
	* Permitted to be shared in this repository by the attached [`license`](./Gibbed.DeadRising2.Tools/license.txt)
* The [free-icons repository](https://github.com/free-icons/free-icons) with which I borrowed a couple of icons for this readme to add some ![](./images/sparkles.svg) **flair** ![](./images/sparkles.svg)

---

This mod was originally made to try and fix the game's luminance variation problem, but eventually turned into something a little bit more.

A lot of players on weaker hardware even in 2024 have a hard time handling this game. (This is probably the only time I'll acknowledge Steam's toxic forums.)

Furthermore, the only guide online to disabling some of the slightly intensive (and honestly annoying) effects was posted to the [PCGamingWiki](https://www.pcgamingwiki.com/wiki/Dead_Rising_2). However, the caveat to using those methods to disable these effects relied on the user playing unauthorized retail copies of DR2.

I began posting edits to the PCGW page for DR2 on how people can alter those effects themselves, but they were long and likely would be confusing for the average user. While a couple of my changes still remain on that wiki right now, I will not be posting further changes, as it would honestly be easier to just simply download a file and plop it in your game folder. So, that's what you can do.

### Yay.

---

### Note to PCGamingWiki

I love PCGW. I go to it immediately any time I install a game, new or old, to see what fixes or changes I can make to improve my gaming experience. However, I also notice a lot of binaries are shared directly to PCGW with no link, info, or knowledge on who the creator of said binaries are. Please do not do that with me. If you want to share the binary in question (![](./images/file.svg) `datafile.big`) from my `Releases` page, just link people here. Don't upload the thing to your server with no info.

Thanks.
