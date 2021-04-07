
# Table of Contents

1.  [Goblocks](#org053a3e6)
    1.  [Intro](#orgb9682a5)
    2.  [Effect](#orgb68acdb)
    3.  [Dependency](#org7fa3a30)
    4.  [Usage](#org3a1cdb4)
    5.  [Configuration](#org289a659)
    6.  [Credit](#org22b9f62)
    7.  [TODO](#org911fdee)


<a id="org053a3e6"></a>

# Goblocks


<a id="orgb9682a5"></a>

## Intro

A simple status monitor for dwm written by go (use nord palette default).


<a id="orgb68acdb"></a>

## Effect

[dark](./shot/dark.png)

[light](./shot/light.png)

-   Time icon changes as time goes on.
-   Battery icon changes with battery state.
-   Volume icon changes with volume state.


<a id="org7fa3a30"></a>

## Dependency

Your dwmbar font should be a [nerd font](https://github.com/ryanoasis/nerd-fonts).

[pamixer](https://github.com/cdemoulins/pamixer) should be installed to get volume.

[status2d](https://dwm.suckless.org/patches/status2d/) should be patched to display color.


<a id="org3a1cdb4"></a>

## Usage

You should change default network interface settings in config.toml to adjust your machine.

If you need change the default settings:

    git clone https://github.com/ayamir/goblocks
    cd goblocks
    mkdir -p $HOME/.config/goblocks
    cp config.toml $HOME/.config/goblocks
    go build .
    goblocks &

Or just use the default configuration:

    git clone https://github.com/ayamir/goblocks
    cd goblocks
    mkdir -p $HOME/.config/goblocks
    cp config.toml $HOME/.config/goblocks
    export $GOBIN=$HOME/go/bin
    export PATH=$GOPATH:$PATH
    go get -u github.com/ayamir/goblocks
    goblocks &


<a id="org289a659"></a>

## Configuration

The source code is extremely simple so you can hack all of it.

Of course, you can change icons and colors easily.

You can find about more colors usage at [status2d](<https://dwm.suckless.org/patches/status2d>)&rsquo;s webpage.

Like this:

[darkbg](./shot/dark_bg.png)


<a id="org22b9f62"></a>

## Credit

[gods](https://github.com/schachmat/gods) give me the initial inspire.


<a id="org911fdee"></a>

## TODO

-   [-] Read Config file <code>[50%]</code>
    -   [X] Network interface
    -   [-] Display color style
-   [ ] Clickable
-   [ ] Scrollable

