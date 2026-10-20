# Katana Sharpening

A Project Zomboid (Build 42) mod that lets you sharpen the katana.

The katana is the only long blade in the game without the `base:sharpenable`
tag, so the vanilla sharpening recipes (whetstone, file and grindstone) never
accept it. Melee damage is scaled by `(Sharpness + 1) / 2`, so a dull katana
deals half damage — and there was no way to sharpen it back.

This mod adds the missing tag, and matches the katana durability to the sword
and the machete so it does not dull or break before the other blades.

- Workshop: <https://steamcommunity.com/sharedfiles/filedetails/?id=3823119413>
- Mod id: `KatanaSharpening` (the value that goes in a server `Mods=` list)
- Requires Build 42 or newer. No other mods needed.

## Layout

```
mods/KatanaSharpening/     the mod published to the Workshop
workshop/listing.json        listing data: title, descriptions per language
workshop/preview.png       cover image, 256x256
workshop/gallery/          carousel images, 1280x720
```

The listing images and the upload itself are handled by
[pz-mod-toolbox](https://github.com/facundoramos-dev/pz-mod-toolbox).

## License

GPL-3.0, see [`LICENSE`](LICENSE).
