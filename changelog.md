# Changelog

## Version 1.0
### Initial release
- First public version of the X Server Launcher Script
- Automatic detection of AMD, Intel, and NVIDIA video cards
- Smart recommendation of the best `startx` option based on detected GPU
- Support for 10 different startup configurations (including `-ignoreABI` and various driver configs)
- Interactive selection via numbered menu or **fzf** (if available)
- GPU detection using `lspci`
- Recommended option highlighting
- Improved input validation to prevent errors from invalid user input
- Added `set -euo pipefail` for better script reliability
- Cleaned up code style and added proper GPL-3.0 license header

---

## Version 0.1 (Internal)
- Initial development version
