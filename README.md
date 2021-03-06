# Chromegray

A Chrome DevTools theme based on @kkga's Sublime Text theme, Spacegray.


# Contributing

Chromegray is built on LESS. Grunt is used to listen for changes to LESS files and generates CSS. This means [Node](http://nodejs.org/) is required.


## Getting Started

1. Clone this repo: `git clone https://github.com/karelvuong/devtools-chromegray--dark.git`.
2. Install dependencies: `npm install`.
3. To use an existing theme: `grunt`. (If you're going to work on your own theme: `grunt watch` to listen for changes).
4. `Chrome > Preferences... > Extensions > DevTools Theme: Zero Dark Matrix = Enabled` (also enable `Allow incognito` below if you wish).
5. chrome://flags (make sure `Enable Developer Tools experiments` is enabled).
6. In Chome Dev Tools > Settings (cog icon or `Shift+?`) > Experiments > Allow custom UI themes.
7. Sometimes it's required to close and reopen the dev tools.


## Contributing to Template Source

All template files are located in the `/less` directory. Files beginning with an `_` indicate template partials. They are imported via `build.less`. Any addition/removal of template partials should be reflected in the build file.
