# My Windhawk Mods

[Windhawk](https://windhawk.net/) mods I have written.

## Mods

| Mod | What it does |
| --- | --- |
| [Desktop Icon Selection Style](mods/desktop-icon-selection-style.wh.cpp) | Restyles the highlight behind selected desktop icons - size, transparency, rounded corners, glow, and a solid, dashed or dotted border. |

## Installing

These are plain source files, not packages. To use one:

1. Open Windhawk and choose **Create new mod**.
2. Replace the contents with the mod file.
3. Press **Ctrl+B** to compile, then enable it.

Settings appear under the mod once it is installed.

## Layout

- `mods/` - installable mods, each named `<mod-id>.wh.cpp` so the name matches
  the mod id. That is the convention the official
  [windhawk-mods](https://github.com/ramensoftware/windhawk-mods) repository
  requires, and matching it here means submitting a mod is a straight copy.
- `attachments/` - screenshots and other files the mod readmes link to.

Readme images are linked by commit permalink rather than by branch. A published
mod carries its readme with it, so a URL that breaks when a file is moved would
need a whole new mod release to fix.

## Licence

MIT, unless an individual file says otherwise.
