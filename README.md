# Keybindings for VSCode on MacOS.

## Motivation

When using Vim Keybindings in VSCode, there are still times one might need to reach for the arrow keys. E.g. when selecting a file, or a code action.

These keybindings use native vim navigation `(j, k) + cmd` for navigating these sections.

## Usage

These keybindings work for both VSCode and Cursor.

### VSCode

```sh
cp keybindings.json ~/Library/Application\ Support/Code/User/keybindings.json
```

### Cursor

For these keybindings to work, make sure to set `workbench.activityBar.orientation` to `vertical` in your settings.json file.

Then, copy the keybindings:

```sh
cp keybindings.json ~/Library/Application\ Support/Cursor/User/keybindings.json
```

## Contributing

If you made changes to the keybindings and you are using VSCode, you can update this repository with:

```sh
cp ~/Library/Application\ Support/Code/User/keybindings.json keybindings.json
```

for Cursor, you can update the file with:

```sh
cp ~/Library/Application\ Support/Cursor/User/keybindings.json keybindings.json
```