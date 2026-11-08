# Importing the add-on

The two folders are separate Bedrock packs. Keep their folder names and the manifest files at the pack roots.

For an importable package, zip the contents of each pack folder so that `manifest.json` is at the root of the zip, then rename the archives to `Train_Behavior_Pack.mcpack` and `Train_Resource_Pack.mcpack`. Open both files with Minecraft Bedrock and activate both imported packs in the same world.

For local development, copy the folders directly into the matching `development_behavior_packs` and `development_resource_packs` directories under the Bedrock `com.mojang` data folder.
