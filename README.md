# KiCAD Plugin Repository

This repository provides a collection of KiCAD plugins through the Plugin and Content Manager (PCM).

## Installation

To install plugins from this repository in KiCAD:

1. Open KiCAD
2. Go to Plugin and Content Manager (PCM)
3. Click on "Add Repository"
4. Enter the repository URL: `https://raw.githubusercontent.com/harry10086/kicad-repository/main/repository.json`
5. Click OK

## Available Plugins

- **ViaStitching**: Automatic via stitching generation for PCB zones  (中文版)
- **Interactive HTML BOM**: Interactive BOM generator with multi-CAD support (中文版)
- **KiCAD JLCPCB Tools (SZLCSC Edition)**: JLCPCB/立创商城 integration with online API
- **JLCImport**: Component importer from JLCPCB/立创商城
- **Fanout Tool**: Automated escape routing for dense IC packages (中文版)

## Adding New Plugins

To add new plugins to this repository:

1. Fork this repository
2. Add the plugin information to `packages.json`
3. Update the SHA256 hash and timestamp in `repository.json`
4. Create a pull request

Each plugin entry in `packages.json` should follow the KiCAD PCM schema.
