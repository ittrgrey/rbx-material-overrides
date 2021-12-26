# 2013-17 ROBLOX Built-Ins: Instructions

**Reminder that MaterialService is currently a beta feature and these will not show up yet in Roblox Player, but any lighting changes will.**

1. To begin with, you will want to download the RBXM (Roblox Model) file inside the folder. We recommend using the one with the highest (latest) version tag.
2. Open Roblox Studio.
3. Ensure that in File -> Beta Features that MaterialService is enabled (you might be asked to restart the software after enabling the beta, in which case do that before continuing).
4. Open a place of your choosing, preferably one that you own.
5. Insert the RBXM into Workspace.
6. Inside the Model (in this case, called "2013-17R"), open the **!!SETUP!!** script.
7. Read through the script's instructions and do what it asks - in most cases, you will want to **Select All**, **Copy**, and **Paste** it into Studio's command line and press enter.
8. Assuming it has worked, you should notice a significant change to the visual appearance of your game.

## Manual instructions from after step 5, if the script does not run correctly or you would prefer to see how it works ##
1. Inside the Model (in this case, called "2013-17R"), open the **!!SETUP!!** script.
2. Read through it, and replicate all applicable lighting settings to the Lighting object in Explorer (some are commented out - this pack is designed for use with Compatibility lighting technology for obvious reasons, but Lighting.Technology is not scriptable so this has to be done manually)
3. You will then want to parent elements related to the fake skybox (which should be inside an applicably named folder) to Workspace. This might cause position changes - Clouds should be (as a model) positioned "0, 1024, 0", and Skybox should be positioned "0,0,0".
4. Parent the "Materials" folder to the MaterialService object in Explorer.
5. In the properties window of MaterialService, you will want to set each material up individually. Double-click the empty box next to each enum, and select the applicable MaterialVariant for each (i.e. Brick would go with OldBrick, Plastic would go with OldPlastic).
6. Assuming it has worked, you should notice a significant change to the visual appearance of your game.

## Known issues specific to this pack of materials ##
- Sand is currently based on the current version of the material, instead of the original, and this wasn't noticed until nearer the release - **fix intended to release with v0.2 (will fix)**
- Wood's normal map currently isn't combined with its original normaldetail map - **various issues with this, hoping to release a fix in a future release (will fix, unscheduled)**
- Cobblestone is currently slightly more metallic than the original material and isn't currently using an adjusted version of original specular map, as it was one of the earlier material implementations - **fix intended to release with v0.2 (will fix)**
- Concrete's normal map currently isn't combined with its original normaldetail map - **yet to be attempted, hoping to release a fix in either v0.2 or v0.3 (will fix)**
- DiamondPlate looks slightly too rough and dull - **hoping to release a fix in a future release (will fix, unscheduled)**
- Pebble's normal map currently isn't combined with its original normaldetail map - **yet to be attempted, hoping to release a fix in either v0.2 or v0.3 (will fix)**
