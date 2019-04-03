todo-mv
=======

Todo List

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/todo-mv.svg)](https://npmjs.org/package/todo)
[![CircleCI](https://circleci.com/gh/mverost44/todocli/tree/master.svg?style=shield)](https://circleci.com/gh/mverost44/todocli/tree/master)
[![Downloads/week](https://img.shields.io/npm/dw/todo.svg)](https://npmjs.org/package/todo)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g todo-mv
$ todocli COMMAND
running command...
$ todocli (-v|--version|version)
todo-mv/1.0.3 linux-x64 node-v10.15.0
$ todocli --help [COMMAND]
USAGE
  $ todocli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`todocli add`](#todocli-add)
* [`todocli help [COMMAND]`](#todocli-help-command)
* [`todocli remove`](#todocli-remove)
* [`todocli show`](#todocli-show)
* [`todocli update`](#todocli-update)

## `todocli add`

Adds a new Todo

```
USAGE
  $ todocli add

OPTIONS
  -n, --task=task  task

DESCRIPTION
  ...
  Adds a new todo to the existing list
```

_See code: [src/commands/add.js](https://github.com/mverost44/todocli/blob/v1.0.3/src/commands/add.js)_

## `todocli help [COMMAND]`

display help for todocli

```
USAGE
  $ todocli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.6/src/commands/help.ts)_

## `todocli remove`

Removes a task by id

```
USAGE
  $ todocli remove

OPTIONS
  -n, --id=id  (required) task id

DESCRIPTION
  ...
  Removes a task permanently from database by id
```

_See code: [src/commands/remove.js](https://github.com/mverost44/todocli/blob/v1.0.3/src/commands/remove.js)_

## `todocli show`

Shows existing tasks

```
USAGE
  $ todocli show

DESCRIPTION
  ...
  Shows all the tasks sorted by their ids
```

_See code: [src/commands/show.js](https://github.com/mverost44/todocli/blob/v1.0.3/src/commands/show.js)_

## `todocli update`

Marks a task as done

```
USAGE
  $ todocli update

OPTIONS
  -n, --id=id  task id

DESCRIPTION
  ...
  Marks a task as done
```

_See code: [src/commands/update.js](https://github.com/mverost44/todocli/blob/v1.0.3/src/commands/update.js)_
<!-- commandsstop -->
