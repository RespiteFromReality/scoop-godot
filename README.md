# Scoop Godot
A third-party scoop bucket tracking [Godot](https://godotengine.org/) versions
# Install
- Install [scoop](https://scoop.sh/)
- Run `scoop bucket add godot https://github.com/RespiteFromReality/scoop-godot/`
- Run `scoop update`
# Uninstall
- Run `scoop bucket rm godot`
# Usage
- To see what Godot versions are available use `scoop search godot` or look inside the bucket folder, each json is a package.
- To install a package use `scoop install godot/<package name>` (like godot-beta-mono)
# Disclaimers
- Provided as-is, do not make this a core dependency of your workflow or god forbit CI/CD.
- I'm not running GitHub Actions to autoupdate, so updates may be delayed.
