sublhandler-ubuntu
==================

Example snippets to open subl://, txmt:// and sublime:// URLs in Sublime Text on Ubuntu

## Overview

These little custom URL Handlers for subl:// and txmt:// will open links in Sublime Text 3.
It's e.g. useful with the Ruby on Rails gem _better_errors_

## Installation

_Only tested with Sublime Text 3_

1. Copy the files to _/usr/share/applications/_
  1. **sublime-handler-subl.desktop**
  2. **sublime-handler-txmt.desktop**
  3. **sublime-handler-sublime.desktop**
2. Issue _sudo update-desktop-database_
3. Copy **sublime-handler** to _~/bin/_ (make sure it's executable)
4. Try it, have fun!
  1. Not working? Create an issue


## Credits and sources
* http://askubuntu.com/questions/250847/sublime-text-url-handler-for-ubuntu
* https://github.com/charliesome/better_errors/wiki#opening-files-in-sublimetext
