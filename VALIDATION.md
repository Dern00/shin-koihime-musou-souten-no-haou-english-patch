# v1.2.1 validation

## Package

- All 28 game files extracted from the release ZIP match the verified installation byte for byte.
- The ZIP also contains the installation guide. The repository and release package exclude personal saves, system reports, and translation work files.
- The startup configuration uses the original save-folder naming scheme. Test profiles were kept separate.
- The compact game archives contain 781 indexed entries and no unindexed payloads. ZIP entries use a fixed timestamp. The v1.1 build replaces 77 populated Voices introduction frames in one indexed asset.

## Illustrated sequences in v1.2.1

- Loaded representative animated story layers and one corresponding gallery still for each of the five sequences in an isolated test copy. A temporary test scene displayed the game resources directly.
- Independently decoded all 195 distinct edited frames from the packed archive and compared their pixels with the English artwork. The 45 resources contain 206 edited frame occurrences. Frame IDs, dimensions, offsets, and the original scenario scripts were verified.
- The full ZIP contains 28 game files and the installation guide. Compared all prior patch files against v1.2 and verified each ZIP member against the v1.2.1 manifest.

## Earlier in-game checks

- Opened the redesigned Sousou, Kyocho, and Sonken Chuubou introductions in Settings → Voices.
- Checked all 77 rendered profiles for text fit and verified that the original portraits and frame placement were preserved.

- Launch and native Game Settings, including System Info and Input.
- The longest story passage in the dialogue box and backlog, plus a revised opening page break.
- Rebuilt the backlog Map and Back buttons in both states. Opened the map and returned to the story in the installed game.
- A battle introduction and a four-line skill description on the deployment screen.
- Localized interface spot checks across title, settings, battle, and Extras.
- Main 17 Part 6 ending captions and farewell images, alongside the Shisui Pass and Karin route cards.
- Gallery portraits and both movie thumbnails, Voices profiles, camp, and the first-run and About dialogs.
- The launcher opens the English manual. The opening movie matches its original archive entry.
- The compact archives loaded through the normal launcher and opened a saved camp checkpoint in the test profile.

- Tested the English Classic preview and a long three-line passage and unbroken word in Classic mode. Text advanced normally with the spinning icon hidden. Extra stories and replays use the shared dialogue window, as confirmed by script inspection.
- Opened the localized Music screen and verified the aligned Camp Phase, chapter, and Choices left labels in Chapter 2.
- Scanned the rebuilt native dialog and string-table resources for the 288 Japanese strings flagged in the audit.

- Verified the English Return to Title confirmation during Bandit Subjugation. Yes returned to the title menu, and No was tested during a story scene.
- Verified the redesigned music popup in game and checked text fit for all 121 track titles.

- Verified Sonsaku Hakufu and six other long labels in the battle dialogue nameplates, including Yellow Turban Sect on both sides.

- Verified that the longest story speaker labels fit on one line in Gradient, Panel, and Classic. Panel uses smaller name text aligned with dialogue, and Classic has a wider nameplate that clears the Save and Load controls.

- Verified the longest backlog speaker names on one line and two full three-line dialogue passages in Meiryo regular and bold. The wider speaker column clears the dialogue while preserving its wrap width.

- Verified Save and Load previews with existing and newly created test saves, including a long speaker name on its own line, four wrapped lines of dialogue, and the complete timestamp. Loaded the new test save successfully.

- Verified the repositioned Panel speaker label and the same long three-line passage in Panel and Classic with bold Meiryo. The dialogue clears the right border, and the complete long speaker name fits on one line in both styles.

- Checked all 155 Camp Phase scene IDs against their launch destinations. Updated four card frames and verified the rendered text in each archived frame.
- Verified the English first-clear popup and opening Gallery from Extras. Played the nine new English ending subtitles in game through the transition to the original credits. Checked the timing of all 12,668 video frames and verified the original audio packets.

## Story pagination

- Reviewed page boundaries across 271 story scripts and adjusted 471 passages. Preserved scripted interruptions between speakers.
- Tested both reported Chapter 1 passages in the story window and backlog, then checked manual advance, Auto playback, and loading a test save.

## Text layout audit

- Scanned 81,888 nonempty dialogue and narration records across 271 scenario files. Visually tested representative long passages with Meiryo and bold MS Gothic.
- Checked 456 battle event messages, 11 battle hints, and 788 skill-description fields against their layout limits.
- Compared 20 families of stock and patched portrait and label assets. Checked all 66 rebuilt battle nameplate frames directly in the archive.

These checks covered the working Windows installation and selected saves. Compatibility across every game revision and Windows configuration has not been established.

## Version 1.2.2

- Checked 1,028 revised voiced passages across 178 scripts. Checked the layout of all 83 four-line passages and replayed the widest in Panel mode.
- Replayed Eika’s corrected line, checked Auto advance, and loaded an older Chapter 1 save.
- Verified all three Son Go teaser captions in playback and confirmed the final caption clears before the title card.

## Version 1.2.3

- Checked six formation names on the normal and highlighted deployment and battle buttons, and updated four tutorial illustrations. The fourth formation now reads Encouragement.
- Matched the original defeat sprite against the third game's original at every RGBA pixel. Verified the English sprite after encoding at its original 351 × 222 size and placement.
- Decoded all 19 edited frames and compared them with the source edits. Checked the archive against v1.2.2 and verified all 28 game files in the full ZIP.
