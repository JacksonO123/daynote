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
