# AudiobookHub
Software resources for audiobook management. Especially Audible-centric, including organization and removing DRM from Audible files

## Guides
* https://github.com/seanap/Plex-Audiobook-Guide: Plex & Booksonic Audiobook Guide. Put your audiobooks in Plex then use Prologue or BookCamp to stream your whole library. You can even share with your friends and family
* http://checkthebenchmarks.com/2019/09/23/why-you-should-manage-your-own-audible-library/: Manage your own Audible library

## Audible APIs

Interfaces for internal Audible API

* https://github.com/omarroth/audible.cr: written in Crystal
* https://github.com/mkb79/Audible: written in Python
* https://github.com/rmcrackan/AudibleApi: written in C#

## Backup, decrypt, convert, organize

* [Libation](https://github.com/rmcrackan/Libation): audible audiobook manager. Download, decrypt, organize, search, and tag. Open-source. Windows only
* [inAudible](https://github.com/rmcrackan/inAudible): remove Audible DRM, edit files, and convert files. Installers available
* [AAX Audio Converter](https://github.com/audiamus/AaxAudioConverter): Convert Audible aax files to mp3 and m4a
* [OpenAudible](https://openaudible.org/): cross-platform audible audiobook manager ($12 shareware)
* [OSAC](https://github.com/adrifcastr/OSAC): Open Source Audible Converter. Convert audible's proprietary AAX audio files to MP3, AAC/M4B, or FLAC
* [AAXtoMP3](https://github.com/KrumpetPirate/AAXtoMP3): Convert Audible's .aax filetype to MP3, FLAC, M4A, or OPUS

## Scripts to make audible's site more usable

* [Audible Statistics Extractor](https://www.themodernnomad.com/audible-statistics-extractor/): script to export your Audible library to a spreadsheet
* [Audible Special Promo Sale Scraper](https://github.com/joonaspaakko/audible-special-promo-sale-scraper): generate a list of sale items
* [Audible Library Extractor browser extension](https://github.com/joonaspaakko/audible-library-extractor/): automatically generates a searchable gallery by scanning your audible library. If you upload the gallery online, you can share it with others
* [Audible library cover downloader](https://github.com/joonaspaakko/audible-library-cover-downloader): downloads all covers in your Audible library and generates a screensaver web page
* [audible wishlist scraper](https://github.com/joonaspaakko/audible-wishlist-scraper): Fetches your wishlist and outputs it as: html, markdown, plaintext, json, csv

## DRM Removal

Behind the scenes, most if not all resources below use these for their heavy lifting (although they aren't the easiest to use directly)

* [FFmpeg](https://ffmpeg.org/ffmpeg-all.html#Audible-AAX): A complete, cross-platform solution to record, convert and stream audio and video. Includes the ability to use your activation data to strip DRM from .aax files
* [audible-activator](https://github.com/inAudible-NG/audible-activator): Retrieves your activation data (activation_bytes) from Audible servers
* [audible-tools.github.io](https://audible-tools.github.io): free service which resolves audible activation bytes. [Nuget pkg](https://www.nuget.org/packages/Aax.Activation.ApiClient/1.0.0). [How to use](https://github.com/JKamsker/OSAC/blob/master/OSAC/MainWindow.xaml.cs#L172)
