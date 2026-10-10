# MisterZine Home label packs

Cartridge label art for the MisterZine Home core, baked into the pack format the core reads.
The packs are release assets, one release per system (the release tag is the system's name):

- `labels16.hlb`: the small labels of every cartridge on the shelf
- `labels256.hlb`: the rich labels, fetched one at a time
- `generic16.hlb`: the label a cartridge wears until its own has arrived
- `names.txt`, `aliases.tsv`: each label's game name, and other names a game goes by

Home fetches these on demand and caches them on the MiSTer's card. This repository holds no
code and no games.

## Sources

| Release | Label art from | Terms |
|---|---|---|
| `n64` | cartridge scans from the Internet Archive's N64 collection | none stated |
| `nes`, `genesis`, `turbografx16` | the LaunchBox Games Database's cartridge fronts, user-contributed (`SOURCES.txt` in each release lists every picture) | none stated |
| `gameboy`, `gba` | the cartridge photos of the Game Boy hardware database, https://gbhwdb.gekkio.fi, by its contributors | CC BY-SA 4.0: these releases are adapted from them and shared under the same licence (`LICENSE.txt`); `CREDITS.txt` names each label's photographer and entry |

Each label is a few dozen texels across, for telling cartridges apart on the shelf.

The label artwork belongs to its respective owners. If you hold rights in any of it and want it
removed, open an issue here and it will be taken down.
