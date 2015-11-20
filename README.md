# IOS Icon version drawing

Script to draw version number on the application icon.

## Installation

1. Install 3rd parties:

brew install imagemagick
brew install ghostscript

2. Add Run Script to Build phases and paste content of Versioning.sh

Caption on the icon is set as "${version} ($build_num)\n${branch}\n${commit}"

## Thanks to

http://habrahabr.ru/post/262667/
