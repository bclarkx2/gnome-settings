# Installation

`git clone git@github.com:bclarkx2/gnome-settings`


# Usage

## Create a new settings store

`./new setting path`

* `setting` - the short name for this particular setting you want to save. This is just a short identifier and doesn't have to match anything in dconf. Ex: "custom-keybindings"
* `path` - the dconf settings path for this setting


## Dump a setting

`./dump setting`

This will copy the dconf config for this setting from your machine to the appropriate folder in the `setting` directory.


## Load a setting

`./load setting`

This will load the config in the `setting` direcotry onto your machine.


## Load/Dump all settings

`./all [ dump | load ]`

Will either dump or load each setting in the repository.

