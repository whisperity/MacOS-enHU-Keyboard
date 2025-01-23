#  MacOS `enHU` keyboard layout

This is a customised keyboard layout file (created with [Ukelele](https://github.com/sillsdev/Ukelele) for **MacOS**, based on the original _English ABC_ layout but customised to support the 🇭🇺 Hungarian language.

> [!IMPORTANT]
> The primary base language of the keyboard layout is still **English**, which makes it sufficient mostly for programming, but can be daunting if the user's _`huHU`_ layout experience is overwhelming the _`enUS`_ or _`enGB`_ ones.

## How to install?

1. `sudo cp ./English\ Keyboard\ with\ Hungarian\ Accents.bundle /Library/Keyboard\ Layouts/`
2. Log out and log back in, or restart the computer.
3. If the first time installing (i.e., not installing an _update_), add the layout in _System Settings_ → _Keyboard_.

## Features over _`enABC`_

### `ő` and `ű`

A new dead key, <kbd>⌥ Option</kbd> (<kbd>⎇ Alt</kbd>) + <kbd>y</kbd> produces the `˝` symbol, which, when combined with <kbd>o</kbd> or <kbd>u</kbd>, produces `ő` and `ű`, respectively.
Similarly, combining the dead key with the upper-case `O` and `U` produces `Ő` and `Ű`.

### `×` (_"times"_ sign)

The keybind for [`×`](https://www.compart.com/en/unicode/U+00D7) (not `x`!) is present as <kbd>⇮ AltGr</kbd> + <kbd>ú</kbd> (<kbd>]</kbd>) on PC keyboards, but this symbol is completely missing from the Mac.
A custom keybind, <kbd>⌥ Option</kbd> (<kbd>⎇ Alt</kbd>) + <kbd>⇧ Shift</kbd> + <kbd>~</kbd> (the key directly below the <kbd>⎋ Esc</kbd> key on the _`enUS`_ layout), produces this symbol.

### Arrow symbols

In order to type the symbols representing the arrow keys, the following keybinds are available:

 * <kbd>⌃ Control</kbd> + <kbd>⌥ Option</kbd> (<kbd>⎇ Alt</kbd>) + <kbd>⇧ Shift</kbd> + <kbd>w</kbd> produces `↑`
 * <kbd>⌃ Control</kbd> + <kbd>⌥ Option</kbd> (<kbd>⎇ Alt</kbd>) + <kbd>⇧ Shift</kbd> + <kbd>a</kbd> produces `←`
 * <kbd>⌃ Control</kbd> + <kbd>⌥ Option</kbd> (<kbd>⎇ Alt</kbd>) + <kbd>⇧ Shift</kbd> + <kbd>s</kbd> produces `↓`
 * <kbd>⌃ Control</kbd> + <kbd>⌥ Option</kbd> (<kbd>⎇ Alt</kbd>) + <kbd>⇧ Shift</kbd> + <kbd>d</kbd> produces `→`

# Other keyboard layouts for 🇭🇺 _`huHU`_

Creating a tractable experience for typing on a Mac was hard to come by, so here is given respect to others who created layouts better than the "official" one.
These layouts are primarily for the exact or best-effort matching of the real Hungarian keyboard layout.

 * [_@gaborsomogyi_: **Hungarian Keyboard Layouts for MacOS**](https://github.com/gaborsomogyi/hungarian-keyboard-mac)
 * [_@martonlederer_: **Hungarian Keyboard Layout for MacBook programmers**](https://gist.github.com/martonlederer/b429a0885d12a5d14d408cdda4bca877)
