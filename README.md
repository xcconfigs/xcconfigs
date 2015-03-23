This project intends to aggregate common or universal Xcode configuration settings, keeping them in hierarchial Xcode configuration files for easy modification and reuse.
## Installation Options

* git submodule
* add to Cartfile

## Usage in a new Project

1. Create a `Configuration` group in your project.
2. Right click on `Configuation group`, and select `Add Files`
3. Navigate to `xcconfigs` (Carthage/Checkouts/xcconfigs if using Carthage)
4. Multiselect `Base`, `iOS`, `Mac OS X` as needed
5. Uncheck `Destination: [ ] Copy items if needed`
6. Select `Added folders: (*) Create groups`
7. Uncheck `Add to targets: [ ] TargetName` so the .xcconfig files won't be copied into target
8. For each `Project->Targets->Build Settings` Select All and Delete
9. Go to `Project->Info->Configurations` and set Debug and Release and Targets to appropriate .xcconfig files

## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

In jurisdictions that recognize copyright laws, the author or authors of this software dedicate any and all copyright interest in the software to the public domain. We make this dedication for the benefit of the public at large and to the detriment of our heirs and successors. We intend this dedication to be an overt act of relinquishment in perpetuity of all present and future rights to this software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to [unlicense.org](http://unlicense.org).
