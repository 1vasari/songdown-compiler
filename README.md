# songdown-compiler

This is the compiler component of the Songdown project it implements [this syntax](https://github.com/1vasari/songdown-app/wiki/The-Songdown-Syntax).

[![Code Climate](https://codeclimate.com/github/1vasari/songdown-compiler/badges/gpa.svg)](https://codeclimate.com/github/1vasari/songdown-compiler)
[![Build Status](https://travis-ci.org/1vasari/songdown-compiler.svg)](https://travis-ci.org/1vasari/songdown-compiler)
[![Dependency Status](https://david-dm.org/1vasari/songdown-compiler.svg)](https://david-dm.org/1vasari/songdown-compiler)
[![devDependency Status](https://david-dm.org/1vasari/songdown-compiler/dev-status.svg)](https://david-dm.org/1vasari/songdown-compiler#info=devDependencies)

[![NPM](https://nodei.co/npm/songdown-compiler.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/songdown-compiler/)

# Changes

### 0.7.0 (2015-08-29)
- Changed the verse ending token (again!).

### 0.6.0 (2015-08-29)
- Implemented guitar tab verse type.
- Change the verse ending token to reduce confusion with guitar tab.
- Refactored and tidied up the code.
- Hide verse headers when there's nothing in the verses themselves.
- Fixed verses getting cut across pages when printed out.

### 0.5.0 (2015-08-20)
- Implemented `fontSize` prop that changes the font size of the song.
- Implemented options for hiding chords, comments and GOTOs.

### 0.4.0 (2015-08-07)
- Implemented transposing.

### 0.3.8 (2015-07-23)
- This is starting to drag on...

### 0.3.7 (2015-07-23)
- Now trying Babel.

### 0.3.6 (2015-07-23)
- Improvements to Webpack build.

### 0.3.5 (2015-07-23)
- Use Webpack.

### 0.3.4 (2015-07-20)
- Nope

### 0.3.3 (2015-07-20)
- Things still aren't right. :sob:

### 0.3.2 (2015-07-20)
- Publishing a React component is hard, apparently. :sob:

### 0.3.1 (2015-07-20)
- Some fixes.

### 0.3.0 (2015-07-20)
- Implemented a new compiler using the brilliant React JavaScript library.
- Removed waffle.io from the README as I don't use it anymore.
- Changed the module used to render markdown comment blocks. The old one was marked as insecure.
- Added some basic tests to start getting some coverage.

### 0.2.5 (2015-1-29)
- Updated some dependencies.
- Added a new Badge in the readme.

### 0.2.4 (2015-1-28)
- Started the laborious task of cleaning up compiled CoffeeScript and making it workable.
- Added some more basic unit tests.

### 0.2.3 (2015-1-23)
- Removed a random `console.log` that was left in accidentally.

### 0.2.2 (2015-1-22)
- Compiled the code to JavaScript to integrate better with the `songdown-app` project and other possible uses.
- Added a few unit tests to be able to start testing.

### 0.2.1 (2015-1-14)
- Fixed indentation of code for better consistency.

### 0.2.0 (2015-1-14)
- Fixed up the code so that it's (slightly) usable.

### 0.1.0 (2015-1-14)
- Initial version as pulled from the (exceedingly cluttered) `1vasari/songdown` repository. None of this code will work until things have moved around a little more.

# License

This project is made with love, under the MIT license, by [@1vasari](https://twitter.com/1vasari). :heart:
