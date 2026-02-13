# AudiobookHub
Software resources for audiobook management. Especially Audible-centric, including organization and removing DRM from Audible files

## Guides
* https://github.com/seanap/Plex-Audiobook-Guide: Plex & Booksonic Audiobook Guide. Put your audiobooks in Plex then use Prologue or BookCamp to stream your whole library. You can even share with your friends and family
* https://web.archive.org/web/20221012164516/http://checkthebenchmarks.com/2019/09/23/why-you-should-manage-your-own-audible-library/: Manage your own Audible library (note: do not visit the original domain, it has since been highjacked)

## Non-audible

* https://github.com/subdavis/kobo-book-downloader: Remove DRM and download from Kobo

## Audible APIs

Interfaces for internal Audible API

* https://github.com/mkb79/Audible: A(Sync) Interface for internal Audible API written in pure Python
* https://github.com/rmcrackan/AudibleApi: written in C#. Used internally by Libation (below)
* https://github.com/Mbucari/AAXClean: C# library for working with AAXC files without ffmpeg

## Listening

* iOS: [BookPlayer](https://apps.apple.com/us/app/bookplayer/id1138219998)
* iOS: [Bound](https://apps.apple.com/us/app/bound-audiobook-player/id1041727137)
* Android: [Smart AudioBook Player](https://play.google.com/store/apps/details?id=ak.alizandro.smartaudiobookplayer&hl=en_US&gl=US)
* Android: [Listen](https://play.google.com/store/apps/details?id=ru.litres.android.audio&hl=en_US&gl=US)
* Android: [Voice Audiobook Player](https://f-droid.org/en/packages/de.ph1b.audiobook/) -- minimal audiobook player
* Android [Libre Librivox listener](https://f-droid.org/en/packages/io.gitlab.libre_librivox_listener/) -- An unofficial libre application to listen to public domain audiobooks
* Desktop: [VLC](https://www.videolan.org/)
* Windows Desktop: [Audibly](https://github.com/rstewa/Audibly) -- a desktop player build specifically for audiobooks
* Guide to DRM-Free Living. Audiobooks is about 2/3 down: https://www.defectivebydesign.org/guide/ebooks

Self-hosting online:

* [audiobookshelf](https://www.audiobookshelf.org). On [reddit](https://www.reddit.com/r/audiobookshelf/). Listen with [ShelfPlayer](https://github.com/rasmuslos/ShelfPlayer) (iOS)
* [plex](https://www.plex.tv/). Listen with [Prologue](https://prologue.audio/) (iOS)

## Backup, decrypt, convert, organize

* [Libation](https://github.com/rmcrackan/Libation): audible audiobook manager. Download, decrypt, organize, search, and tag. Free. Open-source. Windows, Mac, and Linux. GUI and CLI.
* [inAudible](https://github.com/rmcrackan/inAudible): remove Audible DRM, edit files, and convert files. Installers available
* [LibriSync](https://github.com/Promises/LibriSync) -- Libation port for Android
* [Book Lib Connect](https://github.com/audiamus/BookLibConnect): A standalone Audible downloader and decrypter
* [AAX Audio Converter](https://github.com/audiamus/AaxAudioConverter): Convert Audible aax files to mp3 and m4a/m4b
* [OpenAudible](https://openaudible.org/): cross-platform audible audiobook manager (~~free~~, ~~$12~~, ~~$18.95 shareware~~, ~~$18.95~~, ~~$18.95 per year~~, ~~$19.95 per year or $49.99 for lifetime~~, $21.95 per year and another $69.95 for lifetime)
* [Audible Plus Converter](https://www.z3kit.com/audorplus/): Windows, Mac. $15/quarter, $30/yr, or $60 lifetime
* [OSAC](https://github.com/adrifcastr/OSAC): Open Source Audible Converter. Convert audible's proprietary AAX audio files to MP3, AAC/M4B, or FLAC
* [AAXtoMP3](https://github.com/KrumpetPirate/AAXtoMP3): Convert Audible's .aax filetype to MP3, FLAC, M4A, or OPUS
* [Audible-CLI](https://github.com/mkb79/audible-cli): A command line interface for the above audible Python API

## Scripts to make audible's site more usable

* [Audible Statistics Extractor](https://www.themodernnomad.com/audible-statistics-extractor/): script to export your Audible library to a spreadsheet
* [Audible Special Promo Sale Scraper](https://github.com/joonaspaakko/audible-special-promo-sale-scraper): generate a list of sale items
* [Audible Library Extractor browser extension](https://github.com/joonaspaakko/audible-library-extractor/): automatically generates a searchable gallery by scanning your audible library. If you upload the gallery online, you can share it with others
* [Audible library cover downloader](https://github.com/joonaspaakko/audible-library-cover-downloader): downloads all covers in your Audible library and generates a screensaver web page
* [audible wishlist scraper](https://github.com/joonaspaakko/audible-wishlist-scraper): Fetches your wishlist and outputs it as: html, markdown, plaintext, json, csv

uBlock Origin (ad blocker), custom filter to remove "Virtual Voice" titles:

`www.audible.com##li.productListItem.bc-list-item:has-text('Virtual Voice')`

## Browser entensions

* [Audible Series Follower](https://chrome.google.com/webstore/detail/audible-series-follower/ginemimjkldnbpgllnjnfkggfjckiekm): A chrome extension to allow you to follow series you like on Audible

## DRM Removal

Behind the scenes, most if not all resources below use these for their heavy lifting (although they aren't the easiest to use directly)

* [FFmpeg](https://ffmpeg.org/ffmpeg-all.html#Audible-AAX): A complete, cross-platform solution to record, convert and stream audio and video. Includes the ability to use your activation data to strip DRM from .aax files
* [audible-activator](https://github.com/inAudible-NG/audible-activator): Retrieves your activation data (activation_bytes) from Audible servers
* [audible-tools.github.io](https://audible-tools.github.io): free service which resolves audible activation bytes. [Nuget pkg](https://www.nuget.org/packages/Aax.Activation.ApiClient/1.0.0). [How to use](https://github.com/JKamsker/OSAC/blob/master/OSAC/MainWindow.xaml.cs#L172)

## File editing and manipulation
[AudioBookConverter](https://www.recoupler.com/products/audiobookconverter) ([Code on github](https://github.com/yermak/AudioBookConverter)): convert. Also advanced chapter support for combining and splitting
