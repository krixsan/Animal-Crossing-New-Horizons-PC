# Changelog

All notable changes to **Animal Crossing: New Horizons PC** are documented in this file.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v1.0.0] - 2026-11-20

### Added
- **Minimalist Hero GUI Launcher (`Animal Crossing Launcher.exe`):** Opens directly on full-bleed cozy island artwork with clean **Play** and **Settings** controls (supports custom local `cover.png` / `hero.png` override next to the executable or inside the build folder).
- **1-Click Direct Launcher (`Animal Crossing New Horizons (Direct).exe`):** Native WinMain executable that launches the active build directly without command prompt pop-ups.
- **Standalone Windows x64 Runtime Player (`acnh.exe`, folder mode):** Vulkan 1.3+ renderer with SDL3 input/audio, bundled `SDL3.dll`, AMD FidelityFX (`FSR 1 / FSR 3.1 / RCAS`), NVIDIA DLSS/DLAA, and Visual C++ CRT DLLs.
- **Display, Sharpening & Ultrawide Improvements:** Configurable internal rendering resolution, FSR RCAS sharpness slider, 16x anisotropic filtering, FXAA/SSAA, plus aspect clamping under `auto` so narrower windows cleanly letterbox instead of cropping horizontal FOV or displacing cutscene bars.
- **Smooth Frame Pacing & Frame Generation:** Dedicated Vulkan presenter thread offload with DXGI VBlank pacing for rock-solid 30 FPS console timing, native 60 FPS SpeedFix support, and optional AMD FSR 3 Frame Generation.
- **Integrated Save, Mod & Add-On Management:** Multi-island save profile switcher/importer/exporter, RomFS LayeredFS mod manager, add-on content viewer, desktop shortcut creation, `F1` / `Plus + Minus` in-game settings overlay, and `F12` PNG screenshots.
- **RecompLauncher Manifest (`recomplauncher.json`):** Added automated configuration and launch schema for RecompLauncher.
