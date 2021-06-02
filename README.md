jstrapp
=======

Bootstrap simple opinionated JS apps

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/jstrapp.svg)](https://npmjs.org/package/jstrapp)
[![Downloads/week](https://img.shields.io/npm/dw/jstrapp.svg)](https://npmjs.org/package/jstrapp)
[![License](https://img.shields.io/npm/l/jstrapp.svg)](https://github.com/716green/jstrapp/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g jstrapp
$ jstrapp COMMAND
running command...
$ jstrapp (-v|--version|version)
jstrapp/0.0.1 darwin-arm64 node-v15.12.0
$ jstrapp --help [COMMAND]
USAGE
  $ jstrapp COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`jstrapp hello [FILE]`](#jstrapp-hello-file)
* [`jstrapp help [COMMAND]`](#jstrapp-help-command)

## `jstrapp hello [FILE]`

describe the command here

```
USAGE
  $ jstrapp hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ jstrapp hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/716green/jstrapp/blob/v0.0.1/src/commands/hello.ts)_

## `jstrapp help [COMMAND]`

display help for jstrapp

```
USAGE
  $ jstrapp help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_
<!-- commandsstop -->
