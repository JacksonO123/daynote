# Daynote

Easy way to create, edit, and manage daily note files from command line.

## Configuration

Configuration is done in `~/.config/daynote/daynote.conf` file

### Options

#### command

Default: `vim`

Configured with the `cmd` property

Example:

```
cmd=nvim
```

#### file extension

Default: `md`

Configured with `ext` property

Example:

```
cmd=txt
```

### Default file contents

Configured in `~/.config/daynote/startup.txt` file.

This file is `.txt` but only the contents are moved so it doesn't matter.

## Installation

I recommend cloning the repo into some directory, then adding a simlink to the bash file in a `scripts` directory in your home directory.

```sh
export PATH="$HOME/scripts"
```

```sh
cd ~/scripts
ln -s ~/path/to/daynote/bash daynote
#     ^- fill in yourself -^
```

You could also copy the current contents of the bash file into another file you have somewhere maybe as a function. Or do litterally anything else idc.
