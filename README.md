# Roblox ImGui

An ImGui library for Roblox that doesn't require a `RenderStepped` connection.

Perfect for beginners and performance.

## Screenshots

--------

## Notices

* This UI library is in beta. Please report any bugs by opening an issue.
* Any feedback or suggestions would be greatly appreciated.
* Please mention me when integrating this library — **depso**.

## Usage and Documentation

For documentation and usage examples, please read the Wiki.

### Roblox Studio

If you would like to use this in Studio:

1. Create a ModuleScript and paste the library source code into it.
2. Download the Prefabs UI and insert the `ScreenGui` under the ModuleScript.

```lua
local ReplicatedStorage = game:GetService("ReplicatedStorage")

local ImGui = require(ReplicatedStorage.ImGui)
```
**Though**, I doubt anyone is using this for their debug guis because it is intended for an exploit enviroment.

### Exploit / Executor

Reference detections have been mitigated using `cloneref`, and compatibility is checked automatically.

If support is not found, for example when using this in Studio, you are still able to use it.

```lua
loadstring(game:HttpGet('https://raw.githubusercontent.com/water5202/Dear-ImGui/refs/heads/main/BetterReGui.lua'))()
```
you can also use the **deprecated** deptho's ImGui Library
```lua
local ImGui = loadstring(game:HttpGet("https://raw.githubusercontent.com/water5202/Dear-ImGui/refs/heads/main/ImGui.lua"))()
```

## Forking This

If you would like to create your own version for whatever reason:

### Prefabs

Download: **Prefabs**

Make sure you change `UIAssetId` under the ImGui configuration inside the source code.

### Library

Source code

## Demos / Usage Examples

The demonstration window can be found here.

More usage examples can be found on the Wiki.

## Final statement

None of this code is mine and all belongs to **depthso**
