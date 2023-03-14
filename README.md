# Schale Archive

## Overview

This repository contains [Blue Archive](https://bluearchive.nexon.com/home "Blue Archive") game assets. For now, it's only contains Character Skeletal Animation (Spine 2D) aka Live 2D.

## How to Properly Import Character to Spine Editor

- First, you need Spine Editor at least v3.8.x and later because Blue Archive character spine is produced in Spine Editor v.4.3.8.96.
- Create a new project.
- Delete the default skeleton in `Hierarchy` on the right.
- Click Spine logo on top left, then select `Import Data`.
- Select skeleton data (`.skel`) file. Uncheck `New Project` and select `Create a new skeleton`. Name it whatever you want then `Import`.
- After successfuly imported, click Spine logo and select `Texture Unpacker`. Select atlas (`.atlas`) file where the texture is located and set the output folder then `Import`.
- After imported, click `Images` in `Hierarchy`. Set the path on botttom right to where the unpacked texture is located.
- That's it, you have successfully import the character to Spine Editor.
- If you want to see the animations, click `SETUP` on top left then expand the `Animations` in `Hierarchy`. Click `little dot` on the left of animation name and click Play Backward `<` or Play Forward `>` in the `Dopesheet` on the bottom left.

## Known Missing Character Spine

### Students

- Junko

### NPC

- GSC President
- ~~Yume~~
- ~~Nao~~
- Nagusa
- ~~Nyanten-maru~~
- ~~Pei~~
- ~~Reizyo~~
- A.R.O.N.A
- Colconde

## Notes

- If you change the character image (`.png`) name, don't forget to also rename the other files.  
  Then open and edit `.atlas` file, on the second line change the name to the current character image `.png`.

## Disclaimer

Any game assets and resources in this repository is the property and copyright of Nexon, NEXON Games Co., Ltd.
