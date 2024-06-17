# tinted-kitty

A set of [Tinted Theming] scheme templates for the [kitty] terminal
emulator. These templates can be used with any compliant Base16 builder.

**Pre-built** schemes are also available in the [colors] directory of
this repository for convenience.

## Installation

Simply copy the contents of your desired color scheme into your kitty
configuration (`kitty.conf`). If you already have a color scheme defined,
remove it or comment it out before importing the new scheme.

`kitty.conf` locations:

- Linux: `~/.config/kitty/kitty.conf`
- macOS: `~/Library/Preferences/kitty/kitty.conf`

Note that kitty will need to be restarted for the change to take effect.

## 256-color variants

The 256-color variants are for those who wish to use the 16 ANSI colors while
retaining accuracy for bright color variants. For the Base16 color
themes, this is achieved by making the bright variants mirror their
regular counterparts instead of attempting to map them to other Base16
colors. Base24 supports brighter colors.

**TL;DR**: If some colors look strange or darker than normal, try the
256-color variant of your scheme of choice.

[Tinted Theming]: https://github.com/tinted-theming
[kitty]: https://github.com/kovidgoyal/kitty
[colors]: https://github.com/kdrag0n/base16-kitty/tree/main/colors
