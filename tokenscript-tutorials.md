This is a serial of tutorials for tokenscript.

# installation

## pre-requisitions

compatible node versions are: `16.20.2` and `18.18.2`

## installation

`npm i -g @tokenscript/cli`

## tokenscript project lifecycle

create -> build -> emulate

`tokenscript create -t empty` - create an empty tokenscript project

`tokenscript build` - build the tokenscript project

`tokenscript emulate` - show the tokenscript demo in the web browser

## tokenscript commands

once tokenscript installed, you can use `tokenscript` command as following:

```
A tool for managing tokenscript projects

VERSION
  @tokenscript/cli/1.0.11 darwin-arm64 node-v18.16.0

USAGE
  $ tokenscript [COMMAND]

TOPICS
  plugins  List installed plugins.

COMMANDS
  build        Build the tokenscript project into a .tsml
  certificate  Create a certificate request or sign an existing request.
  create       Create a new TokenScript project
  emulate      Emulate the TokenScript in a browser
  help         Display help for tokenscript.
  plugins      List installed plugins.
  sign         sign the built .tsml
  validate     Validate an existing .tsml
```