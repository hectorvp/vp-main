vp
==



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/vp.svg)](https://npmjs.org/package/vp)
[![Downloads/week](https://img.shields.io/npm/dw/vp.svg)](https://npmjs.org/package/vp)
[![License](https://img.shields.io/npm/l/vp.svg)](https://github.com/hectorvp/vp/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g vp
$ vp COMMAND
running command...
$ vp (-v|--version|version)
vp/0.0.0 darwin-x64 node-v14.17.1
$ vp --help [COMMAND]
USAGE
  $ vp COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`vp hello [FILE]`](#vp-hello-file)
* [`vp help [COMMAND]`](#vp-help-command)

## `vp hello [FILE]`

describe the command here

```
USAGE
  $ vp hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ vp hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/hectorvp/vp/blob/v0.0.0/src/commands/hello.ts)_

## `vp help [COMMAND]`

display help for vp

```
USAGE
  $ vp help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_
<!-- commandsstop -->
