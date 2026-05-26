[update-readmes]   Mode: rewrite — migrating to template structure...
# appimagecraft

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/appimagecraft)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/appimagecraft.git
cd appimagecraft
```

## Usage


appimagecraft requires a simple YAML-based file to lay in the repository root directory. Once the file has been written, you just have to run `appimagecraft` (or `appimagecraft build`) in the repository directory. appimagecraft creates a temporary directory and generates a bunch of shell scripts, all of which are called in the right order from a central script. Then, it runs the build scripts, ideally generates an AppImage and moves that back into your repository directory. Now, you should have an AppImage on hand!

If you want to just generate the scripts, you can run `appimagecraft genscripts -d build/`. This will just generate all the scripts in said directory and exit. You can then inspect the contents. If you want to run the build, just call the `build.sh` script inside that directory. Please beware that the directory will not be cleaned up automatically, and artifacts (such as AppImages) will remain within that directory as well.

For more information about the scripts, see [Contents of the build directory](#contents-of-the-build-directory).

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/appimagecraft`](https://github.com/Interested-Deving-1896/appimagecraft) and mirrored through:

```
Interested-Deving-1896/appimagecraft  ──►  OpenOS-Project-OSP/appimagecraft  ──►  OpenOS-Project-Ecosystem-OOC/appimagecraft
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/appimagecraft/blob/master/LICENSE.txt) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
