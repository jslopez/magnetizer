# magnetizer

## Installation
Run `./install.sh`.

## Usage
Once installed, it will print the list of available tasks to perform. This list can be printed with `fab -l`.
Each task must be ran as follows:
`fab -H <user>@<host> <task>...`

### Examples
To get zsh installed and set as the default shell on your local machine, you should ran:
`fab -H <user>@localhost zsh.install`
