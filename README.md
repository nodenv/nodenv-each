## Installation

To install nodenv-each, clone this repository into your nodenv plugins directory.

```
$ mkdir -p "$(nodenv root)"/plugins
$ git clone https://github.com/nodenv/nodenv-each.git "$(nodenv root)"/plugins/nodenv-each
```

## Usage

```
$ nodenv help each
```

Verbose mode will print a header for each node so you can distinguish
the output.

**note**: Aliases ([nodenv-aliases][]) or symlinks are skipped.

### Examples:

```
$ nodenv each npm install
$ nodenv each -v npm test
```

## Credits

Forked from [Chris Eppstein][chriseppstein]'s [rbenv-each][] by [Jason Karns][jasonkarns] and modified for [nodenv][].

[chriseppstein]: https://github.com/chriseppstein
[rbenv-each]: https://github.com/rbenv/rbenv-each
[jasonkarns]: https://github.com/jasonkarns
[nodenv]: https://github.com/nodenv/nodenv
