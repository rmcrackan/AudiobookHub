# AudiobookHub
Software resources for audiobook management. Especially organization and removing DRM from Audible files

## DRM Removal

Behind the scenes, most if not all resources below use these for their heavy lifting (although they aren't the easiest to use directly)

* [audible-activator][audibleActivator]: Retrieves your activation data (activation_bytes) from Audible servers
* [FFmpeg][ffmpeg]: A complete, cross-platform solution to record, convert and stream audio and video. Includes the ability to use your activation data to strip DRM from .aax files

## Audible APIs

Interfaces for internal Audible API

* https://github.com/omarroth/audible.cr: written in Crystal
* https://github.com/mkb79/Audible: written in Python
* https://github.com/rmcrackan/AudibleApi: written in C#

## Resources

* [inAudible][inaudible]: remove Audible DRM, edit files, and convert files. Installers available
* [AAX Audio Converter][aaxaudioconverter]: Convert Audible aax files to mp3 and m4a
* OpenAudible -- [website][openaudibleWebsite] -- [source code][openaudibleGit]: open-source cross-platform audible audiobook manager
* [Libation][libation]: audible audiobook manager. Download, decrypt, organize, search, and tag. Open-source. Windows only
* [OSAC][osac]: Open Source Audible Converter. Convert audible's proprietary AAX audio files to MP3, AAC/M4B, or FLAC
* [AAXtoMP3][aaxtomp3]: Convert Audible's .aax filetype to MP3, FLAC, M4A, or OPUS

  [audibleActivator]: https://github.com/inAudible-NG/audible-activator
  [ffmpeg]: https://ffmpeg.org/ffmpeg-all.html#Audible-AAX

  [inaudible]: https://github.com/rmcrackan/inAudible
  [aaxaudioconverter]: https://github.com/audiamus/AaxAudioConverter
  [libation]: https://github.com/rmcrackan/Libation
  [openaudibleWebsite]: https://openaudible.org/
  [openaudibleGit]: https://github.com/openaudible/openaudible
  [osac]: https://github.com/adrifcastr/OSAC
  [aaxtomp3]: https://github.com/KrumpetPirate/AAXtoMP3
