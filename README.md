
An ImGui library for Roblox that doesn't require a RenderStep connection.
Perfect for beginners and performance.

Screenshots
	
Notices❄1�7
This UI library is in beta, please report any bugs by opening an issue
Any feedback or suggestions would be great
Please mention me when integrating this library - depso.
Usage and documentation
For documentation and usage examples, please read the Wiki

Type
Roblox Studio	
If you would like to use this in Studio:

Create a module script and paste the library source code
Download the Prefabs UI and insert the ScreenGui it under the module script
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local ImGui = require(ReplicatedStorage.ImGui)
Exploit/Executor	
Reference detections have been mitigated using cloneref which compatibility is checked,
if support is not found, for example using this in studio, you are still able to use it.

local ImGui = loadstring(game:HttpGet('https://github.com/depthso/Roblox-ImGUI/raw/main/ImGui.lua'))()
Forking this
If you would like to create your own version for whatever reason,

Prefabs: Prefabs
Make sure you change UIAssetId under the ImGui configuration inside of the source code
Library: Source code
Demos/Usage examples
The demonstration window can be found here
More usage examples can be found on the Wiki
