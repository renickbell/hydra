# Changelog
## [1.2.15] - 2022-02-09
### Added
- added api and docs as submodules in folder /frontend
- server enpoint for '/api' and '/docs' referring to function documentation
- added instructions for cloning submodules

### Changed
- subfolders for different frontend endpoints in 'frontend'
- removed unused 'backend/app' files
- less unnecessary server logging

## [1.2.14] - 2022-01-25
### Changed
- Editor easier to scroll
- saving screenshot also saves code
- separate keymaps file
- updated hydra-synth

### Fixed
- `show-code=false` in URL correctly hides all elements 
- async no longer added to gallery sketches

## [1.2.14] - 2022-01-09
### Changed
- restructured repo to contain frontend and backend subfolders
- removed extraneous/unused files

## [1.2.13] - 2021-12-19
### Changed
- removed all keymaps based on arrow keys

## [1.2.12] - 2021-12-13
- bundle size optimizations: removed prettier and added js-beautify
- loaded p5js separately

## [1.2.11] - 2021-12-13
### Changed
- switched keymaps: ctrl+left and right arrow uses default editor behavior, ctrl+shift + arrow keys cycle between previous sketches
- removed old forum link

## [1.2.10] - 2021-10-28
### Fixed 
- code with trailing comments now evaluates
- error loggin in on-screen console now shows up

## [1.2.9] - 2021-10-26
### Added 
- Added load script function
- added README examples of loading script

### Changed
- updated prettier formatting

### Changed
- updated screen capture info in readme

## [1.2.8] - 2021-10-26
### Changed
- updated to latest version of hydra synth
- removed extra log statements

## [1.2.7] - 2021-02-28
### Changed
 - Updated p5.js

## [1.2.6] - 2021-02-28
### Changed
 - Saved Mutator updates into URL state
 
## [1.2.5] - 2021-02-13
### Changed
 - Updated Mutator by Jamie Fenton

## [1.2.4] - 2020-04-27
### Fixed
 - Initial example loading
 - pb.setStream()

## [1.2.3] - 2020-04-26
### Added
 - Added new examples

### Changed
 - does not load code to url when found in database

## [1.2.2] - 2020-04-26
### Changed
 - checks whether is ios in order to specify precision value
 - resolution independent of browser zoom level
 - code not repeated at bottom

## [1.2.1] - 2020-04-14
### Added
 - Changelog
 - Run button
 - Code reloaded on url change
 - Code is saved on Ctrl+shift+enter
 - Code flash for Ctrl+shift+enter
