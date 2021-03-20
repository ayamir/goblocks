# Goblocks

## Intro

A simple status monitor for dwm written by go (use nord palette default).

## Effect

![dark](./shot/dark.png)

![light](./shot/light.png)

+ Time icon changes as time goes on.
+ Battery icon changes with battery state.
+ Volume icon changes with volume state.

## Dependencies

Your dwmbar font should be a [nerd font](https://github.com/ryanoasis/nerd-fonts).

[pamixer](https://github.com/cdemoulins/pamixer) should be installed to get volume.

[status2d](https://dwm.suckless.org/patches/status2d/) should be patched to display color.

## Usage

```shell
git clone https://github.com/ayamir/goblocks
cd goblocks
go build .
goblocks &
```

## Configuration

The source code is extremely simple so you can hack all of it.

Of course, you can change icons and colors easily.

You can find about more colors usage at [status2d](https://dwm.suckless.org/patches/status2d)'s webpage.

Like this:

![dark_bg](./shot/dark_bg.png)

## Credit

[gods](https://github.com/schachmat/gods) give me the initial inspire.

## TODO

-   [ ] Clickable

-   [ ] Scrollable
