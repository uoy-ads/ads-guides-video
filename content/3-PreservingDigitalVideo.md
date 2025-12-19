---
authors:
  - name: null
---

# 3 Preserving Digital Video

## 3.1 Deciding What to Archive

Selecting what to archive depends heavily on how the video was created. As discussed in the opening sections, many digital devices are limited in terms of the quality and type of video that they can produce and so it is essential that the capabilities of the device are assessed against the requirements of the project. Ideally digital video should be captured at a quality suitable for archiving - i.e. the original would be stored - and then lower quality files derived from this 'master'. Although creating and storing completely uncompressed video may not be an option for many, it is essential that a suitable format is chosen as once files are converted between formats (transcoded) then there is no ability to recover or improve data from low quality formats. The significant properties identified below highlight the aspects that should be maintained if moving data between formats.

## 3.2 Deciding How to Archive

__Significant properties__

The significant properties of video files are discussed in detail in the JISC report 'The Significant Properties of Moving Images' [@coyne2008significant] as well as in the AHDS preservation handbook for moving images [@knight2005moving]. To summarise, the properties of digital video files that should remain unchanged when preserving or storing data are:
* the length and size of the file (e.g. 5min 31secs / 150MB)
* the frame rate in frames per second (e.g. 25 for PAL or 30 for NTSC)
* the frame size / video resolution (e.g. 720 x 576 pixels)
* the bit-rate (in kbps)
* audio bit-rate (kbps)
* audio frequency (kHz)
* audio channels used (e.g. stereo)
* associated metadata and documentation, and file size.

Prior to conversion it is advisable to check the video file against any documentation provided to ensure that the file is the specified length (minutes and seconds) and that its significant properties are correctly documented. This ensures that the file is complete and that it will no suffer any unplanned degradation while undergoing any planned file conversion. 

The actual process of transcoding digital video - i.e. migrating data from one digital format to another - is described in detail on the JISC Digital Media site.

__File Formats__

The formats described in the table below are recommended for the long-term preservation of digital video:

```{list-table}
:header-rows: 1

* - Format
  - Requirements
* - MPEG 1 (.mpg,.mpeg)
  - A published open standard ISO/IEC standard (11172) suitable for preservation and dissemination.
* - MPEG 2 (.mpg,.mpeg)
  - As with MPEG-1, a published open standard (ISO/IEC (13818)) particularly suitable for preservation.
* - MPEG 4 (.mp4)
  - A published open standard ISO/IEC 14496-14:2003 suitable for data preservation and dissemination although a higher quality MPEG format should be used where appropriate.
```

Motion JPEG 2000, as discussed in detail by @pearson2005evaluation may also provide a useful preservation format for digital video, especially in the case of digitisation projects, though research into the suitability of the format is still currently ongoing.

## 3.3 Metadata and Documentation

As with other data formats, metadata for digital video provides key information on how the data has been created. In addition to generic project level metadata (as discussed in the [Project Metadata](https://doi.org/10.5284/h0p2-5584) section), specialised metadata should be recorded for digital video so that the nature of the file can be understood. It is key in this instance to notice that the core specialised metadata presented here ties in with the significant properties described above.

__Specialised metadata__

```{list-table}
:header-rows: 1

* - Element
  - Description
* - Software, version and platform
  - The software (or hardware if taken directly from a device) used to create the video.
* - Video Codec
  - The name and version of video codec (where appropriate).
* - Video Dimension
  - The video dimension (in pixels).
* - Frame Rate
  - Frame rate per second (fps).
* - Bit rate
  - The video bit rate.
* - Audio Codec
  - Name and version of audio codec.
* - Audio Sample Frequency
  -
* - Audio Bit-rate
  - 
* - Audio Channels
  - Channels used e.g. Stereo
* - Length
  - Length (hours, minutes, seconds) of file
* - File Size
  - Size of the file in MB
```
----

