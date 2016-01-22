## Installation

To install nodenv-each, clone this repository into your nodenv plugins directory. (You'll need a recent version of nodenv that supports plugin bundles.)


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

### Examples:

```
$ nodenv each npm install
$ nodenv each -v npm test
```

### Credits

Forked from [rbenv-each](https://github.com/rbenv/rbenv-each) and modified to work for [nodenv](https://github.com/nodenv/nodenv).
