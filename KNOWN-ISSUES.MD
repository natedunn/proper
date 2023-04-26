# Known Issues

Listed below are known issues that are either blocked, or very difficult to address.

- **Mac App Store apps will not install**. This can occur if the applications in manifest were not previously _manually_ installed/purchased. Unfortunately this is due to [continued API restrictions](https://github.com/mas-cli/mas#%EF%B8%8F-known-issues). This is blocking and cannot be fixed by Proper.
- **Script breaks if there is an unrelated shell error.** There may always be an unrelated shell error that will break the script as it is running. If it is due to Proper, we'll do our best to patch, silence, or provide better context on the error.
