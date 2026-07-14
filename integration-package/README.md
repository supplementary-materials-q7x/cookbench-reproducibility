# CookBench environment-integration capsule

This small package contains the environment-side files required by the documented Windows setup:

- `CS_CamDump.dll` — the released environment integration binary (version `20260430.1906`)
- `item_name_mapping.txt` — item-name mapping
- `object_en_ch_mapping.txt` — object-name mapping

## Installation

1. Obtain **Cooking Simulator** and the **Food Network DLC** from their official distributor. These commercial assets are not included or redistributed here.
2. Install **MelonLoader 0.5.7** from its official site: <https://melonloader.co/download/>.
3. Copy `CS_CamDump.dll` to `<Cooking Simulator>/Mods/`.
4. Copy both `.txt` files to `<Cooking Simulator>/UserData/`.
5. Start the game. Press `F12` to toggle object monitoring and `F10` to toggle its text overlay. Seeing the overlay confirms that the integration loaded.

The benchmark code, task definitions, prompts, evaluation scripts, and trajectory format must be obtained from the accompanying public anonymous artifact repository. Put its URL on the reproducibility page before publication.

## Security and licensing boundaries

- This archive contains no API keys, email credentials, private repository URLs, author information, or personal paths.
- It does not include Cooking Simulator, DLC assets, Steam content, model-provider accounts, or closed-model APIs.
- Use this binary only with the matching publicly released benchmark artifact and on a separately licensed local game installation.
