# BepInEx Installation for Abandoned Archive

## Tested BepInEx Version

**BepInEx Version:** `6.0.0-be.738` (bleeding-edge build)  
**Unity Version:** `2021.3.45f2`  
**Runtime:** Mono (CLR 4.0.30319.42000)  
**Platform:** Windows x64

## Download Links

### Exact version of BepInEx I used for win x64. (#738)
   https://builds.bepinex.dev/projects/bepinex_be/738/BepInEx-Unity.Mono-win-x64-6.0.0-be.738%2Baf0cba7.zip

### Official BepInEx Releases
- **BepInEx Bleeding Edge Releases Page:** https://builds.bepinex.dev/projects/bepinex_be
- **Direct Download:** Look for `BepInEx-Unity.Mono-win-x64-6.0.0-be.738.zip` or the latest bleeding-edge release
- The `be` suffix indicates a bleeding-edge/pre-release version

### Installation Documentation
- **Unity Mono Installation Guide:** https://docs.bepinex.dev/v6.0.0-pre.1/articles/user_guide/installation/unity_mono.html

## Installation Notes

### Manual Installation
If installing manually:

1. **Download the correct version:**
   - Ensure you download the **Mono** version (not IL2CPP)
   - For Unity 2021.3 games
   - Windows x64 platform

2. **Extract to game directory:**
   - Extract all files to `C:\SteamLibrary\steamapps\common\Abandoned Archive\`
   - The `BepInEx` folder should be at the same level as `Abandoned Archive.exe`

3. **First launch:**
   - Run the game once to generate configuration files
   - Check `BepInEx\LogOutput.log` to verify successful installation

## Troubleshooting

### Check Installation
After installation, verify BepInEx is working by:
1. Launching the game (see if the BepInEx console starts up)
2. Checking `BepInEx\LogOutput.log` for startup messages
3. Looking for `[Message:   BepInEx] Chainloader startup complete` in the log

### Common Issues
- **Wrong version:** Ensure you downloaded the Mono version, not IL2CPP
- **Missing files:** Ensure all BepInEx files are extracted to the game root directory

## Mod Installation

After BepInEx is installed, place mod DLLs in plugins, either with the mod folder & dll:
```
BepInEx\plugins\[ModName]\ModName.dll
```

Or just the dll directly in:
```
BepInEx\plugins\ModName.dll
```
