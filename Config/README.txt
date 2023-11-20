2 Config files exist:

EOS and SteamWithCrossplay

When packaging the project for the EPIC release, replace the DefaultEngine.ini with the DefaultEngine_EOS.ini (either delete the DefaultEngine.ini or just replace the text in it)

When packaging the project for the STEAM release, replace the DefaultEngine.ini with the DefaultEngine_SteamWithCrossplay.ini (same as before)

Then test the build (artifacts/server config check since those are in the .ini's)