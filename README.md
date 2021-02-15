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

* [Libation][libation]: audible audiobook manager. Download, decrypt, organize, search, and tag. Open-source. Windows only
* [inAudible][inaudible]: remove Audible DRM, edit files, and convert files. Installers available
* [AAX Audio Converter][aaxaudioconverter]: Convert Audible aax files to mp3 and m4a
* [OpenAudible][openaudible]: cross-platform audible audiobook manager ($12 shareware)
* [OSAC][osac]: Open Source Audible Converter. Convert audible's proprietary AAX audio files to MP3, AAC/M4B, or FLAC
* [AAXtoMP3][aaxtomp3]: Convert Audible's .aax filetype to MP3, FLAC, M4A, or OPUS

## Scripts to make audible's site more usable

* [Audible Statistics Extractor][audibleStatisticsExtractor]: script to export your Audible library to a spreadsheet
* [Audible Special Promo Sale Scraper][audibleSpecialPromoSaleScraper]: generate a list of sale items

## DRM Removal

Behind the scenes, most if not all resources below use these for their heavy lifting (although they aren't the easiest to use directly)

* [FFmpeg][ffmpeg]: A complete, cross-platform solution to record, convert and stream audio and video. Includes the ability to use your activation data to strip DRM from .aax files
* [audible-activator][audibleActivator]: Retrieves your activation data (activation_bytes) from Audible servers
* [audible-tools.github.io][activationBytesLib]: free service which resolves audible activation bytes. [Nuget pkg][activationBytesLibNuget]. [How to use][activationBytesLibHowToUse]

  [libation]: https://github.com/rmcrackan/Libation
  [inaudible]: https://github.com/rmcrackan/inAudible
  [aaxaudioconverter]: https://github.com/audiamus/AaxAudioConverter
  [openaudible]: https://openaudible.org/
  [osac]: https://github.com/adrifcastr/OSAC
  [aaxtomp3]: https://github.com/KrumpetPirate/AAXtoMP3
  [audibleStatisticsExtractor]: https://www.themodernnomad.com/audible-statistics-extractor/
  [audibleSpecialPromoSaleScraper]: https://github.com/joonaspaakko/audible-special-promo-sale-scraper

  [ffmpeg]: https://ffmpeg.org/ffmpeg-all.html#Audible-AAX
  [audibleActivator]: https://github.com/inAudible-NG/audible-activator
  [activationBytesLib]: https://audible-tools.github.io
  [activationBytesLibNuget]: https://www.nuget.org/packages/Aax.Activation.ApiClient/1.0.0
  [activationBytesLibHowToUse]: https://github.com/JKamsker/OSAC/blob/master/OSAC/MainWindow.xaml.cs#L172
