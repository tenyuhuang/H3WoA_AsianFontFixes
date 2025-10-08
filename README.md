# Asian Font Fixes for Hitman WoA

By default, due to the lack of characters in Hitman WoA's font files, the game will fail to display any character that doesn't exist in `font_*.swf` of current language, which is rather confusing in certain circumstances. This mod adds supplementary Asian characters to target languages so they will no longer be displayed as black blocks.

Currently, only Simplified & Traditional Chinese along with Japanese characters are added according to `fonts_chi.swf`, `fonts_tra_chi.swf` and `fonts_jap.swf` found in the game files, and in correspondent styles (`$medium`, `$light`, `$normal` and `$bold`) with open-source fonts (Noto Sans) that blends well with Neue Haas Grotesk which is being used by Latin characters by default.

This mod also aims to resolve the font inconsistency issue introduced by localization for Chinese and Japanese: due to Noto Sans CJK being selected for everything in these localizations, whatever IOI intended to express with Neue Haas Grotesk is (literally) lost in translation. With this mod, Latin characters are reinstated with Neue Haas Grotesk for said locales.

PPS: This is a work of noob, criticism & suggestions definitely welcomed :)

# TODO

-   Do some research on Korean charmaps and add Korean character display support.

> Korean isn't included yet for various reasons: first, I found no reference of a Korean character map from the game. Feel free to reach me if you have a standard Korean charmap and I'll try adding them too; beyond that, since I have little knowledge about the language, QAing anything for Korean is going to be sloppy on my side.

-   (Maybe) Do everything for Russian language too?

> Russian fonts are untouched for more or less the same reasons, whereas I would have less of an idea whether Cyrillic characters are sitting well enough against Chinese and Japanese. For now it is on hold.

-   DONE: ~~Add proper Chinese character display support for Japanese localization, and vice versa;~~
-   DONE: ~~Port Helvetica fonts (for English characters) to Chinese and Japanese localizations.~~
