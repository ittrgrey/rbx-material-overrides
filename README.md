# ittrgrey's Roblox Material Overrides

**DISCLAIMER: MaterialService is currently a Roblox beta feature that needs to be enabled in Roblox Studio. Do not publish to production games yet, as any changes will not show in-game.**

In this repo, you will find a number of overrides created to be used in the MaterialService feature in Roblox Studio.

Each override "package" will contain specific setup instructions - many are designed to restore fidelity and style that Roblox has either removed or downgraded over the years. 

Texture files are not currently included however can be downloaded using Roblox's asset API, should you wish to modify them or create your own: https://assetdelivery.roblox.com/v1/asset?id=ID

All suggestions for this are welcomed however work is currently being prioritised on the 2009-13 and 2013-17 ROBLOX Built-In overrides. 

Please open an issue if something doesn't work as intended. Do not re-report known bugs, which are in two lists below.

## General Bugs (mostly outside of our control):
- Black skybox usage with fake sky part used as hacky workaround to allow usage of metalness functionality without heavy fresnel effect. Cannot be fixed unless Roblox allows more granular control over lighting functionality.
- Some materials might look weird on lower graphics settings due to Roblox's vertex shader implementation, however this should not be visual or game-breaking.
- You may need to reload places at times to see specularity changes on Humanoids/SpecialMeshes. Cannot be fixed, Roblox issue.
- We cannot update your games for you - you will need to install any upgrades that may be released here manually.
- These may look odd/unusual in Voxel, ShadowMap and Future lighting modes. These packs are, for the most part, designed using Compatibility lighting to try and, where possible, replicate a look more akin to Legacy. We are not responsible for any bugs that occur specific to these lighting modes.
- Some materials may look **slightly** duller than the versions we're trying to recreate. Please note - it is not possible to recreate all of the configurations absolutely perfectly (due to the fact Roblox uses a different rendering system now than between 2009 to 2020), however all of the configurations should hopefully look much better in your games than the default configuration, depending on what you are making.

## Changelog (25/12/21):
- Released 2013-17 ROBLOX Built-Ins material pack (v0.1).
