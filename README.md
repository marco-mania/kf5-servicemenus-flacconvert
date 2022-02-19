# KDE service menus for flac file converting

KDE service menus for flac file converting.

## Prerequisites

* [KDE](https://www.kde.org/)
* [FLAC](https://xiph.org/flac/)
* [LAME](https://lame.sourceforge.io/)
* [Opus](https://opus-codec.org/)

## Installation

    sudo cp ServiceMenus/* /usr/share/kservices5/ServiceMenus/
    sudo cp bin/flacconvert-kdialog /usr/local/bin/

## Uninstall

    sudo rm /usr/share/kservices5/ServiceMenus/flacconvert.desktop.desktop
    sudo rm /usr/local/bin/flacconvert-kdialog

## Contributing

Pull requests are welcome. For major changes, please open an issue first to
discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[GPL-3.0+](https://www.gnu.org/licenses/gpl-3.0.de.html)
