# ICARUS Breeding Tool

**Genetics · Pedigree · Breeding Advisor**

Breeding Tool is a community mod for **ICARUS** that automatically records your animals, their genetics, bloodlines and ancestry.

Track your breeding collection, explore family trees, compare potential parents and plan future generations.

## Download

- **[Download on GitHub](https://github.com/taitsuo/Icarus-BreedingTool/releases/latest)**
- **[Download on Nexus Mods](https://www.nexusmods.com/icarus/mods/373?tab=description)**
- **[Open the Web Advisor](https://icarus-breeding-tools.github.io)**

On GitHub, download **Brreding.Tool.zip** from the latest Release under *Assets*, not the automatically generated Source code archives.

## Features

- **Automatic animal tracking** — Records genetics, bloodlines, ancestry and breeding information.
- **Interactive Pedigree** — Explore family relationships and breeding history.
- **Breeding Board** — Organize animals and manage breeding pairs.
- **Breeding Advisor** — Compare combinations, estimate offspring genetics and find promising pairs.
- **Advanced Breeding Panel** — View breeding information and predictions inside ICARUS.
- **Breeding Scanner** — Portable access to breeding information.

## Installation

**Requirements**

- ICARUS (PC)
- UE4SS `v3.0.1-1181-g83330635` (tested version)
- Included BreedingTool Lua mod (`v1.1.0`)
- Included AdvancedBreedingPanel PAK (`v1.0.1`)

**Steps**

1. Install the specified UE4SS version in `Icarus\Icarus\Binaries\Win64\`.
2. Extract the downloaded ZIP and copy its included `UE4SS` folder into the same `Win64` directory, merging folders as necessary. Preserve your existing UE4SS configuration and other mods.
3. Install the included `.pak` using either:
   - **Manual installation:** copy it to `Icarus\Icarus\Content\Paks\mods\`.
   - **Icarus Mod Manager:** use IMM V2.5.2 → **Extract Mod from PAK File**, then add the mod to your install list and merge/install your mods. Install the Lua component separately as described in step 2.
4. Launch ICARUS and enter your world.

Do not install the same PAK through both methods.

## Getting Started

Craft the **Advanced Breeding Panel** and **Breeding Scanner** at the Fabricator or Manufacturer.

Use the **Wall version** of the Advanced Breeding Panel to access all its controls.

To use the Web Advisor:

1. Open [Breeding Advisor](https://icarus-breeding-tools.github.io ).
2. Click **Connect folder**.
3. Select `Icarus\Icarus\Binaries\Win64\ue4ss\Mods\BreedingTool`.
4. Explore the **Pedigree**, **Board** and **Advisor**.
5. Use **Send to Breeding Panel** to transfer your selected pair and its predictions into the game.

## Important Notes

- Breeding Tool observes the existing genetics system; it does **not** modify genetics, breeding speeds or mutation probabilities.
- Genetic predictions are estimates, not guaranteed outcomes.
- Animal records and preferences are stored in local JSON files. The Web Advisor does not upload your animal data.
- **Back up your `BT_*.json` files before updating or uninstalling.** Never delete your existing data folder merely to update the mod.
- Only the specified UE4SS version has been validated.

## Feedback & Support

Found a bug or have an improvement idea?

Visit the **[Nexus Mods page](https://www.nexusmods.com/icarus/mods/373?tab=posts)** to share feedback.

When reporting a problem, include your ICARUS version, installed mod versions and steps to reproduce the issue.

---

Developed by **Taitsuo**.

Unofficial community mod for ICARUS. Powered by UE4SS.