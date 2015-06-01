## Installation

To install nodenv-each, clone this repository into your nodenv plugins directory. (You'll need a recent version of nodenv that supports plugin bundles.)


```
$ mkdir -p "$(nodenv root)"/plugins
$ git clone https://github.com/jasonkarns/nodenv-each.git "$(nodenv root)"/plugins/nodenv-each
```

## Usage

```
$ nodenv help each
```

Verbose mode will print a header for each node so you can distinguish
the output.

### Examples:

```
$ nodenv each bundle install
$ nodenv each -v rake test
```
