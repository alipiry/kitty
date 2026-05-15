# kitty

My personal [kitty](https://sw.kovidgoyal.in/kitty/) terminal emulator config.

## Highlights

- **Font:** Vazir Code Hack @ 22pt, ligatures enabled
- **Theme:** Dark background with vivid 16-color palette, yellow block cursor
- **Scrollback:** 10,000 lines, `less` pager
- **Tab bar:** Bottom, fade style with green active tab
- **Mod key:** `cmd` (macOS-friendly)
- **Misc:** Copy on select, audio bell off, smooth wheel scrolling

## Install

```sh
git clone https://github.com/alipiry/kitty.git ~/.config/kitty
```

Then restart kitty.

## Shortcuts cheatsheet

> `mod` = `cmd`

### Clipboard

| Shortcut | Action |
| --- | --- |
| `mod` + `v` | Paste from clipboard |
| `mod` + `s` | Paste from selection |

### Scrolling

| Shortcut | Action |
| --- | --- |
| `mod` + `↑` | Scroll line up |
| `mod` + `↓` | Scroll line down |

### Windows

| Shortcut | Action |
| --- | --- |
| `mod` + `enter` | New window |
| `mod` + `shift` + `enter` | New window with cwd |
| `mod` + `t` | New OS window |
| `mod` + `w` | Close window |
| `mod` + `shift` + `→` / `↑` | Next window |
| `mod` + `shift` + `←` / `↓` | Previous window |
| `mod` + `k` | Next window |
| `mod` + `j` | Previous window |
| `mod` + `f` | Move window forward |
| `mod` + `r` | Start resizing window |
| `mod` + `1`…`0` | Jump to window 1–10 |

### Layouts

| Shortcut | Action |
| --- | --- |
| `mod` + `l` | Next layout |

### Tabs

| Shortcut | Action |
| --- | --- |
| `mod` + `n` | New tab |
| `mod` + `→` | Next tab |
| `mod` + `←` | Previous tab |
| `mod` + `.` | Move tab forward |
| `mod` + `shift` + `,` | Set tab title |

### Font size

| Shortcut | Action |
| --- | --- |
| `mod` + `=` | Increase font size |
| `mod` + `-` | Decrease font size |
| `mod` + `backspace` | Reset font size |

### Miscellaneous

| Shortcut | Action |
| --- | --- |
| `mod` + `f11` | Toggle fullscreen |
| `mod` + `f10` | Toggle maximized |
| `mod` + `u` | Unicode input |
| `mod` + `f2` | Edit config file |
