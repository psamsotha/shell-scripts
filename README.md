# shell-scripts

A collection of some shell scripts that I use for common tasks.


## Install

To install the scripts, clone this repository, then put the project
directory on the `PATH`. Then you should be able to use the command
without having to use the path of the script

```shell
cd <install-dir>
git clone https://github.com/psamsotha/shell-scripts.git
export PATH="${PATH}:<install-dir>/shell-scripts"
```

If you dont want to have to keep typing the `export` everytime you open
a new shell, you can put the export into a `~/.bash_profile`, `~/.bashrc`,
or `~/.zshrc` (depending on your particular shell).

* [Cheat Sheets (cheat)](#cheat-sheets)



## Cheat Sheets

This script helps with the management of simple cheat sheets that
you edit and view from the terminal.

### Motivation

I often keep cheat sheets strored as text files. I wanted to find an easy
way to manage, organize, and retrieve these files when needed. So I just
created a simple script to help with these tasks. The options provided
are the most common tasks that I am always performing on these text files.

### Commands

#### View

When used without an options, the specified cheat sheet will be displayed
in the terminal.

```shell
cheat <cheat sheet>
```

#### New

To create a new cheat sheet, use the `-n` option, followed by the name of
the new cheat sheet.

```shell
cheat -n <cheat sheet>
```

#### Edit

To edit an existing cheat sheet, use the `-e` option, followed bu the name
of the cheat sheet to edit.

```shell
cheat -e <cheat sheet>
```

#### Delete

To delete an existing cheat sheet, use the `--rm` option, followed by the
name of the cheat sheet to delete.

```shell
cheat --rm <cheat sheet>
```

#### List

To list all available cheat sheets, use the `-l` option.

```shell
cheat -l
```


