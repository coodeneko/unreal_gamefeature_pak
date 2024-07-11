1. Please copy in an Engine or connect it to whatever engine you want to test with
2. Copy the files in ProjectLauncherConfigs to Engine\Programs\UnrealFrontend\Profiles or create your own profiles
3. Disable the GFPak Plugin and build the base
4. Enable the GFPak Plugin and build the dlc

Notice that the base pak files includes upluigin files for the enabled plugin at the time but the dlc pak file does not include the new uplugin files

Tried it with also GPPak and BasePlugin2 with same results.
