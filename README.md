# Awesome-DataHoarding

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Note: This is only a first draft/brainstorm. I will try to organize the list with more useful sections in the future    
Feel free to contribute!

* [Download utilities](#download-utilities)
  * [Web Archiving](#web-archiving)
  * [General](#general)
  * [Application-specific](#application-specific)
  * [Download automation](#download-automation)
* [Backup](#backup)
* [Compression](#compression)
* [Network](#network)
* [File systems](#file-systems)
* [File conversion](#file-conversion)
* [Utility Scripts](#utility-scripts)
* [Content sharing](#content-sharing)
* [Data curation](#data-curation)
* [APIs & Online tools](#apis--online-tools)
* [Hardware / Monitoring](#hardware--monitoring)
* [Data recovery](#data-recovery)
* [Local Media](#local-media)
* [Long-term data archiving](#long-term-data-archiving)

## Download utilities

**[`^        back to top        ^`](#)**

### Web Archiving
* [ArchiveBox](https://github.com/pirate/ArchiveBox): The open source self-hosted web archive. Takes browser history/bookmarks/Pocket/Pinboard/etc., saves HTML, JS, PDFs, media, and more...
* [Browsertrix Crawler](https://github.com/webrecorder/browsertrix-crawler): Browsertrix Crawler is a simplified (Chrome) browser-based high-fidelity crawling system, designed to run a complex, customizable browser-based crawl in a single Docker container  
* [Collect](https://github.com/xarantolus/Collect): A server to collect & archive websites that also supports video downloads
* [grab-site](https://github.com/ludios/grab-site): The archivist's web crawler: WARC output, dashboard for all crawls, dynamic ignore patterns
* [Heritrix](https://github.com/internetarchive/heritrix3): Extensible, web-scale, archival-quality web crawler
* [HTTrack](https://www.httrack.com/): Download a website from the Internet to a local directory
* [wail](https://github.com/machawk1/wail): Web Archiving Integration Layer: One-Click User Instigated Preservation
* [webrecorder](https://github.com/webrecorder/webrecorder): An integrated platform for creating high-fidelity, ISO-compliant web archives in a user-friendly interface, providing access to archived content, and sharing collections
* [wikiteam](https://github.com/WikiTeam/wikiteam): set of tools for archiving wikis

### General
* [annie](https://github.com/iawia002/annie): YouTube-DL alternative written in Golang
* [aria2](https://aria2.github.io/): A lightweight multi-protocol & multi-source command-line download utility
* [CrowLeer](https://github.com/ERap320/CrowLeer): Powerful C++ web crawler based on libcurl
* [curl](https://github.com/curl/curl): Tool and library for transferring data with URL syntax, supporting many protocols
* [Horahora](https://github.com/horahoradev/horahora): Video hosting website and video archival manager for Niconico, Bilibili, and YouTube
* [httpie](https://httpie.org/): A tool similar to curl and wget but designed to be user friendly, useful for web scraping with shell scripts but be aware you're adding a dependency by doing so.
* [news-crawl](https://github.com/commoncrawl/news-crawl): Cralwer for news feeds based on StromCrawler that prouduces WARC files
* [Plowshare](https://github.com/mcrapet/plowshare): Command-line tool to manage file-sharing site
* [Rclone](https://github.com/ncw/rclone): A command line program to sync files and directories to and from various cloud storage providers
* [rsync](https://rsync.samba.org/): An open source utility that provides fast incremental file transfer
* [Suck-It](https://github.com/skallwar/suckit): Recursively visit and download a website's content to your disk (multi-threaded)
* [wget](https://savannah.gnu.org/git/?group=wget): Utility for non-interactive download of files from the Web
* [wget2](https://gitlab.com/gnuwget/wget2): Successor of GNU Wget, works multi-threaded
* [wpull](https://github.com/ArchiveTeam/wpull): Wget-compatible web downloader and crawler
* [you-get](https://github.com/soimort/you-get): Dumb downloader that scrapes the web
* [Youtube-DL](https://github.com/rg3/youtube-dl): A command-line program to download videos from YouTube and a few hundred more sites
* [ytdl-sub](https://github.com/jmbannon/ytdl-sub): Automate downloading and metadata generation with YouTubeDL
* [ytdl-sub](https://github.com/yt-dlp/yt-dlp): A fork of YT-DLP that behaves better
### Application-specific
* [BBCSoundDownloader](https://github.com/FThompson/BBCSoundDownloader): Bulk downloader for BBC's Sound Effects library http://bbcsfx.acropolis.org.uk/
* [ChanThreadWatch](https://github.com/SuperGouge/ChanThreadWatch): Saves threads from \*chan-style boards and checks for updates until the thread dies
* [comics-downloader](https://github.com/Girbons/comics-downloader): Command-line tool to download comicsand manga in pdf/epub/cbz/cbr from supported sites
* [floatplane_ripper](https://gist.github.com/simon987/0756c378ca2dfb0003931e26ff7fe270): Script to rip all videos from https://floatplane.rip/
* [gallery-dl](https://github.com/mikf/gallery-dl): Download image galleries and collections from pixiv, exhentai, danbooru and more
* [Discord-Channel-Scraper](https://github.com/simon987/Discord-Channel-scraper): Discord server archival (json output, download attachments and emojies)
* [dzi-dl](https://github.com/ryanfb/dzi-dl): Deep Zoom Image Downloader
* [FanFicFare](https://github.com/JimmXinu/FanFicFare): Tool for making eBooks from stories on fanfiction and other web sites
* ~~[FicSave](https://github.com/waylaidwanderer/FicSave): Online fanfiction downloader~~ Source code is available, website however is now offline.
* [flickr_download](https://github.com/beaufour/flickr-download): Simple script to download a Flickr set
* [Google Images Download](https://github.com/hardikvasa/google-images-download): Python script for downloading images
* [iiif-dl](https://github.com/ryanfb/iiif-dl): Command-line tile downloader/assembler for IIIF endpoints/manifests
* [imgbrd-grabber](https://github.com/Bionus/imgbrd-grabber): Very customizable imageboard/booru downloader with powerful filenaming features
* [instaloader](https://github.com/instaloader/instaloader): Download pictures (or videos) along with their captions and other metadata from Instagram
* [InstaLooter](https://github.com/althonos/InstaLooter): API-less Instagram pictures and videos downloader.
* [Instagram Scraper](https://github.com/dankmemes/instagram-scraper): Instagram-scraper is a command-line application written in Python that scrapes and downloads an instagram user's photos and videos. Use responsibly.
* [PyInstaLive](https://github.com/notcammy/PyInstaLive): Instagram live stream downloader
* [RedditDownloader](https://github.com/shadowmoose/RedditDownloader): Scrapes Reddit to download media of your choice
* [Scribd-Downloader](https://github.com/ritiek/scribd-downloader): Allows downloading of Scribd documents
* [snscrape](https://github.com/JustAnotherArchivist/snscrape): A social networking service scraper in Python
* [RipMe](https://github.com/RipMeApp/ripme): RipMe is an album ripper for various websites. Runs on your computer. Requires Java 8.
* [Tube Archivist](https://www.tubearchivist.com/): Self-Hosted Docker container for automated/scheduled YouTube downloads of channels, playlists, etc.
* [tumblr-utils](https://github.com/bbolli/tumblr-utils): Utilities for dealing with Tumblr blogs, Tumblr backup
* [yt-mango](https://github.com/terorie/yt-mango): YouTube metadata archiver the Web (HTTP & FTP)
* [Youtube-MA](https://github.com/CorentinB/YouTube-MA): YouTube metadata archiver

### Download automation
* [bazarr](https://github.com/morpheus65535/bazarr): Companion application to Sonarr and Radarr for downloading subtitles
* [FlexGet](https://github.com/Flexget/Flexget): Multipurpose automation tool for content like torrents, nzbs, podcasts, comics, series, movies, etc.
* [Jackett](https://github.com/Jackett/Jackett): API support for torrent trackers (works with Sonarr, Radarr and others)
* [Lidarr](https://github.com/lidarr/Lidarr): Music collection manager for Usenet and BitTorrent users
* [Mylar](https://github.com/evilhero/mylar): An automated Comic Book downloader (cbr/cbz) for use with SABnzbd, NZBGet and torrents
* [Sick-Beard](https://github.com/midgetspy/Sick-Beard): PVR for newsgroup users (with limited torrent support)
* [Radarr](https://github.com/Radarr/Radarr): A fork of Sonarr to work with movies à la Couchpotato
* [Sonarr](https://github.com/Sonarr/Sonarr): PVR for Usenet and BitTorrent users

## Backup

**[`^        back to top        ^`](#)**

* [BorgBackup](https://www.borgbackup.org/): Deduplicating archiver with compression and encryption

## Compression

**[`^        back to top        ^`](#)**

* [7-Zip](https://www.7-zip.org/): A file archiver with a high compression ratio
* [KGB Archiver](https://github.com/RandallFlagg/kgbarchiver): compression tool with unbelievable high compression rate
* [peazip](http://www.peazip.org/): File archiver utility
* [PIGZ](https://zlib.net/pigz/): Multi-threaded gzip
* [WinRAR](https://www.rarlab.com/download.htm): Can decompress RAR and zip files

## Network

**[`^        back to top        ^`](#)**

* [NetLimiter](https://www.netlimiter.com/): Internet traffic control and monitoring tool for Windows

## File systems

**[`^        back to top        ^`](#)**

* [httpdirfs](https://github.com/fangfufu/httpdirfs/):  A filesystem which allows you to mount HTTP directory listings
* [mergerfs](https://github.com/trapexit/mergerfs): a featureful union filesystem
* [NTFS drivers for MacOS](https://www.seagate.com/ca/en/support/downloads/item/ntfs-driver-for-mac-os-master-dl/)

## File conversion

**[`^        back to top        ^`](#)**

* [AAXtoMP3](https://github.com/KrumpetPirate/AAXtoMP3): convert AAX files to common MP3, M4A, M4B, flac and ogg formats through a basic bash script frontend to FFMPEG
* [html2warc](https://github.com/steffenfritz/html2warc): Convert web resources to a single warc file
* [warcat](https://github.com/chfoo/warcat): Tool and library for handling Web ARChive (WARC) files

## Utility Scripts

**[`^        back to top        ^`](#)**

* [Backblaze B2 sync backup script](https://gist.github.com/AlexanderProd/cb645cf858fd5c89780e7df267226b80): Script to sync mutliple directories with Backblaze B2
* [flac2mp3_V0.py ](https://gist.github.com/simon987/2a1dd3090a2ad0574c00e171670b1e0d): Multi-threaded python script to convert all flac files to mp3 V0 while keeping the directory structure
* [Misc download scripts](https://github.com/simon987/Misc-Download-Scripts): Scripts for downloading content from various websites
* [TheFrenchGhosty's Ultimate YouTube-DL Scripts Collection](https://github.com/TheFrenchGhosty/TheFrenchGhostys-Ultimate-YouTube-DL-Scripts-Collection): Collection of YouTube-dl scripts to aid in YouTube channel archival
* [rclone_dirsize](https://gist.github.com/simon987/7aff5ca3e9ae6c755055ca7b350ef9f8): Get size of http directory listing with rclone
* [rm_empty_subdir](https://gist.github.com/simon987/f5c2cd7602898615ac9bc8c762d9fe1d): Remove empty sub-directories on Windows
* [void-cat-uploader](https://github.com/takky1154/void-cat-uploader): This script automatically uploads all files inside a directory to https://void.cat
* [youtube-dl_soundcloud](https://gist.github.com/simon987/2dd7c57d65a741c93f5791bc984b97d1): Snippet for using YouTube-dl to download soundcloud playlists

## Content sharing

**[`^        back to top        ^`](#)**

* [h5ai](https://github.com/lrsjng/h5ai): HTTP web server index for Apache httpd, lighttpd, nginx and Cherokee
* [ipfs](https://ipfs.io/): Protocol and network designed to create a content-addressable, peer-to-peer method of storing and sharing hypermedia in a distributed file system
* [opds](https://opds.io/): Easy to use, Open & Decentralized Content Distribution
* [Syncthing](https://syncthing.net/): An application that lets you synchronize your files across multiple devices

## Data curation

**[`^        back to top        ^`](#)**

* [baobab](https://github.com/GNOME/baobab): Graphical disk usage analyzer
* [beets](https://github.com/beetbox/beets): Music library manager and MusicBrainz tagger
* [browsemonkey](https://github.com/shukriadams/browsemonkey): Takes snapshots of file systems for offline browsing and searching.
* [Calibre](https://github.com/kovidgoyal/calibre): Ebook manager
* [DataCurator-Filetree](https://github.com/roboyoshi/datacurator-filetree): A unified filetree for all kinds of data, which should help in storing, categorising and retrieving
* [DeepSort](https://github.com/CorentinB/DeepSort/): AI powered image tagger backed by DeepDetect
* [diskover](https://github.com/diskoverdata/diskover-community): File system crawler, disk space usage, file search engine and file system analytics powered by Elasticsearch
* [Everything](https://www.voidtools.com/): Locate files and folders by name instantly (Windows)
* [FileBot](https://www.filebot.net/): FileBot is the ultimate tool for organizing and renaming your Movies, TV Shows and Anime
* [fucking-weeb](https://github.com/cosarara/fucking-weeb): A library manager for animu (and TV shows, and whatever).
* [grepWin](https://github.com/stefankueng/grepWin): A powerful and fast search tool using regular expressions (Windows)
* [Hydrus](https://github.com/hydrusnetwork/hydrus): A desktop application for large media collections
* [Kiwix](https://www.kiwix.org): An offline reader for online content like Wikipedia, Project Gutenberg, or TED Talks
* [jdupes](https://github.com/jbruchon/jdupes): Powerful duplicate file finder
* [MediaElch](https://github.com/komet/mediaelch): Media manager for Kodi
* [MediaInfo](https://github.com/MediaArea/MediaInfo): Convenient unified display of the most relevant technical and tag data for video and audio files
* [Mp3tag](https://www.mp3tag.de): Powerful and easy-to-use tool to edit metadata of audio files (Windows/Mac)
* [phockup](https://github.com/ivandokov/phockup): Media sorting tool to organize photos and videos from your camera
* [picard](https://github.com/metabrainz/picard): MusicBrainz tagger
* [TeraCopy](https://www.codesector.com/downloads): Copy your files faster and more securely
* [tree](http://mama.indstate.edu/users/ice/tree/): 'tree' command for linux
* [WinDirStat](https://windirstat.net/): Disk usage statistics viewer and cleanup tool for Windows
* [WizTree](https://antibody-software.com/web/software/software/wiztree-finds-the-files-and-folders-using-the-most-disk-space-on-your-hard-drive/): Finds the files and folders using the most disk space on your hard drive
* [sist2](https://github.com/simon987/sist2/): Lightning-fast file system indexer and search tool
* [SyncToy](https://www.microsoft.com/en-us/download/details.aspx?id=15155): Microsoft windows file parity across locations tool
* [VisiPics](http://www.visipics.info/index.php?title=Main_Page): Automatically finds duplicated images

## APIs & Online tools

**[`^        back to top        ^`](#)**

* [iqdb](https://iqdb.org/): Multi-service reverse image search
* [thetvdb](https://www.thetvdb.com/): TV shows metadata (used by plex)

## Hardware / Monitoring

**[`^        back to top        ^`](#)**

* [CrystalDiskInfo](https://crystalmark.info/en/software/crystaldiskinfo/): A HDD/SSD utility software which supports a part of USB, Intel RAID and NVMe
* [GSmartControl](https://gsmartcontrol.shaduri.dev/): Easy to use Multi-OS S.M.A.R.T. utility with an easy to understand graphical interface
* [Hard Drive Sentinel](https://www.hdsentinel.com/): Multi-OS SSD and HDD monitoring and analysis software
* [smartmontools](https://www.smartmontools.org/): Control and monitor storage systems using the (SMART) built into most modern ATA/SATA, SCSI/SAS and NVMe disks

## Data recovery

**[`^        back to top        ^`](#)**

* [PhotoRec](https://www.cgsecurity.org/wiki/PhotoRec) FOSS powerful gui data recovery tool
* [TestDisk](https://www.cgsecurity.org/wiki/TestDisk_Download) Another FOSS tool by the author of PhotoRec, but this one is for cli

## Local Media

**[`^        back to top        ^`](#)**

* [whipper](https://github.com/whipper-team/whipper): Python CD-DA ripper preferring accuracy over speed. Generates .flac, .cue, and .log by default and automatically fetches metadata from musicbrainz. EAC log plugin is available.
* [Exact Audio Copy](http://www.exactaudiocopy.de/): A freeware, Windows only application similar to the above that doesn't automatically fetch metadata by default, but EAC rips are preferred by most trackers
* [MakeMKV](https://www.makemkv.com/): A cross-platform DVD ripper that supports recent blu ray DVDs. It's mostly open source, but the blu ray secret sauce is still hidden
* [Handbrake](https://handbrake.fr/): Open source DVD ripper and media trascoder. Has more options and features than the above, but it cannot rip blu ray discs

## Long-term data archiving

**[`^        back to top        ^`](#)**

* [CommonCrawl](http://commoncrawl.org/the-data/get-started/): Data collected over seven years (ongoing) which contains web page data, extracted metadata and text extractions.
* [Blockyarchive](https://github.com/darrenldl/blockyarchive): Archive with forward error correction and sector level recoverability
* [par2cmdline](https://github.com/Parchive/par2cmdline): A PAR 2.0 compatible file verification and repair tool
