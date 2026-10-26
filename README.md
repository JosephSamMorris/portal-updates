# Portal – Solar Viewer: firmware updates

This repository only holds firmware releases for *Portal – Solar Viewer* pieces.
The pieces read `portal-update.json` from the latest release here and install a
newer build overnight (3–5 am local time).

- Each release has two files: `portal_R3_xx_signed.bin` (the firmware with its
  signature) and `portal-update.json` (its name, build number, file and size).
- Pieces install only builds signed with the artist's private key; anything
  else is refused, whoever uploads it.
- The release tagged `test` (a pre-release) is for the artist's own board,
  which tries each build before it goes to everyone.

The firmware's source is kept privately.
