# Schale Archive

## Overview

This repository contains [Blue Archive](https://bluearchive.nexon.com/home "Blue Archive") game assets. For now, it's only contain Spine 2D asset aka Character Skeletal Animation.

## How to Properly Import Character to Spine Editor

- First, you **must** have Spine Editor v3.8.x because Arknights character spine is produced in Spine Editor v.3.8.99.
- Create a new project.
- Delete the default skeleton in `Hierarchy` on the right.
- Click Spine logo on top left, then select `Import Data`.
- Select skeleton data (`.skel`) file. Uncheck `New Project` and select `Create a new skeleton`. Name it whatever you want then `Import`.
- After successfuly imported, click Spine logo and select `Texture Unpacker`. Select atlas (`.atlas`) file where the texture is located and set the output folder then `Import`.
- After imported, click `Images` in `Hierarchy`. Set the path on botttom right to where the unpacked texture is located.
- That's it, you have successfully import the character to Spine Editor.
- If you want to see the animations, click `SETUP` on top left then expand the `Animations` in `Hierarchy`. Click `little dot` on the left of animation name and click Play Backward `<` or Play Forward `>` in the `Dopesheet` on the bottom left.

## Disclaimer

Any game assets and resources in this repository is the property and copyright of Nexon, NEXON Games Co., Ltd..
