# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.6.15](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.14...v0.6.15) (2021-08-05)


### Bug Fixes

* **build:** another --relink-eln-files flag fix ([3622df5](https://github.com/jimeh/build-emacs-for-macos/commit/3622df550c72fc9da70235005239b278b5822cf6))

### [0.6.14](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.13...v0.6.14) (2021-08-05)


### Bug Fixes

* **build:** silly typo ([1fc7faa](https://github.com/jimeh/build-emacs-for-macos/commit/1fc7faac1f040466fa4474a873d2290273780ee2))

### [0.6.13](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.12...v0.6.13) (2021-08-04)


### Bug Fixes

* **native_comp:** add option to enable/disable relinking *.eln files ([ac943c4](https://github.com/jimeh/build-emacs-for-macos/commit/ac943c430c58e0761ac44e8d25d4d55a461d01a2))

### [0.6.12](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.11...v0.6.12) (2021-08-02)


### Bug Fixes

* **sign:** resolve signing issue caused by re-linking shared lib in *.eln files ([e6b1e5a](https://github.com/jimeh/build-emacs-for-macos/commit/e6b1e5a554fd0f776bd01c17cfb1ebbbdf7a7831))

### [0.6.11](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.10...v0.6.11) (2021-07-17)


### Bug Fixes

* **native-comp:** fix re-linking and signing issue with *.eln files ([b03343f](https://github.com/jimeh/build-emacs-for-macos/commit/b03343f506aa3ceabdfa03f8a2916b2db4873f3f))

### [0.6.10](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.9...v0.6.10) (2021-07-16)


### Bug Fixes

* **native-comp:** *.eln files were not being found during shared lib embedding ([9d32509](https://github.com/jimeh/build-emacs-for-macos/commit/9d32509c615076618957cc47c82f6e9d8f972fe7))

### [0.6.9](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.8...v0.6.9) (2021-07-04)


### Features

* **release:** add bulk edit command to quickly change multiple GitHub releases ([cb63806](https://github.com/jimeh/build-emacs-for-macos/commit/cb638062625d9bc3eee12515067fb09e05a08414))


### Bug Fixes

* **plan:** correctly parse --test-release-type flag ([fd0ec4d](https://github.com/jimeh/build-emacs-for-macos/commit/fd0ec4d772dd3da93afc234fb3024220b2099c88))

### [0.6.8](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.7...v0.6.8) (2021-07-02)


### Features

* **builds:** add support for stable builds ([f4d6e3a](https://github.com/jimeh/build-emacs-for-macos/commit/f4d6e3a56d2c15b0c86af18e8d16bebbeb92a8ab))

### [0.6.7](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.6...v0.6.7) (2021-07-02)


### Features

* **bundle:** move bundled shared libraries to Contents/Frameworks ([5c722e3](https://github.com/jimeh/build-emacs-for-macos/commit/5c722e36c571aa7bf558b7f210c011f12d8d8a1c))

### [0.6.6](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.5...v0.6.6) (2021-07-01)

### [0.6.5](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.4...v0.6.5) (2021-07-01)


### Bug Fixes

* **native_comp:** improve handling of *.eln files in .app bundle ([9019e73](https://github.com/jimeh/build-emacs-for-macos/commit/9019e73d606f0379f988f46d6008770f8f3f7a51))

### [0.6.4](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.3...v0.6.4) (2021-06-30)

### [0.6.3](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.2...v0.6.3) (2021-06-29)


### Bug Fixes

* **patches:** correctly set ref when loading a build plan YAML ([99aa76b](https://github.com/jimeh/build-emacs-for-macos/commit/99aa76b3985195c310a20bafa19a8c7a4c8558fd))

### [0.6.2](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.1...v0.6.2) (2021-06-29)


### Bug Fixes

* **native_comp:** patch Emacs.pdmp for customized native-lisp paths ([23b8236](https://github.com/jimeh/build-emacs-for-macos/commit/23b8236e0a66fb09810e8422bedf02f7192a53e4))

### [0.6.1](https://github.com/jimeh/build-emacs-for-macos/compare/v0.6.0...v0.6.1) (2021-06-28)


### Bug Fixes

* **cask:** add missing --force flag to cask update command ([6af597b](https://github.com/jimeh/build-emacs-for-macos/commit/6af597b4271341f9796c3d9c356de9918e0f6f85))

## [0.6.0](https://github.com/jimeh/build-emacs-for-macos/compare/v0.5.2...v0.6.0) (2021-06-28)


### Features

* **cask:** add cask update command to manage cask formula ([adbcfc6](https://github.com/jimeh/build-emacs-for-macos/commit/adbcfc6fc433fcc99b10dc5ccb51ba458333fa9c))

### [0.5.2](https://github.com/jimeh/build-emacs-for-macos/compare/v0.5.1...v0.5.2) (2021-06-27)


### Bug Fixes

* **native_comp:** rename native-lisp folder paths to appease Apple's codesign ([eeca7b7](https://github.com/jimeh/build-emacs-for-macos/commit/eeca7b798de236a3ffc1ab04b0f7735a37ce5af4))

### [0.5.1](https://github.com/jimeh/build-emacs-for-macos/compare/v0.5.0...v0.5.1) (2021-06-27)


### Bug Fixes

* **native_comp:** symlink creation was missing a conditional check ([ca73ab7](https://github.com/jimeh/build-emacs-for-macos/commit/ca73ab7202877acefd97289f3d28e7c025e36b9d))

## [0.5.0](https://github.com/jimeh/build-emacs-for-macos/compare/v0.4.17...v0.5.0) (2021-06-21)


### ⚠ BREAKING CHANGES

* **release:** Add v prefix to git version tags
* **build:** New archive naming convention, and folder structure within archive.

### Features

* **build:** add ability to output as directory and/or archive ([3e1eb01](https://github.com/jimeh/build-emacs-for-macos/commit/3e1eb01e248ebbc314b8b9f50bbc371ac8df666b))
* **cli:** add basis for new "emacs-builder" CLI tool written in Go ([8d87c01](https://github.com/jimeh/build-emacs-for-macos/commit/8d87c01db79201182fbcd1a210b1b19df9209aeb))
* **notarize:** add notarize command to notarize and staple *.dmg files ([72d0254](https://github.com/jimeh/build-emacs-for-macos/commit/72d0254772bf7d0937b41634e9a4bfcf87f60fb6))
* **package:** add package command to create a styled *.dmg for Emacs.app ([87ecfbc](https://github.com/jimeh/build-emacs-for-macos/commit/87ecfbcec05b46d7a30202269474612834b648f3))
* **plan:** add plan command to create build plans ([1ffd735](https://github.com/jimeh/build-emacs-for-macos/commit/1ffd735c23e375479ea6bb2c771553ce4cac902b))
* **release:** add release check command ([276a9da](https://github.com/jimeh/build-emacs-for-macos/commit/276a9da5eed618322e09fba11a486ae0d9925fdd))
* **release:** add release publish command ([72ca9ce](https://github.com/jimeh/build-emacs-for-macos/commit/72ca9ce2b64505a8bbc50b3139c0f84fb24813fd))
* **sign:** add sign command to sign Emacs.app bundles with codesign ([698756a](https://github.com/jimeh/build-emacs-for-macos/commit/698756ac5597d3dc7b69f28bc209093fc8c11f30))


* **release:** add v prefix to git version tags ([b719437](https://github.com/jimeh/build-emacs-for-macos/commit/b719437bee9acf28d5d352eb44cbf4d3a17107d7))

### [0.4.17](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.16...0.4.17) (2021-06-20)


### Bug Fixes

* **download:** don't use GitHub API to get tarball URL ([707bc9e](https://github.com/jimeh/build-emacs-for-macos/commit/707bc9e0d13246b7cfb8d27da859a101d4a3c166))

### [0.4.16](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.15...0.4.16) (2021-06-07)


### Bug Fixes

* **compiling:** improve portability of builds ([ca2d4c3](https://github.com/jimeh/build-emacs-for-macos/commit/ca2d4c38f69c434c77c266594104bfbf34ad5221))
* **native_comp:** crash on launch when gcc homebrew package was not installed ([bd81870](https://github.com/jimeh/build-emacs-for-macos/commit/bd8187065928b9f79de8b14222c98f8dc34bfe5f))

### [0.4.15](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.14...0.4.15) (2021-05-31)


### Features

* **github:** perform authenticated GitHub API requests when GITHUB_TOKEN env var is set ([deda28e](https://github.com/jimeh/build-emacs-for-macos/commit/deda28e5aded2817bcc7956f377378576372816f))

### [0.4.14](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.13...0.4.14) (2021-05-22)


### Features

* **cli:** add "emacs" CLI launcher script to Emacs.app/Conents/MacOS/bin ([8237aa9](https://github.com/jimeh/build-emacs-for-macos/commit/8237aa9272ce1d13a412b2495cbaa90df38d928b)), closes [#41](https://github.com/jimeh/build-emacs-for-macos/issues/41)

### [0.4.13](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.12...0.4.13) (2021-05-22)


### Bug Fixes

* **codesign:** prevent "bundle format unrecognized" error from codesign ([7259111](https://github.com/jimeh/build-emacs-for-macos/commit/7259111478ecb838dea9c8f50ea39eafdf47ed5a))
* **embed:** avoid potential error caused by trying to set duplicate rpath ([bb45cda](https://github.com/jimeh/build-emacs-for-macos/commit/bb45cda0231e99618571dc835348cf5c3345e277))

### [0.4.12](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.11...0.4.12) (2021-05-17)


### Bug Fixes

* **shared-libraries:** stop aggressive dylib re-linking ([0a22d83](https://github.com/jimeh/build-emacs-for-macos/commit/0a22d8393c53305354c4c6d8e784e7d59caa039a)), closes [#12](https://github.com/jimeh/build-emacs-for-macos/issues/12)
* **svg:** enable SVG by default via librsvg ([bf7c4d5](https://github.com/jimeh/build-emacs-for-macos/commit/bf7c4d5debf32980dbbabc1ea99b58b266390011))

### [0.4.11](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.10...0.4.11) (2021-05-08)


### Features

* **builds:** update build script for new plan.yml format ([1df39fa](https://github.com/jimeh/build-emacs-for-macos/commit/1df39fafe62ada385aa1d92e6b7f591c16c0a80c))
* **release:** initial attempt at providing automatic builds ([6328921](https://github.com/jimeh/build-emacs-for-macos/commit/63289216d70e496d664a7e3078dea5a82eb8f65d))


### Bug Fixes

* **release:** attempt to fix issue with talking to GitHub API ([272a300](https://github.com/jimeh/build-emacs-for-macos/commit/272a3000a1f96d8f131e684736127b923513a205))

### [0.4.10](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.9...0.4.10) (2021-04-25)


### Bug Fixes

* **cli:** correctly default to master branch if no git ref is given ([844df73](https://github.com/jimeh/build-emacs-for-macos/commit/844df73c8fa8440e657f7900ec89cdedb7c4c312))

### [0.4.9](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.8...0.4.9) (2021-04-08)


### Bug Fixes

* **cli:** default to "master" if no git ref is given ([e19a6a7](https://github.com/jimeh/build-emacs-for-macos/commit/e19a6a7bc24379292ee06ae4c805b8c5365f2d97)), closes [#35](https://github.com/jimeh/build-emacs-for-macos/issues/35)
* **native_comp:** skip symlink creation for recent builds which do not need symlinks ([1000999](https://github.com/jimeh/build-emacs-for-macos/commit/1000999eb2673dc207a390ff3f902b9987b99173))

### [0.4.8](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.7...0.4.8) (2021-02-27)


### Bug Fixes

* **native_comp:** add support for new --with-native-compilation flag ([581594d](https://github.com/jimeh/build-emacs-for-macos/commit/581594da3cfbf1dd2fa28e91710b767e21ff75d2))

### [0.4.7](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.6...0.4.7) (2021-02-21)


### Bug Fixes

* **native_comp:** add libgccjit include dir during build stage ([e25ceaa](https://github.com/jimeh/build-emacs-for-macos/commit/e25ceaa7e25b0e1b9947401597845b5ba43e6cd1)), closes [#20](https://github.com/jimeh/build-emacs-for-macos/issues/20)

### [0.4.6](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.5...0.4.6) (2021-02-15)


### Bug Fixes

* **native_comp:** improve env setup patch fixing potential issues ([dca023d](https://github.com/jimeh/build-emacs-for-macos/commit/dca023daecd8704f197cbc391380aa194bc47d62))

### [0.4.5](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.4...0.4.5) (2021-01-06)


### Bug Fixes

* **cli:** remove defunct --[no-]native-comp-macos-fixes option ([ab55f54](https://github.com/jimeh/build-emacs-for-macos/commit/ab55f5421c81dc629e487bf4b8bb402657cb1bc4))

### [0.4.4](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.3...0.4.4) (2021-01-02)


### Bug Fixes

* **deps:** add autoconf to Brewfile ([a47d3e0](https://github.com/jimeh/build-emacs-for-macos/commit/a47d3e0c6a8ea8161a3bad0eafdac2401cf53129))

### [0.4.3](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.2...0.4.3) (2020-12-28)


### Bug Fixes

* **big-sur:** add Xcode CLI tools lib directory to runtime LIBRARY_PATH ([946856e](https://github.com/jimeh/build-emacs-for-macos/commit/946856e9c242d4a6fb5f839d8cae0acfafecdfc6))
* **big-sur:** added support for building on Big Sur ([2247158](https://github.com/jimeh/build-emacs-for-macos/commit/2247158051d0f59933569b6974b2b5269f13c79e))

### [0.4.2](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.1...0.4.2) (2020-12-09)


### Bug Fixes

* **cli:** avoid error if --git-sha is used without a branch/tag/sha argument ([884f160](https://github.com/jimeh/build-emacs-for-macos/commit/884f1607f6707ca187b1abfb0ce562757d872230)), closes [#21](https://github.com/jimeh/build-emacs-for-macos/issues/21)
* **native_comp:** update env setup patch for recent changes to comp.el ([c7daa13](https://github.com/jimeh/build-emacs-for-macos/commit/c7daa1350bd69df172ce6484c54189d2cee8d97e))

### [0.4.1](https://github.com/jimeh/build-emacs-for-macos/compare/0.4.0...0.4.1) (2020-10-29)


### Features

* **native_comp:** remove patch based on feature/native-comp-macos-fixes branch ([70bf6b0](https://github.com/jimeh/build-emacs-for-macos/commit/70bf6b05d584976632b2fd2947c0bf692f5b6421))

## [0.4.0](https://github.com/jimeh/build-emacs-for-macos/compare/0.3.0...0.4.0) (2020-10-04)


### ⚠ BREAKING CHANGES

* **native_comp:** Standard Homewbrew `gcc` and `libgccjit` formula are now required for native-comp, instead of the custom patched gcc formula.

### Features

* **native_comp:** use new libgccjit Homebrew formula ([d8bbcb7](https://github.com/jimeh/build-emacs-for-macos/commit/d8bbcb72b33f6bde8678c9d37548217ffdf3d641))

## [0.3.0](https://github.com/jimeh/build-emacs-for-macos/compare/0.2.0...0.3.0) (2020-09-22)


### ⚠ BREAKING CHANGES

* **native_comp:** `--[no-]launcher` option is deprecated, as launcher script is no longer used.

### Features

* **native_comp:** use elisp patch instead of launcher script to set LIBRARY_PATH ([111cb64](https://github.com/jimeh/build-emacs-for-macos/commit/111cb6499368d14853a5927d38a43fc5e2f759f4)), closes [#14](https://github.com/jimeh/build-emacs-for-macos/issues/14)

## [0.2.0](https://github.com/jimeh/build-emacs-for-macos/compare/0.1.1...0.2.0) (2020-09-20)


### ⚠ BREAKING CHANGES

* **native_comp:** Deprecate `--[no-]native-fast-boot` option in favor of `--[no-]native-full-aot`

### Features

* **native_comp:** add support for NATIVE_FULL_AOT, replacing NATIVE_FAST_BOOT ([0ab94da](https://github.com/jimeh/build-emacs-for-macos/commit/0ab94da15309b04978982369bdfa17e03e9b6329))

### [0.1.1](https://github.com/jimeh/build-emacs-for-macos/compare/0.1.0...0.1.1) (2020-09-19)


### Bug Fixes

* **internal:** improve macOS version detection ([c89d0a0](https://github.com/jimeh/build-emacs-for-macos/commit/c89d0a0b73dfc82d918c326d89b141f8a2fc4de4)), closes [#13](https://github.com/jimeh/build-emacs-for-macos/issues/13)

## 0.1.0 (2020-09-05)


### Features

* **deps:** add mailutils to Brewfile so Emacs can use GNU Mailutils ([d944a64](https://github.com/jimeh/build-emacs-for-macos/commit/d944a644847db564e56679b1c75c2550c8261b62))
* **native_comp:** add fix based on feature/native-comp-macos-fixes branch ([da2fcb0](https://github.com/jimeh/build-emacs-for-macos/commit/da2fcb0440a074a12c4fc6b1572cb55d8fb3cf9a))
* **native_comp:** Add support for --with-nativecomp ([fe460a8](https://github.com/jimeh/build-emacs-for-macos/commit/fe460a824ee57b602d29854167feab1b9f032aef))
* **native_comp:** embedd gcc/libgccjit into Emacs.app ([83289ac](https://github.com/jimeh/build-emacs-for-macos/commit/83289acd33b54a0d332fe92e2ad4ef7c1c633b72)), closes [#5](https://github.com/jimeh/build-emacs-for-macos/issues/5) [#7](https://github.com/jimeh/build-emacs-for-macos/issues/7)
* **native_comp:** support renaming of eln-cache director to native-lisp ([9d26435](https://github.com/jimeh/build-emacs-for-macos/commit/9d264357df61cf57a153947d2c22e28c27cba2d5))
* **patches:** add support for optional no-titlebar and no-refocus-frame patches ([583f22a](https://github.com/jimeh/build-emacs-for-macos/commit/583f22a360a08bf236ea0e0562e6fd1ddda3b933))
* **ref:** allow overriding git SHA ([eebda4d](https://github.com/jimeh/build-emacs-for-macos/commit/eebda4db42a700971b2083b3d420b99177f68b51))
* **release:** support building from release git tags ([c0e89b1](https://github.com/jimeh/build-emacs-for-macos/commit/c0e89b13648f9336aa46b2f088dcd439cb4028b7))


### Bug Fixes

* **deps:** Add missing dependencies to Brewfile ([39ea3eb](https://github.com/jimeh/build-emacs-for-macos/commit/39ea3eb5e8fed28f09962fcb8594ef85492b2f43))
* **native_comp:** ensure builds work after recent changes to eln cache locations ([b46e5aa](https://github.com/jimeh/build-emacs-for-macos/commit/b46e5aa7cba3c9496d2126fa9827275eaab720af)), closes [/akrl.sdf.org/gccemacs.html#org4b11ea1](https://github.com/jimeh//akrl.sdf.org/gccemacs.html/issues/org4b11ea1)
* **native_comp:** Improve ./install-patched-gcc helper ([a8d4db2](https://github.com/jimeh/build-emacs-for-macos/commit/a8d4db284cc216afa6793173f17e3811305eff05))
* **patches:** Fix patch download URL, add additional patches ([66acc01](https://github.com/jimeh/build-emacs-for-macos/commit/66acc01c0ca5d2f3c257f7df36082351a35f4273))
* **patches:** Only apply patches as part of archive extraction ([c4768f4](https://github.com/jimeh/build-emacs-for-macos/commit/c4768f4c3aed02a758863131abae5f07e8e4cf55))
* **requirements:** make script compatible with Ruby 2.3.0 and later ([8e459ce](https://github.com/jimeh/build-emacs-for-macos/commit/8e459ce00d8e5e3032ced260d8fbbc9b1dbc2c7a))
* **svg:** disable rsvg by default ([d30b45f](https://github.com/jimeh/build-emacs-for-macos/commit/d30b45fb2e507af98c3a958d159be3402a7a7bd1))
* **xwidgets:** Add support for emacs-27 specific xwidgets patch ([7767df0](https://github.com/jimeh/build-emacs-for-macos/commit/7767df0b660714c502d953b7bb22f5f3c2e3e3df))
* **xwidgets:** Use patch from emacs-plus Homebrew formula ([fb93beb](https://github.com/jimeh/build-emacs-for-macos/commit/fb93beb22c8b8dd0b46170c5c0b58159f25d6c1d))
