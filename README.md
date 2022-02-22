# Panzer Front DC - English tranlsation source files
The source files for the English Panzer Front English translation patch - [Click here for more](https://derplayer.neocities.org/repo/panzerfront/index.html)

## How to use?
First install the font from "FONT" folder ("Mx437_DOS-V_re._JPN16-PZFMod.ttf")
Then you can start the GSMT tool in folder "TEXT_GSMT" and with it open the Project File in "TEXT" folder.
Here you can edit, import/export strings as CSV, generate the game font, patch the 1ST_READ.BIN binary and other files and generate/apply the translation to the game in general.
No support is given for the GSMT tool. (It is a bit buggy.)

I also used my own [PDN-FileTypePVR Plugin for Paint.NET](https://github.com/derplayer/PDN-FileTypePVR), in the creation of this translation.

## Pull requests/Other languages support
Pull requests are welcome. When you find some errors in the translation or want to add other language feel free to do so.
The pull requests could then result in a new patch verison.

## Folder structure

| Folder    | Description                                                                                                                              |
|-----------|------------------------------------------------------------------------------------------------------------------------------------------|
| ARCHIVE   | Archive of older translation files                                                                                                       |
| BUILD     | Build environment for GDI debugging                                                                                                      |
| FONT      | All Font-related files used in the translation                                                                                           |
| GFX       | All graphics that contain English edits (saved in *.pvr directly or as Paint.NET Project file (*.pdn)                                    |
| PATCH     | Contains patch files that are applied on the image of the game (DCP format is used by Universal Dreamcast Patcher)                       |
| TEXT      | Contains the core translation project files                                                                                              |
| TEXT_GSMT | Translation tool, that can open the project file in "TEXT" folder                                                                        |
| WEBSITE   | Source code for the Website, where I host the patch.                                                                                     |
