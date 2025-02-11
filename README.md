# Texts  
Official texts repository for MMH55 and the external manual.

To see changes for each release look at the [closed pull requests](https://github.com/Might-Magic-Heroes-5-5/MMH55-Texts-EN/pulls?q=is%3Apr+is%3Aclosed).
- Mod folder has the texts for the mod.
- Skillwheel folder has the texts for the manual

# Guides and Links
- [How to create translation](https://www.moddb.com/mods/might-magic-heroes-55/tutorials/mod-translation-guide).
- [Existing mod translations](https://www.moddb.com/mods/might-magic-heroes-55/addons).

> **Important:** The files are kept in the repo in **UTF-8** format instead of the **UTF-16 LE BOM** which the game uses.  
> This is required because GitHub cannot read and detect changes in UTF-16 format.  
>  
> That is why in the repo you will also find PowerShell scripts:  
> - **`convertUTF8.ps1`** → Converts all files in the `mod` folder to **UTF-8**.  
> - **`prep_game_package.ps1`** → Packages the mod text files (while converting them to **UTF-16**) into `MMH55-Texts-EN.pak` for the game.
