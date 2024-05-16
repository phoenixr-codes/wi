# wi

`wi` is a wrapper around [linguist][] that pretty prints the languages used
in a git repository to the terminal similar to how it's shown on GitHub. To
use this script [`github-linguist`][linguist] must be installed.

![Preview](./preview.png)

## Installation

Download the `wi` file from this repository and put it in `/usr/local/bin/`
(or similar).


## Usage

```text
Usage:
  > wi (path) 

Flags:
  -h, --help - Display the help message for this command

Parameters:
  path <string>: The path to the git repository (optional, default: '.')

Input/output types:
  ╭───┬─────────┬─────────╮
  │ # │  input  │ output  │
  ├───┼─────────┼─────────┤
  │ 0 │ nothing │ nothing │
  ╰───┴─────────┴─────────╯
```


> ![TIP]
> Use `github-linguist -j | from json` to work with the data by yourself.

[linguist]: https://github.com/github-linguist/linguist
