# Angular Electron starter
A basic angular5 application (with Angular Material) combined with Electron to build desktop app with Angular.

## Scripts

All default Angular CLI scripts remain.  Addtional scripts are:

0. `npm run test:ci`: only runs tests once.
0. `npm run build-electron`: builds the angular app with `--base-href .`
0. `npm run electron`: builds the angular app and then runs `electron .` to start the app
0. `npm run package`: runs tests, builds app, packages the app for default target (the host platform)
0. `npm run package:win32`: runs tests, builds app, packages the app for windows.  (note: must have wine 1.6+ installed for windows packages on linux host machines.)
0. `npm run package:mac`: runs tests, builds app, packages the app for mac. (note: homebrew is necessary for packaging windows on a mac)
