![Overlord of the Blue Sky English logo and key visual](banner.png)

# Shin Koihime † Musou -Kakumei- Souten no Haou English Patch

An English translation patch for BaseSon’s original Japanese Windows release of *Shin Koihime † Musou -Kakumei- Souten no Haou* (真・恋姫†夢想-革命- 蒼天の覇王).

**v1.2.3 · Full English patch for the main story, character routes, battles, menus, and extras**

[![Download v1.2.3](download.svg)](https://github.com/Dern00/shin-koihime-musou-souten-no-haou-english-patch/releases/download/v1.2.3/Shin_Koihime_Musou_Souten_no_Haou_English_Patch_v1.2.3.zip)

[Installation](#installation) · [Existing saves](#existing-saves) · [Removing the patch](#removing-the-patch) · [Report an issue](https://github.com/Dern00/shin-koihime-musou-souten-no-haou-english-patch/issues)

## Features

- English story dialogue, narration, choices, and character routes, including the illustrated ending.
- English comic lettering in five illustrated story sequences and their gallery stills.
- English subtitles for the ending movie dialogue and the three spoken lines in the Son Go teaser.
- Localized title art, menus, settings, map labels, Extras, and an English game manual.
- Redesigned all 77 character introductions in Settings → Voices.
- English battle tutorials, deployment and formation menus, combat dialogue, and skill descriptions.
- Long story passages keep sentences together with selective font sizing and page breaks at sentence boundaries.
- Long voiced lines use smaller text where needed so the dialogue for one voice clip fits in one text box.
- Word wrapping suited to the dialogue box, backlog, and battle text panels.

## Requirements

- Your own installed copy of the original Japanese Windows base game.
- A Windows setup that can already launch the Japanese game. Keep the Japanese locale or compatible environment you normally use for it.

This release targets the base game. A separately distributed Append package is outside its scope.

## Installation

1. Close the game and its launcher.
2. Open the game folder containing `bootmenu.exe` and `souten.exe`. Back up any existing copies of the files listed below and keep a separate copy of your saves.
3. Download the [v1.2.3 release ZIP](https://github.com/Dern00/shin-koihime-musou-souten-no-haou-english-patch/releases/tag/v1.2.3). Extract the patch into the game folder, preserving the `config` and `html` subfolders, and accept file replacements.
4. Open `bootmenu.exe` and choose **Launch Game**. Load a save or start a new game.

| Patch file | Destination |
| --- | --- |
| `update99.int` | Game folder |
| `movie.int` | Game folder |
| `efktex.int` | Game folder |
| `bootmenu.exe` | Game folder |
| `souten.exe` | Game folder |
| `cs2conf.dll` | Game folder |
| `config/startup.xml` | `config` subfolder |
| `boot.hg3`, `banner.bmp` | Game folder |
| `html/` (19 English pages) | Matching paths in the game’s `html` folder |

The release ZIP contains the loose patch files and a plain-text installation guide.

## Existing saves

The patch uses the original save folder. Use **Open Save Folder** in the launcher to find it. Selected existing saves were used during testing. Saved previews and backlog entries may still show text captured by an earlier build. Start a new game for a clean English backlog. The separate launcher title bar uses the original Japanese product name for its installation check. The game window uses the English title.

## Removing the patch

Close the game and launcher. Restore the files you backed up and remove any patch files that were absent from your copy before installation.

## Verification and feedback

The release includes a SHA-256 checksum for the ZIP. See [release metadata](RELEASES.json) and [validation notes](VALIDATION.md) for the package contents and test coverage.

When reporting a problem, include the patch version, where it happened, and steps to reproduce it. For text issues, a screenshot or a short quote helps locate the passage.

## Credits

Original game, story, artwork, music, and branding by **BaseSon** and their respective creators. This is an unofficial fan translation.
