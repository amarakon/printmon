PrintMon – Print Monitor
================

## Contents

-   [Usage](#usage)
-   [Dependencies](#dependencies)
-   [Installation](#installation)
    -   [Universal](#universal)
    -   [Gentoo](#gentoo)
-   [Uninstallation](#uninstallation)
    -   [Universal](#universal-1)
    -   [Gentoo](#gentoo-1)

PrintMon is a simple script to print the monitor number. It is useful
for scripting.

## Usage

``` sh
`# user` printmon
```

## Dependencies

1.  xrandr
2.  xdotool

## Installation

### Universal

``` sh
`# user` git clone https://github.com/amarakon/printmon
`# user` cd printmon
`# root` make install
```

### Gentoo

``` sh
`# root` eselect repository add amarlay git https://github.com/amarakon/amarlay
`# root` emerge --sync amarlay
`# root` emerge x11-misc/printmon
```

## Uninstallation

### Universal

``` sh
`# user` cd printmon
`# root` make uninstall
```

### Gentoo

``` sh
`# root` emerge -c x11-misc/printmon
# Remove my overlay (optional)
`# root` eselect-repository remove -f amarlay
`# root` emerge --sync
```
