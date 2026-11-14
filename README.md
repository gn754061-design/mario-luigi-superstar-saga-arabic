# Mario & Luigi: Superstar Saga - Arabic Translation Patch

Arabic fan translation patch for *Mario & Luigi: Superstar Saga* (GBA, EU ROM).

The patch is a **BPS binary patch**: it stores only the byte differences between
the original ROM and the translated ROM. It contains no original game data, no
code, and no assets. Apply it to your own legally obtained dump of the EU ROM.

## Applying

Use any BPS-capable patcher (Floating IPS, beat, or flips):

    floating-ips --apply MLSS_EU_AR.bps "Superstar Saga (EU).gba"

## Repository layout

- `MLSS_EU_AR.bps` - the patch itself, also attached to the latest GitHub Release.
- The build tooling for the Arabic glyph pipeline lives in the companion repository
  `arabic-gba-glyphs`.

This is a non-commercial fan project. Nintendo and Nintendo of Europe own all
rights to the original game. If you do not own the game, this patch is of no use
to you.

