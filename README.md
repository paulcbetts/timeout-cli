# timeout-cli: GNU timeout for node

This utility reimplements GNU timeout, but for operating systems that don't support it, like macOS and Windows. 

## To Install:

```sh
npm i -g timeout-cli
```

## Usage:

```
Usage: timeout -- some-cmd arg1 arg2 arg3
Execute a command and exit if it doesn't terminate in a certain amount of time

Options:
  -t, --timeout     is a floating point number with an optional suffix: 's' for
                    seconds (the default), 'm' for minutes, 'h' for hours or 'd'
                    for days.                                           [string]
  -o, --on-timeout  if set, command will be executed when a timeout occurs
                                                                        [string]
  -v, --version     Print the current version number and exit
```

