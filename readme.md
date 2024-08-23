# Vladabdf's Edits to Dead Rising 2

## Pick only one download, as both modify the same binary file in the game.

---

### Visual changes made

#### Download [here](https://github.com/Vladabdf/DeadRising2GameplayPlus/releases/tag/visualOnly).

> Place <svg xmlns="http://www.w3.org/2000/svg" height="1em" fill="currentColor" viewBox="0 0 512 512"> <path d="M 64 64 Q 65 37 83 19 L 83 19 L 83 19 Q 101 1 128 0 L 288 0 L 288 0 L 288 128 L 288 128 Q 288 142 297 151 Q 306 160 320 160 L 448 160 L 448 160 L 448 448 L 448 448 Q 447 475 429 493 Q 411 511 384 512 L 128 512 L 128 512 Q 101 511 83 493 Q 65 475 64 448 L 64 64 L 64 64 Z M 448 128 L 320 128 L 448 128 L 320 128 L 320 0 L 320 0 L 448 128 L 448 128 Z" /> </svg> `datafile.big` inside your `Dead Rising 2/data` <svg xmlns="http://www.w3.org/2000/svg" height="1em" fill="currentColor" viewBox="0 0 512 512"> <path d="M 64 480 L 448 480 L 64 480 L 448 480 Q 475 479 493 461 Q 511 443 512 416 L 512 160 L 512 160 Q 511 133 493 115 Q 475 97 448 96 L 288 96 L 288 96 Q 272 96 262 83 L 243 58 L 243 58 Q 224 33 192 32 L 64 32 L 64 32 Q 37 33 19 51 Q 1 69 0 96 L 0 416 L 0 416 Q 1 443 19 461 Q 37 479 64 480 L 64 480 Z" /> </svg> folder. Overwrite when asked.

| Effect | Disabled | Enabled | Altered | Description |
|--------|----------|---------|---------|-------------|
| Depth of Field | :heavy_check_mark: | - | - | Low quality background blur of the world. |
| Game world fog | :heavy_check_mark: | - | - | Likely made to mask item pop-in on the original Xbox 360 hardware the game was made for. | 
| Screen vignette | :heavy_check_mark: | - | - | Cinematic, or whatever. |
| Game blur fx | :heavy_check_mark: | - | - | Even with the in-game toggle off, many blur effects remain. | 
| Luminance variation | :heavy_check_mark: | - | - | This game is notorious for wildly shifting luminence coverage depending on exactly which spot Chuck is standing at. |
| Field of View | - | - | :heavy_check_mark: | Default FOV is narrow. Now it's not. |
| TBD | - | - | - | - |

> Currently, the "fix" I implemented for luminance just disables the built-in shifting of it as you move to different areas within the game. It helps with the jarring flashbangs, but has the unfortunate side effect of making some areas far too bright.
> > It may be **removed** soon, until I can figure out some other workarounds to work alongside it. Unfortunately, due to how many variables are at play, that may take a lot longer than anything else done thus far.

---

### Additional gameplay changes

#### Download [here](https://github.com/Vladabdf/DeadRising2GameplayPlus/releases/tag/gameplayPlus).

> Place <svg xmlns="http://www.w3.org/2000/svg" height="1em" fill="currentColor" viewBox="0 0 512 512"> <path d="M 64 64 Q 65 37 83 19 L 83 19 L 83 19 Q 101 1 128 0 L 288 0 L 288 0 L 288 128 L 288 128 Q 288 142 297 151 Q 306 160 320 160 L 448 160 L 448 160 L 448 448 L 448 448 Q 447 475 429 493 Q 411 511 384 512 L 128 512 L 128 512 Q 101 511 83 493 Q 65 475 64 448 L 64 64 L 64 64 Z M 448 128 L 320 128 L 448 128 L 320 128 L 320 0 L 320 0 L 448 128 L 448 128 Z" /> </svg> `datafile.big` inside your `Dead Rising 2/data` <svg xmlns="http://www.w3.org/2000/svg" height="1em" fill="currentColor" viewBox="0 0 512 512"> <path d="M 64 480 L 448 480 L 64 480 L 448 480 Q 475 479 493 461 Q 511 443 512 416 L 512 160 L 512 160 Q 511 133 493 115 Q 475 97 448 96 L 288 96 L 288 96 Q 272 96 262 83 L 243 58 L 243 58 Q 224 33 192 32 L 64 32 L 64 32 Q 37 33 19 51 Q 1 69 0 96 L 0 416 L 0 416 Q 1 443 19 461 Q 37 479 64 480 L 64 480 Z" /> </svg> folder. Overwrite when asked.
>> *Includes all graphical changes mentioned above*

| Change | Implemented? | Description |
|--------|--------------|-------------|
| Combo weapon magazines | :heavy_check_mark: | Combo weapons now have magazine assignments. |
| TBD | - | - |

#### View the changes to combo weapons [here](./notes/combo.md).
---

## Credit to:
* Gibbed Dead Rising 2 Tools
	* Copyright (c) 2011 Rick (rick 'at' gibbed 'dot' us)
	* Permitted to be shared in this repository by the attached [`license`](./Gibbed.DeadRising2.Tools/license.txt)
* The [free-icons repository](https://github.com/free-icons/free-icons) with which I borrowed a couple of icons for this readme to add some <svg xmlns="http://www.w3.org/2000/svg" height="1em" fill="currentColor" viewBox="0 0 512 512">
  <path d="M 328 85 Q 320 88 320 96 Q 320 104 328 107 L 384 128 L 384 128 L 405 185 L 405 185 Q 408 192 416 192 Q 424 192 427 185 L 448 128 L 448 128 L 505 107 L 505 107 Q 512 104 512 96 Q 512 88 505 85 L 448 64 L 448 64 L 427 8 L 427 8 Q 424 0 416 0 Q 408 0 405 8 L 384 64 L 384 64 L 328 85 L 328 85 Z M 205 73 Q 201 64 191 64 Q 181 64 176 73 L 123 187 L 123 187 L 9 240 L 9 240 Q 0 245 0 255 Q 0 265 9 269 L 123 322 L 123 322 L 176 436 L 176 436 Q 181 445 191 445 Q 200 445 205 436 L 258 322 L 258 322 L 372 269 L 372 269 Q 381 264 381 254 Q 381 245 372 240 L 258 187 L 258 187 L 205 73 L 205 73 Z M 384 384 L 328 405 L 384 384 L 328 405 Q 320 408 320 416 Q 320 424 328 427 L 384 448 L 384 448 L 405 505 L 405 505 Q 408 512 416 512 Q 424 512 427 505 L 448 448 L 448 448 L 505 427 L 505 427 Q 512 424 512 416 Q 512 408 505 405 L 448 384 L 448 384 L 427 328 L 427 328 Q 424 320 416 320 Q 408 320 405 328 L 384 384 L 384 384 Z" />
</svg> **flair** <svg xmlns="http://www.w3.org/2000/svg" height="1em" fill="currentColor" viewBox="0 0 512 512">
  <path d="M 328 85 Q 320 88 320 96 Q 320 104 328 107 L 384 128 L 384 128 L 405 185 L 405 185 Q 408 192 416 192 Q 424 192 427 185 L 448 128 L 448 128 L 505 107 L 505 107 Q 512 104 512 96 Q 512 88 505 85 L 448 64 L 448 64 L 427 8 L 427 8 Q 424 0 416 0 Q 408 0 405 8 L 384 64 L 384 64 L 328 85 L 328 85 Z M 205 73 Q 201 64 191 64 Q 181 64 176 73 L 123 187 L 123 187 L 9 240 L 9 240 Q 0 245 0 255 Q 0 265 9 269 L 123 322 L 123 322 L 176 436 L 176 436 Q 181 445 191 445 Q 200 445 205 436 L 258 322 L 258 322 L 372 269 L 372 269 Q 381 264 381 254 Q 381 245 372 240 L 258 187 L 258 187 L 205 73 L 205 73 Z M 384 384 L 328 405 L 384 384 L 328 405 Q 320 408 320 416 Q 320 424 328 427 L 384 448 L 384 448 L 405 505 L 405 505 Q 408 512 416 512 Q 424 512 427 505 L 448 448 L 448 448 L 505 427 L 505 427 Q 512 424 512 416 Q 512 408 505 405 L 448 384 L 448 384 L 427 328 L 427 328 Q 424 320 416 320 Q 408 320 405 328 L 384 384 L 384 384 Z" />
</svg>
	* Seriously, check it out. They have a TON of icons, free to use.

---

This mod was originally made to try and fix the game's luminance variation problem, but eventually turned into something a little bit more.

A lot of players on weaker hardware even in 2024 have a hard time handling this game. (This is probably the only time I'll acknowledge Steam's toxic forums.)

Furthermore, the only guide online to disabling some of the slightly intensive (and honestly annoying) effects was posted to the [PCGamingWiki](https://www.pcgamingwiki.com/wiki/Dead_Rising_2). However, the caveat to using those methods to disable these effects relied on the user playing unauthorized retail copies of DR2.

I began posting edits to the PCGW page for DR2 on how people can alter those effects themselves, but they were long and likely would be confusing for the average user. While a couple of my changes still remain on that wiki right now, I will not be posting further changes, as it would honestly be easier to just simply download a file and plop it in your game folder. So, that's what you can do.

## Yay.

---

### Note to PCGamingWiki

I love PCGW. I go to it immediately any time I install a game, new or old, to see what fixes or changes I can make to improve my gaming experience. However, I also notice a lot of binaries are shared directly to PCGW with no link, info, or knowledge on who the creator of said binaries are. Please do not do that with me. If you want to share the binary in question (`datafile.big`) from my `Releases` page, just link people here. Don't upload the thing to your server with no info.

Thanks.
