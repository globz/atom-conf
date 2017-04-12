**0.8.0 - 10.01.2016**
- Added new shortcut: Escape closes panel
- Updated Google Closure Compiler

**0.7.5 - 17.06.2016**
- Bugfix: Success notification message was not properly formatted ([issue #27](https://github.com/armin-pfaeffle/atom-minify/issues/27))

**0.7.4 - 31.05.2016**
- Bugfix: Minification was executed although no editor was active ([issue #25](https://github.com/armin-pfaeffle/atom-minify/issues/25))

**0.7.3 - 26.04.2016**
- Bugfix: Wrapper CSSO by `allowUnsafeNewFunction` so it works... (CSP restrictions, EvalError, unsafe-eval)

**0.7.2 - 26.04.2016**
- Bugfix: UglifyJS2 option `source_map` does not work ([issue #24](https://github.com/armin-pfaeffle/atom-minify/issues/24))

**0.7.0 - 16.12.2015**
- Added new parameter: minifyOnSave / minOnSave
- Improved minification workflow
- Improved performance of parsing first line parameter
- Removed unnecessary options `outputPath`, use filename pattern options/parameters
- Bugfix: Internal options representation missed an option
- Code refactoring & minor improvements

**0.6.2 - 13.11.2015**
- Fixed missing dependency in package.json

**0.6.1 - 13.11.2015**
- Bugfix: Fixed CSP restrictions (EvalError, unsafe-eval) with latest uglify-js version, [issue #17](https://github.com/armin-pfaeffle/atom-minify/issues/17)

**0.6.0 - 04.11.2015**
- Added new feature: options for minifiers
- Improved panel notifications
- Improved inline parameter parsing
- Improved shortcuts
- Updated Google Closure Compiler
- Bugfix: Quoted parameters could lead to incorrect behaviour
- Bugfix: Warning of too less buffer size was never visible to user

**0.5.0 - 27.10.2015**
- Optimized parameter parsing
- Improved shortcuts
- Improved notification panel
- Improved main menu entry
- Improved notifications
- Bugfix: "Minify" item in Tree View context menu was not always visible on file items
- Bugfix: "Minify" item in Tree View context menu was not working correctly
- Bugfix: Multiple minifcation were possible
- Bugfix: Opening file by clicking on panel notification could fail
- Minor improvements and bugfixes

**0.4.2 - 17.09.2015**
- Buxfix: Incorrect file existence check in delete file method

**0.4.1 - 01.09.2015**
- Fixed documentation

**0.4.0 - 01.09.2015**
- New option: Advanced → Java path for defining an absolute path to a special Java installation
- Minor improvements

**0.3.1 - 25.08.2015**
- Bugfix: Recursive creation of non-existent output directory failed on Darwin and Linux, see [issue #11](https://github.com/armin-pfaeffle/atom-minify/issues/11)

**0.3.0 - 22.08.2015**
- General: Output path is automatically created when not existent
- General: Reordering options in settings view
- General: Minifiyng a unsaved file leads to a save dialog
- New feature: Added inline parameters in a first-line-comment to override global settings
- New feature: Detection of already minified file
- New feature: 'Minify' item in Tree View context menu
- New Option: Ask for overwriting already existent minified files
- New Option: Ask for minification of already minified files
- New Option: Show Minify-item in Tree View context menu
- New Option: General output path
- Improved panel: Better clickable lines for opening files
- Improved panel: When trying opening file by clicking on filename and it does not exist, panel shows an corresponding information and does not open an empty file
- Improved menu: Better menu usability and fixed visual binding problem
- Bugfix: Added try-catch-block when deleting temporary files, so no `Uncaught Error` message occurs, see [issue #10](https://github.com/armin-pfaeffle/atom-minify/issues/10)
- Bugfix: panel was still visible although nothing was minified

**0.2.2 - 27.07.2015**
- Fixed link in documentation

**0.2.1 - 24.07.2015**
- Improved and fixed panel notification

**0.2.0 - 12.07.2015**
- Complete rewrite of package, not depending on node-minify any more
- Improved output filename generation
- Minor improvements

**0.1.7 - 01.07.2015**
- Bugfix: CSS parameters ignored ([pull request](https://github.com/armin-pfaeffle/atom-minify/pull/3) by [William Wells](https://github.com/whanwells))
- Removed unused code

**0.1.5 / 0.1.6 - 27.05.2015**
- Updated CHANGELOG and README

**0.1.4 - 27.05.2015**
- Updated required engine version to <=0.185.0, <2.0.0

**0.1.3 - 27.05.2015**
- Bugfix: Using deprecrated API, so package does not work with API 1.0 (issue [atom/atom#6867](https://github.com/atom/atom/issues/6867))

**0.1.2 - 18.05.2015**
- Bugfix: Missing require() leads to a call of an undefined variable

**0.1.1 - 08.05.2015**
- Removed console outputs

**0.1.0 - 08.05.2015**
- Initial version
