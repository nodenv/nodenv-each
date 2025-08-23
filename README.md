# nodenv-each

[![Build Status](https://travis-ci.org/nodenv/nodenv-each.svg?branch=master)](https://travis-ci.org/nodenv/nodenv-each)

Invoke commands for each nodenv Node version

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
