# v1.0 validation

## Package

- All 27 game files extracted from the release ZIP match the tested patch build byte for byte.
- The ZIP also contains the installation guide. The repository and release package exclude personal saves, system reports, and translation work files.
- The startup configuration uses the original save-folder naming scheme. Test profiles were kept separate.
- The compact game archives contain 732 indexed entries and no unindexed payloads. The backlog button update changed four frames in one indexed asset. ZIP entries use a fixed timestamp.

## In-game checks

- Launch and native Game Settings, including System Info and Input.
- The longest story passage in the dialogue box and backlog, plus a revised opening page break.
- Rebuilt the backlog Map and Back buttons in both states. Opened the map and returned to the story in the installed game.
- A battle introduction and a four-line skill description on the deployment screen.
- Localized interface spot checks across title, settings, battle, and Extras.
- Main 17 Part 6 ending captions and farewell images, alongside the Shisui Pass and Karin route cards.
- Gallery portraits and both movie thumbnails, Voices profiles, camp, and the first-run and About dialogs.
- The launcher opens the English manual. The source movie archive matches its original checksum.
- The compact archives loaded through the normal launcher and opened a saved camp checkpoint in the test profile.

## Text layout audit

- Scanned 81,888 nonempty dialogue and narration records across 271 scenario files. Visually tested representative long passages with Meiryo and bold MS Gothic.
- Checked 456 battle event messages, 11 battle hints, and 788 skill-description fields against their layout limits.
- Compared 20 families of stock and patched portrait and label assets. Checked all 66 rebuilt battle nameplate frames directly in the archive.

These checks covered the working Windows installation and selected saves. Compatibility across every game revision and Windows configuration has not been established.
