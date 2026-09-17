fun.limited splash faces
========================

Ten typefaces flash through the word "fun.limited" for two seconds before the
site appears, one every 200 milliseconds. All ten are served from this folder.

Each file holds ONLY the ten characters in "fun.limited": . d e f i l m n t u
That is why ten display faces come to 36 KB rather than roughly half a megabyte.

No system fonts
---------------
An earlier version used Impact and Courier New, which need no download because
they sit on most desktops. Android has neither, so two of the ten would not
have been the faces that were chosen. Both were replaced on 12 September 2026
with faces this site serves itself, so the sequence looks the same everywhere.

Renamed on purpose
------------------
Eight of the ten are licensed under the SIL Open Font License with a Reserved
Font Name, and clause 3 of that licence says a modified version may not use the
reserved name. Cutting a font down to ten characters is a modification, so each
family is renamed inside the font file itself and the stylesheet refers to the
new name. The copyright, trademark and licence records inside each file still
carry the original attribution, which the licence requires.

  shipped as             file                original            licence
  FLSplash Static        static.woff2        Rubik Glitch        OFL 1.1
  FLSplash Dimensional   dimensional.woff2   Bungee Shade        OFL 1.1
  FLSplash Deco          deco.woff2          Monoton             OFL 1.1
  FLSplash Pixel         pixel.woff2         Press Start 2P      OFL 1.1
  FLSplash Typewriter    typewriter.woff2    Special Elite       Apache 2.0
  FLSplash Script        script.woff2        Homemade Apple      Apache 2.0
  FLSplash Heavy         heavy.woff2         Stalinist One       OFL 1.1
  FLSplash Drip          drip.woff2          Creepster           OFL 1.1
  FLSplash Poster        poster.woff2        Anton               OFL 1.1
  FLSplash Terminal      terminal.woff2      Space Mono          OFL 1.1

Do not rename these back. The new names are what keeps the subsetting within
the licence.

Rebuilding
----------
Sources are the google/fonts repository, fetched from raw.githubusercontent.com.
Subset and renamed with fonttools. If a face is ever swapped, subset the
replacement to the same ten characters and give it an FLSplash name too.
