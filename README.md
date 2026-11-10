# amix-media

The release files of [amigaux](https://amigaux.org): install CDs, boot floppies, boot disks, ready installed
disk images and the Z3660 firmware a release is tested with. Each version is one GitHub release of this
repository, with its files, a `SHA256SUMS` and the release's content check (`RELEASE-CHECK.txt`). This
repository holds no source: the media are built from [amigaux/amix](https://github.com/amigaux/amix), and the
Commodore system files they carry are in [amigaux/amix-system](https://github.com/amigaux/amix-system).

## Documentation

- Release notes: <https://amigaux.org/release-notes/1.1/>
- Installing: <https://amigaux.org/install/>
- The packages an installed system takes later come from <http://pkg.amigaux.org/1.1>, not from here.

## Checking a download

    sha256sum -c --ignore-missing SHA256SUMS

## Licensing

| What | Licence |
|---|---|
| amigaux's own work on the media: the installer, the boot loader, the kernels' and drivers' own code, the packages built from amix | MIT, Jussi Alanärä (see `LICENSE` in amigaux/amix); a package built from someone else's work keeps that work's licence |
| the Commodore files the media carry (the Amiga UNIX system: the stock packages, kernel objects and files) | published under Amiga Corporation's approval, given on 2026-09-23; not covered by the MIT licence |
| the Z3660 firmware | its own licence, as stated in its README |

Amiga Corporation approved releasing Amiga UNIX on 2026-09-23, and the Commodore files on these media are published
under that approval. They are not covered by amix's MIT licence.

This site and its developers are not affiliated with, endorsed by, or sponsored by Amiga Corporation. Amiga is a
registered trademark of Amiga Corporation.
