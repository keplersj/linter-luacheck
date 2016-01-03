# linter-luacheck

[![Build Status](https://travis-ci.org/AtomLinter/linter-luacheck.svg?branch=master)](https://travis-ci.org/AtomLinter/linter-luacheck)
[![Build status](https://ci.appveyor.com/api/projects/status/uk8gd88k1af3ga5a/branch/master?svg=true)](https://ci.appveyor.com/project/xpol/linter-luacheck/branch/master)
[![Circle CI](https://circleci.com/gh/AtomLinter/linter-luacheck.svg?style=svg)](https://circleci.com/gh/AtomLinter/linter-luacheck)

This package will lint your opened Lua files in Atom, using [luacheck](https://github.com/mpeterv/luacheck).

## Installation

* Install [luacheck](https://github.com/mpeterv/luacheck).
* `$ apm install linter` (if you don't have [AtomLinter/Linter](https://github.com/AtomLinter/Linter) installed).
* `$ apm install linter-luacheck`

## Configuration

Atom -> Preferences... -> Packages -> linter-luacheck -> Settings:

* **Executable** Path to your luacheck executable.
* **Globals** Add more globals names to standard ones, separated by comma, eg `jit, bit`.
* **Ignore** Ignore warnings related to these variables names, separated by comma, eg `self, myvar`.

## Contribute

Bugs, ideas and pull requests please go to [AtomLinter/linter-luacheck](https://github.com/AtomLinter/linter-luacheck).
