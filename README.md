# AudiobookHub
Software resources for improving audiobook management

## DRM Removal

Behind the scenes, most if not all resources below use these for their heavy lifting (although they aren't the easiest to use directly)

* [audible-activator][audibleActivator]: Retrieves your activation data (activation_bytes) from Audible servers
* [FFmpeg][ffmpeg]: A complete, cross-platform solution to record, convert and stream audio and video. Includes the ability to use your activation data to strip DRM from .aax files

## Resources

* [inAudible][inaudible]: remove Audible DRM, edit files, and convert files. Source code and installers available
* OpenAudible -- [website][openaudibleWebsite] -- [source code][openaudibleGit]: open-source cross-platform audible audiobook manager
* [Audible API][audibleApi]: WIP interface for internal Audible API
* [OSAC][osac]: Open Source Audible Converter. Convert audible's proprietary AAX audio files to MP3, AAC/M4B, or FLAC
* [AAXtoMP3][aaxtomp3]: Convert Audible's .aax filetype to MP3, FLAC, M4A, or OPUS

  [audibleActivator]: https://github.com/inAudible-NG/audible-activator
  [ffmpeg]: https://ffmpeg.org/ffmpeg-all.html#Audible-AAX
  
  [inaudible]: https://github.com/rmcrackan/inAudible
  [openaudibleWebsite]: https://openaudible.org/
  [openaudibleGit]: https://github.com/openaudible/openaudible
  [audibleApi]: https://github.com/omarroth/audible.cr
  [osac]: https://github.com/adrifcastr/OSAC
  [aaxtomp3]: https://github.com/KrumpetPirate/AAXtoMP3
