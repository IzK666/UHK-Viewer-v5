## Changelog

### v0.1
- Ability to convert old json files (version 4) to the newer.
- The old macros are converted to the new format compatible with smart macros.
- Created $onInit macro to initialize the macro engine.

### v0.5
- Implemented many of the old UHK-Viewer functions.
- Many old macro options aren't available. Only view, rename and delete.

### v0.6
- Added creation and removal of additional layers

### v0.65
- Bug: Format convertion: Macros on keymap assignements wheren't updated after macro $onInit is added, making all key assignments to call for the wrong macro
- When a layer is removed, macro calls for that specific layer are commented. It doesn't apply to holdLayer (for example), as it doesn't specify the keymap.

### v0.7
- Bug fixes

### v0.71
- Fixed bug. Odd/undesired behaviour when a layer side was copy-pasted.
