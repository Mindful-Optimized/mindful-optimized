# 🏗 Litematica

Frequently Asked Questions / commonly used features:

- Q: How do I access anything from the mod?
- A: The main menu of the mod opens by default with the `M` key, and the config menu with `M + C`.

**Note** that if you use a **non-QWERTY** layout, then these keys can be different, such as `M` becoming `,` on AZERTY.

- Q: I don't see any keybinds in the vanilla Controls menu?
- A: Litematica doesn't use the vanilla keybind system.

It uses the custom keybind system from the `malilib` library mod, which supports multi-key keybinds and a lot more features.
The hotkeys are thus only configurable via Litematica's or malilib's own config menus.
Most commonly you would get to the Litematica hotkey menu with `M + C` -> `Hotkeys`.
You can also access these per-mod config menus via the separate Mod Menu mod's mod list, using the gear button for each mod.

- Q: How do I load a schematic?
- A: Put the schematic file to the `.minecraft/schematics/` directory (or use the Open Schematics folder button), and then load it via the `Load Schematics` menu (`M`-> `Load Schematics`).

- Q: How do I create a schematic?
- A: You first create an area selection, and then you save that as a schematic.
The [Area Selections](https://github.com/maruohon/litematica/wiki/Area-Selections) page describes in more detail how the area selection things work in the mod.
If the selected area is large (goes outside of the loaded chunks around your player), then you will need to move around to load all the chunks once.
You will get a `Missing Chunks` message at the bottom right telling you how many chunks are still missing and thus which ones you still need to move in range of.

- Q: How do I move or rotate a loaded schematic?
- A: This is done via the [placement configuration menu](https://github.com/maruohon/litematica/wiki/Placement-Configuration-Menu).
You can get to it via `M` -> `Schematic Placements` -> `Configure`.
You can also access it by default using the hotkey `Numpad Minus`, which opens the GUI for the currently selected placement, if any.
To change which placement is selected, click on one in the `Schematic Placements` list/menu, so that it has the white outline  indicating that it's selected.
You can also use the "tool item" and (while being in the `Schematic Placement` tool mode) middle click while looking at the placement  in-world.
You can also click with the tool to move the placement origin, or use `Alt + mouse scroll` to nudge the placement in the direction you  are looking.

- Q: How do I show for example just one layer of blocks?
- A: Use the [Render Layers](https://github.com/maruohon/litematica/wiki/Render-Layers) menu or the related hotkeys to switch the mode and select the layer to show.

- Q: How to change blocks in the schematic?
- A: Use the [Edit Schematic](https://github.com/maruohon/litematica/wiki/Schematic-Editing) mode.

# [Open Full Guide In Browser](https://github.com/maruohon/litematica/wiki/Basic-Operations#saving-schematics)
(*Minecraft no like 45,000 characters*)