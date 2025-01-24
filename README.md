# OreLight RTX
A simple package used to highlight common ores and create light in cave.
Minecraft RTX required.

## Using
Compress all files in `package` dir to a `.zip`, and change to `.mcpack`,
then open it.

## Adding new ores
Normally you can add new ores by the following instruction. If it doesn't work,
you might need to follow [NVIDIA Official Guide][1].
### Lighting block, eg. stone
Copy `light.texture_set.json`, `light.png`, `light_mer.png` from
`template/light` to the directory the ore stored in `package`,then change `x`
into the id of your block.
### Ore block, eg. diamond_ore
Copy `top.texture_set.json`, `top.png`, `top.png` from `template/top` to the
directory the ore stored in `package`, then change `x` into the id of your ore.

## License
MIT License. When containing Minecraft property (for example, Vanilla
resource pack), [Minecraft EULA][2].

[1]: https://www.nvidia.com/en-us/geforce/guides/minecraft-rtx-texturing-guide/
[2]: https://www.minecraft.net/en-us/eula

