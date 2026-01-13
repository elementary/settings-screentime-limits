# Screen Time & Limits Settings
[![Translation status](https://l10n.elementaryos.org/widget/settings/screentime-limits/svg-badge.svg)](https://l10n.elementaryos.org/engage/settings/)

![screenshot](data/screenshot.png?raw=true)

## Building and Installation

You'll need the following dependencies:

* libaccountsservice-dev
* libadwaita-1-dev
* libdbus-1-dev
* libflatpak-dev
* libglib2.0-dev
* libgranite-7-dev (>= 7.4.0)
* libgtk-4-dev
* libmalcontent-0-dev
* libpolkit-gobject-1-dev
* libswitchboard-3-dev
* meson >= 0.46.1
* policykit-1
* valac

Run `meson` to configure the build environment and then `ninja` to build

    meson build --prefix=/usr
    cd build
    ninja

To install, use `ninja install`

    ninja install
