# Awesome-File-Compression-Archive-Management

Top File Compression Archive Management (Opensource) 🌟 Star if you like it! 🌟

A curated list of the best open-source file compression tools, archive managers, CLI utilities, compression algorithms, and hosted/cloud archive extractors.

## Contents

- [Open-Source Software](#open-source-software)
  - [Desktop GUI Archive Managers](#desktop-gui-archive-managers)
  - [Command-Line (CLI) Archivers & Tools](#command-line-cli-archivers--tools)
  - [Compression Algorithms & Libraries](#compression-algorithms--libraries)
  - [Web-Based & Self-Hosted Extractors](#web-based--self-hosted-extractors)
- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Contributing](#contributing)
- [License](#license)

---

## Open-Source Software

### Desktop GUI Archive Managers

* [7-Zip](https://7-zip.org) - File archiver with a high compression ratio supporting 7z, XZ, BZIP2, GZIP, TAR, ZIP, and WIM formats. ([Source Code](https://github.com))
* [PeaZip](https://github.io) - Cross-platform file and archive manager based on Open Source technologies supporting 200+ archive formats. ([Source Code](https://github.com))
* [Keka](https://keka.io) - Free and open-source macOS file archiver supporting 7z, Zip, Tar, Gzip, Bzip2, XZ, Lzip, DMG, and ISO. ([Source Code](https://github.com))
* [NanaZip](https://github.com) - Open-source file archiver intended for the modern Windows experience, forked from 7-Zip.
* [Ark](https://kde.org) - KDE's graphical file compression and decompression tool supporting multiple formats including tar, gzip, bzip2, zip, and rar. ([Source Code](https://kde.org))
* [File Roller](https://gnome.org) - Archive manager for the GNOME desktop environment.
* [Xarchiver](https://github.com) - Lightweight desktop-independent GTK+ frontend for manipulating 7z, arj, bzip2, gzip, rar, tar, and zip files.
* [Engrampa](https://github.com) - Archive manager for the MATE desktop environment, forked from File Roller.
* [MacUnarchiver / The Unarchiver (XADMaster)](https://github.com) - Objective-C unarchiving library and engine powering open-source macOS archive tools.
* [p7zip](https://github.com) - POSIX/Linux port of the 7-Zip command line and GUI utilities.

### Command-Line (CLI) Archivers & Tools

* [atool](https://nongnu.org) - Script for managing file archives of various types (`aunpack`, `apack`, `als`, `acat`) with unified syntax.
* [ouch](https://github.com) - Painless compression and decompression in the terminal written in Rust supporting `.tar`, `.zip`, `.bz`, `.xz`, `.lzma`, `.gz`, and `.zst`.
* [dtrx](https://github.com) - "Do The Right Extraction" — intelligent archive extraction tool that handles nested archives and permissions automatically.
* [patool](https://github.com) - Portable command-line archive file manager written in Python supporting over 30 archive formats.
* [unar / lsar](https://theunarchiver.com) - Command-line tools for listing and extracting almost any archive format cleanly without directory clutter. ([Source Code](https://github.com))
* [GNU Tar](https://gnu.org) - Standard archiving utility to store and extract files from an archive file known as a tarfile.
* [Info-ZIP](http://sourceforge.net) - Portable open-source utilities (`zip` and `unzip`) for manipulating ZIP archives across operating systems.
* [pbzip2](http://greatnet.de) - Parallel implementation of the bzip2 block-sorting file compressor that uses pthreads for multi-core speed.
* [pigz](https://zlib.net) - Parallel implementation of gzip that exploits multiple processors and multiple cores to the hilt when compressing data.
* [pixz](https://github.com) - Parallel, indexed XZ compressor for faster multi-threaded compression and random-access decompression.
* [plzip](https://nongnu.org) - Massively parallel lossless data compressor based on the lzip file format.
* [dar](http://free.fr) - Disk ARchive CLI tool designed for incremental backups, slicing, encryption, and differential archiving.
* [zpaq](http://mattmahoney.net) - Incremental journaling archiver with high compression ratios and built-in deduplication.

### Compression Algorithms & Libraries

* [Zstandard (zstd)](https://github.com) - Fast real-time compression algorithm providing high compression ratios, developed by Meta.
* [Brotli](https://github.com) - Generic-purpose lossless compression algorithm developed by Google, widely used for web assets and archives.
* [LZ4](https://github.com) - Extremely fast lossless compression algorithm providing compression speeds > 500 MB/s per core.
* [XZ Utils (LZMA)](https://tukaani.org) - General-purpose data compression software with a high compression ratio based on the LZMA2 algorithm.
* [zlib](https://github.com) - Massively spiffy yet delicately unobtrusive compression library implementing the Deflate algorithm.
* [Snappy](https://github.com) - Fast compressor/decompressor developed by Google aiming for very high speeds and reasonable compression.
* [libarchive](https://github.com) - Multi-format archive and compression C library powering `bsdtar` and numerous open-source extractors.
* [Blosc (C-Blosc2)](https://github.com) - High-performance compressor optimized for binary data and memory-to-memory transfers.
* [Zopfli](https://github.com) - Compression library programmed in C to perform very good, but slow, deflate or zlib compression.
* [Lzip](https://nongnu.org) - Lossless data compressor based on the LZMA algorithm with strict integrity checking.

### Web-Based & Self-Hosted Extractors

* [hatchzip](https://github.com) - Open-source web-based archive extraction and compression tool.
* [zip.js](https://github.com) - JavaScript library to zip and unzip files directly in the browser using Web Workers.
* [JSZip](https://github.com) - Create, read, and edit `.zip` files with JavaScript directly on the client side.
* [fflate](https://github.com) - High-performance, lightweight pure JavaScript compression and decompression library.
* [libarchive.js](https://github.com) - WebAssembly port of `libarchive` enabling extraction of RAR, 7z, TAR, GZIP, and ZIP files in the browser.

---

## SaaS / Hosted Platforms

| Product | Description | Company Size (Valuation / Revenue) | Starting Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| [WinZip](https://winzip.com) | Commercial file archiver and cloud storage compression suite for Windows and macOS. | **~$1 Billion** (Acquired by KKR for $1B; estimated parent revenue ~$100M+) | $34.95 (one-time standard license) / ~$10/mo billed annually | 21-day free trial (no credit card required; locks access after 21 days) |
| [WinRAR](https://win-rar.com) | Commercial proprietary archive manager for Windows famous for native RAR creation and recovery records. | **~$15M – $30M Annual Revenue** (~$100M+ theoretical valuation; €1M+ annual net profit) | $29.00 (one-time perpetual single-user license) | 40-day free trial (full functionality with reminder prompts upon trial expiration) |
| [CloudConvert](https://cloudconvert.com) | Cloud-based file converter and archive utility supporting ZIP, RAR, 7Z, TAR, GZ, and BZ2 conversions via web UI and API. | **~$1M – $5M ARR** (Private, Bootstrapped / Lunaweb GmbH) | $9.00/month (1,000 monthly conversion credits) or $17.00 one-time credit package | Free forever plan with 10 conversion credits/day, max 1 GB file size, 5 concurrent tasks, and 5 minutes/conversion |
| [Bandizip](https://bandisoft.com) | Lightweight, fast Windows and macOS archiver featuring multi-core compression and archive repair (Freemium/Proprietary). | **~$900K – $3M Annual Revenue** (1.2B – 4B KRW; Bandisoft) | $30.00 (one-time single-user license) | Free forever standard edition (includes ads; max 16 CPU threads; password manager, archive repair, and image preview disabled) |
| [123apps Archive Extractor](https://extract.me) | Free web application to extract over 70 types of compressed files including 7z, zipx, rar, tar, exe, and dmg. | **~$500K – $2M Annual Revenue** (Bootstrapped / 123apps LLC) | $6.00/month (or $48/year billed annually) | Free forever plan with up to 10 GB file size limit, ad-supported, and standard processing speed |
| [Convertio Archive Converter](https://convertio.co) | Hosted cloud platform for converting between various archive formats seamlessly. | **~$500K – $2M Annual Revenue** (Private / Convertio Ltd.) | $9.99/month (Light plan with 500 MB max file size and 25 concurrent conversions) | Free forever plan with up to 100 MB file size limit and 10 conversion credits per 24 hours |
| [ezyZip](https://ezyzip.com) | Free online browser-based file compression and extraction utility that processes files locally without server uploads. | **~$100K – $500K Annual Revenue** (Indie SaaS & Ad-supported) | $18.00/month (or $54/year, $98 lifetime access for ezyZip Pro) | Free forever plan with up to 2 GB file size limit, ad-supported, standard browser WebAssembly processing |

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request to add more open-source compression tools, libraries, or hosted archive utilities.

## License

[![CC0](https://licensebuttons.net)](https://creativecommons.org)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

