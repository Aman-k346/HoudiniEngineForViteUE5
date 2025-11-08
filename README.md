# Houdini Engine for Vite Studio's Physx Unreal Engine 5.0

## Compatibility

This plugin has been **tested with Houdini 20.5.278** and **Vite Studio’s Unreal Engine 5.0**.
It may work with other builds, but they have not been tested.
If you encounter any issues, please create a **GitHub Issue** in this repository.

Prebuilt binaries are available in the [Releases](https://github.com/Aman-k346/HoudiniEngineForViteUE5/releases) section.
The full source code for the Unreal Engine 5.0 plugin is provided in this repository.

---

## Installation

1. Go to the **[Releases](https://github.com/sideeffects/HoudiniEngineForUnreal/releases)** page.
2. Download the Houdini Engine version that matches your Houdini installation.
3. Extract the **HoudiniEngine** folder to your Unreal Engine **Plugins\Runtime** directory.

   You can install it in one of the following locations:

   * **Engine-wide installation**
     `C:\Program Files\Epic Games\UE_5.0\Engine\Plugins\Runtime\HoudiniEngine`

   * **Project-specific installation (recommended)**
     `C:\Unreal Projects\MyGameProject\Plugins\HoudiniEngine`

**Note:** For Unreal Engine 5, the plugin must be installed in your **project’s Plugins** folder.

---

## Verifying Installation

1. Open a new or existing Unreal project.
2. Verify that **Houdini Engine** appears in the **main menu bar**.
3. Check the plugin version:

   * Go to **Edit → Plugins**
   * Search for **Houdini Engine**
   * Confirm that the version (H20.5.x) matches your installed Houdini version.

For more information about exporting and importing Houdini Digital Assets (HDAs), see the [SideFX documentation](https://www.sidefx.com/docs/unreal/_assets.html).

---

## Building from Source

1. Create a `Plugins` folder in your Unreal project root if one does not already exist.
2. Clone or download this repository into that folder.
3. Right-click your `.uproject` file and select **Generate Visual Studio project files**.
4. Build the project and launch Unreal Engine.

