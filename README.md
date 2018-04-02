# script screen find ssh agent

In a long running screen sessions on a remote host a forwarded ssh agent is only available till this first disconnect of the ssh connection.

This script searches for available agents and add them to the environment.

## Usage

```sh
. screen-find-ssh-agent
```

Don't miss the dot. It is an alias for `source` and is needed to change the environment of the current shell.


## Installation

Alternatives:

* Use my tool [link-script-paths](https://github.com/simonwalz/script-link-script-paths).

Or do it manually:

* Close this repository and add it to the path environment.

* Copy all scripts to a directory already added to the path environment. E.g. `/usr/local/bin`
