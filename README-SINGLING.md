## Singling
##### By: Jonathan Vasquez (fearedbliss)
##### Build: 2019-08-12-2057

## Synopsis

A collection of non-gameplay modifications and fixes in
order to improve the Vanilla Diablo II Single Player Experience.

## Supported Versions

- **`1.00`**
- **`1.05b`**
- **`1.07`**
- **`1.09b`**
- **`1.10`**
- **`1.13d`**

## Features

- You can now run multiple clients of Diablo II.
- You are now able to quickly join LAN games.
- Fixed CPU usage bug in Main Menu, Single Player, and LAN games.
- The Battle.net button has been disabled for safety reasons.
- The introduction cinematics are now automatically skipped.
- The massive slowdown when the letters on the top left appears is now fixed.

- **`[1.00-1.10]`** You no longer need the CD in order to play the game.
- **`[1.00-1.10]`** You can now make Hardcore characters without beating Softcore.
- **`[1.00-1.10]`** The window will no longer minimize when you click out of it.
- **`[1.00-1.10]`** The window will now have Minimize and Close buttons.

- **`[1.10-1.13d]`** Battle.net-only Runewords are now enabled on Single Player.

## Notes

- The Main Menu CPU fix will only be applied for **`v1.10+`**, since people not
  using Glide in versions before that would experience massive lag. Most people
  don't spend their time sitting in the Main Menu so this isn't a big deal.

- If you are using Glide, make sure to disable VSYNC in your Glide settings
  or you will still experience high CPU usage in LAN games.

- Due to a Windows bug, the Minimize/Close buttons will not show if you are
  using Glide for versions below **`1.14d`**.
  
- The fix for the massive slowdown when the letters on the top left of the screen appears
  required us to disable the **`/fps`** command.
  
- In order for the **`Prevent Window Minimization`** fix to work, make sure that the game
  was started with **`-w`**. Making the GlideWrapper settings have Window Mode is not enough.

- If you are using **`OBS Studio`**, make sure you use **`Window Capture`** rather than **`Game Capture`**.
  The latter will make the game crash when you exit the game. This is not a bug caused by Singling,
  it also happens with Vanilla D2.

## Patch Rational

#### Patch 1.00

This patch was selected due to it simply being the first version of Diablo II released.
There are a few things this patch has that you can't do in **`1.05b`**, however it also
is obviously an unpolished version with many bugs and some crashes.

#### Patch 1.05b

This patch was picked over **`1.06`** since the only reason **`1.06`** was released
was to implement anti-duping code. The dupes that the game would delete on Single Player
could have been legitimately found. This is because the game sometimes assigns the same
fingerprint to a new drop. It was also kept because it is the most stable version of the game
before **`Lord of Destruction`**.

#### Patch 1.07

This patch was selected because it is the first version of **`Lord of Destruction`**
that was released and was the first massive change to Diablo II. Due to this, it contains
a lot of features that were immediately patched out in Patches **`1.08`** and **`1.09`**,
and it also contains a lot of bugs (Some which are fun like full rejuv bug or MPK rings).

#### Patch 1.09b

This patch was picked over **`1.09d`** because it is the most stable version of Diablo II
before the massive changes implemented in 1.10, and also because it contains **`players 64`**
and also working CtC. **`1.09d`** has broken CtC which means that you will see the animation
of your CtC effect, but it actually won't do anything.

#### Patch 1.10

This patch was picked because it was the last patch released by Blizzard North,
it was the second patch in the series that massively redesigned the game and made
it primarily balanced for Multiplayer, and lastly it is the patch that has the
most mod support.

#### Patch 1.13d

This patch was selected because it is the last patch released by Blizzard
that is the fully developed version of the game with all quality of life
improvements (respecs, higher rune drop rates, etc), window improvements, etc.
It was also selected because it is the last patch that contained the original
program architecture, which contained all code in their own separate dlls.
Thus this will be the last supported version by Singling.
