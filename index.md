![Heads booting on an x230](https://farm6.static.flickr.com/5574/30450989320_f6504cb662.jpg)

Welcome to the Heads firmware wiki! We are in the process of migrating pages into this tree.  Until then:

* [Heads overview](https://trmm.net/Heads)
* [Presentation at 33c3](https://trmm.net/Heads_33c3)

Using Heads
===
* [Installing Heads](/Installing-Heads) on an x230 Thinkpad
* [Upgrading Heads](/Upgrading), including how to generate your TOTP token
* Qubes specific configurations
* Server specific configurations

Developing Heads
===

* [Open issues](https://github.com/osresearch/heads/issues)
* [Emulating Heads](/Emulating-Heads) (with qemu)
* [Porting to a new mainboard](/Porting) (rough draft)
* [Keys, Passwords and PCRs in Heads](/Keys) (rough draft)
* The Heads build process
* Adding a new sub-module

Releases
===
There are currently no binary downloads; you must build from source to ensure that you can add your own GPG keys to the image to sign your installation.

The current release is [0.1.0](https://github.com/osresearch/heads/releases/tag/v0.1.0) and should be fully reproducible on any Linux-ish system ([OSX build is not supported](https://github.com/osresearch/heads/issues/96)).  If you don't get the same hashes, please file an issue against the [reproducible build milestone](https://github.com/osresearch/heads/milestone/1).


