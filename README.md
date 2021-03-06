# Little Backup Box

Bash shell scripts that transform a Raspberry Pi (or any single-board computer running a Debian-based Linux distribution) into an inexpensive, fully-automatic, pocketable photo backup and streaming device.

<img src="http://i.imgur.com/xrpfK9h.jpg" alt="" width="375"/>

## Installation

Run the following command on your Raspberry Pi:

    curl -sSL https://goo.gl/btmpKd | bash

When prompted, reboot the Raspberry Pi.

## Usage

1. Boot the Raspberry Pi
2. Plug in the backup storage device
3. Plug in the card reader and wait till the Raspberry Pi shuts down

**Note:** To differentiate between different storage cards, the backup script assigns a random 8-digit identifying number to each card (this number is stored in the *CARD_ID* file in the root of the card). The contents of the card is saved on the storage device in a folder with the identifying number as its name.

## Problems?

Please report bugs and issues in the [Issues](https://github.com/dmpop/little-backup-box/issues) section.

## Author

Dmitri Popov [dmpop@linux.com](mailto:dmpop@linux.com)

## License

The [GNU General Public License version 3](http://www.gnu.org/licenses/gpl-3.0.en.html)

## Linux Photography

Little Backup Box is a part of a streamlined and automated Linux-based photographic workflow described in the [Linux Photography](https://gumroad.com/l/linux-photography) book. The book provides step-by-step instructions on building a Raspberry Pi-based photo backup device running the Little Backup Box script. Get your copy at [Gumroad](https://gumroad.com/l/linux-photography).

<img src="https://scribblesandsnaps.files.wordpress.com/2016/07/linux-photography-6.jpg" width="200"/>
