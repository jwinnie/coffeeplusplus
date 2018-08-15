# Coffee++

🚧 Warning: under heavy development. Not ready for production. 🚧

A fork of CoffeeScript inspired by Elixir and Python.
Current features:
- Remove yes/no, on/off aliases
- Add Elixir/F# pipe operator (`|>`)

## Installation

There is no NPM package yet; you will have to install from source:
```shell
(~)$ git clone https://github.com/jwinnie/coffeescript
(~)$ cd coffeescript
(coffeescript)$ npm i
(coffeescript)$ sudo npm i -g coffeescript # Required in order to run cake
(coffeescript)$ cake build # Build the source code
(coffeescript)$ cake test # Run the test suite
```
Run the Coffee++ compiler in development with `bin/coffee`. 

## Getting Started

Execute a script:

```shell
coffee /path/to/script.coffee
```

Compile a script:

```shell
coffee -c /path/to/script.coffee
```

For documentation, usage, and examples, see: https://coffeescript.org/

To suggest a feature or report a bug: https://github.com/jashkenas/coffeescript/issues

If you’d like to chat, drop by #coffeescript on Freenode IRC.

The source repository: https://github.com/jashkenas/coffeescript.git

Changelog: https://coffeescript.org/#changelog

Our lovely and talented contributors are listed here: https://github.com/jashkenas/coffeescript/contributors
