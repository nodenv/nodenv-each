# nodenv-each

Invoke commands for each installed Node version

[![Tests](https://img.shields.io/github/actions/workflow/status/nodenv/nodenv-each/test.yml?label=tests&logo=github)](https://github.com/nodenv/nodenv-each/actions/workflows/test.yml)
[![Latest GitHub Release](https://img.shields.io/github/v/release/nodenv/nodenv-each?label=github&logo=github&sort=semver)](https://github.com/nodenv/nodenv-each/releases/latest)
[![Latest Homebrew Release](<https://img.shields.io/badge/dynamic/regex?label=homebrew-nodenv&logo=homebrew&logoColor=white&url=https%3A%2F%2Fraw.githubusercontent.com%2Fnodenv%2Fhomebrew-nodenv%2Frefs%2Fheads%2Fmain%2FFormula%2Fnodenv-each.rb&search=archive%2Frefs%2Ftags%2Fv(%3F%3Cversion%3E%5Cd%2B.*).tar.gz&replace=v%24%3Cversion%3E>)](https://github.com/nodenv/homebrew-nodenv/blob/main/Formula/nodenv-each.rb)
[![Latest npm Release](https://img.shields.io/npm/v/@nodenv/nodenv-each?logo=npm&logoColor=white)](https://www.npmjs.com/package/@nodenv/nodenv-each/v/latest)

<!-- toc -->

- [Installation](#installation)
- [Usage](#usage)
  - [Examples](#examples)
- [Credits](#credits)

<!-- tocstop -->

## Installation

To install nodenv-each, clone this repository into your nodenv plugins directory.

```console
mkdir -p "$(nodenv root)"/plugins
git clone https://github.com/nodenv/nodenv-each.git "$(nodenv root)"/plugins/nodenv-each
```

## Usage

```console
nodenv help each
```

Verbose mode will print a header for each node so you can distinguish
the output.

**note**: Aliases ([nodenv-aliases][]) or symlinks are skipped.

### Examples

```console
nodenv each npm install
nodenv each -v npm test
```

## Credits

Forked from [Chris Eppstein's](https://github.com/chriseppstein)
[rbenv-each](https://github.com/rbenv/rbenv-each)
by [Jason Karns](https://github.com/jasonkarns)
and modified for [nodenv](https://github.com/nodenv/nodenv).

[nodenv-aliases]: https://github.com/nodenv/nodenv-aliases
