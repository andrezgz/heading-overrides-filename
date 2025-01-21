# Heading Overrides Filename (BETA)

> Override (verb). To prevail over; conquer.

[Obsidian](https://obsidian.md/) plugin that updates the filename according to the first level 1 heading (H1) in the note.

> **Warning**: This plugin will rename your files. This action is irreversible.

- When you set or update the first level 1 heading of a file, it renames the file.
- When a file is opened in edit mode, if the first level 1 heading is found, it's used to rename the file.

This project was derived from [Obsidian Filename Heading Sync](https://github.com/dvcrn/obsidian-filename-heading-sync) by @dvcrn

## Configuration

Rules for replacing characters in the heading. The result is used to rename the file.

- **Allow Alphanumeric ASCII characters only**: Replace non-alphanumeric ASCII characters (besides the replacement character, if defined)
- **Custom Characters and Strings**: Individual characters or strings to be replaced.
- **Replacement Character**: Character to replace unwanted character/strings. Leave empty to remove them.

Two hooks are available to trigger the rename action automatically: one when a file is saved and another when a file is opened. There is a **Delay** setting to control the number of milliseconds to wait before doing it and a command to manually execute it.

Files can be ignored either manually or by using a rule in regex format.

## Installation

Installation via BRAT

1. Install [BRAT](https://obsidian.md/plugins?id=obsidian42-brat) from the Community Plugins.
2. Open BRAT settings and choose **Add Beta plugin**.
3. Paste in `https://github.com/andrezgz/obsidian-heading-overrides-filename` and click **Add Plugin**.
    - Make sure the option "Enable after installing the plugin" is selected, or
    - Manually enable the **Heading Overrides Filename** plugin in Options -> Community Plugins

## LICENSE

MIT
