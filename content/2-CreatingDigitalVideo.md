---
authors:
  - name: null
---

# 2 Creating Digital Video

## 2.1 General Considerations

A detailed 'Introduction to Digital Video', covering its creation and storage has been created by JISC Digital Media. This guide aims to draw upon the main points of this - and other - documents but the user is referred to the JISC Digital Media guide for further detail. In general, this guide aims to provide an overview of desktop video files (i.e. video that exists as a file either on the capture device or on a computer) and does not aim to cover either the digitisation of analogue materials or transfer of digital tape or disc/DVD-based video to desktop formats. As with other data types covered in these Guides, it is assumed that data is best preserved on network-based storage rather than on physical media such as DVD discs and tapes.

As mentioned in the previous section, the sources of data/digital video can often determine the format, quality and final physical size of the video files. When digitising from analogue sources, a range of formats are open to the creator in addition to a number of considerations determining the quality and size of the final file. The digitisation of analogue materials are outlined in detail in the JISC Digital Media documents 'Selecting a video digitisation system' and 'Equipping a video digitisation system'. When creating video files from other datasets (e.g. a 'fly-through' of a 3D model), similar considerations exist as those that apply to digitisation although final file formats and quality are likely to be limited by the software application used.

__Containers and Codecs__

As with [Digital Images](https://doi.org/10.5284/mtgj-7130) and [Digital Audio](https://doi.org/10.5284/40fr-fr91) files, digital video files contain a range of significant properties (discussed in the next section) that determine the quality and size of the video file. Many of these properties are also directly related to the capabilities of the various file formats used for digital video. However, unlike other file formats, many widely used digital video formats are in fact 'wrapper' or container formats that simply encapsulate separate video and audio streams. These separate streams can in turn also be present in a number of differing formats (described in terms of the codec used to encode them) and it is therefore of great importance that the data creator is aware of the exact codecs being used, their capabilities and intended use. The wrapper format itself can also vary in terms of capabilities with certain formats e.g MPEG limiting the types of codecs used within the wrapper for each of the streams.

In general, data creators should be aware of the use of:
* Compression, for both video and audio streams. As with various other formats, lossy compression results in the loss of data. It is recommended that no compression (or lossless where possible) is used for the original video file as this will provide a high quality 'master' from which other files can be derived..
* Frame Size / Pixels per Frame describes the physical width and length of the video picture and can therefore, as with image resolution, determine the level of detail captured in the file.
* Frame Rate describes the number of frames per second captured/displayed by the file. A higher frame rate creates a smoother video but also a larger file.
* Bit Rates, for both audio and video streams. Bit rates are derived from a combination of frame size, bits per frame, and frame rate and often appear as as a preset option in many digital video applications. In addition to constant standard presets, many applications give the option of variable bitrates which allow the video file to adjust these rate depending on the complexity of the frames.

The table below outlines a number of the common codec and container formats used for digital video files, more detailed comparisons of the capabilities of these can be found in the Wikipedia [codec](http://en.wikipedia.org/wiki/Comparison_of_video_codecs) and [container format](http://en.wikipedia.org/wiki/Comparison_of_container_formats) comparison tables.

## 2.2 File Formats

```{list-table}
:header-rows: 1

* - Format
  - Properties/Technologies
  - Description
  - Recommendations
* - MPEG 1 (.mpg, .mpeg)
  - A published open standard binary format for video and audio
  - An [International ISO/IEC standard (11172)](https://www.iso.org/standard/22411.html) developed by the Moving Picture Experts Group (MPEG) for Video CD (VCD and SVCD) and less commonly DVD-Video. Provides reasonable quality audio/video playback comparable to VHS tape. The MPEG-1 Audio Layer III equates to MP3 audio. Many tools, including open source tools, exist for working with this format.
  - Suitable for preservation and dissemination.
* - MPEG 2 (.mpg, .mpeg)
  - A published open standard
  - As with MPEG-1, an [ISO/IEC (13818)](https://www.iso.org/standard/91403.html) standard but for DVD and Digital Television. It includes a number of differing 'profiles' (the Simple Profile, Main Profile and 4:2:2 Profile (as used for Digital TV)), all of which contain different standard specifications for elements such as display size and data rate. MPEG-2 video is not optimized for low bit-rates (i.e. less than 1 Mbit/s) but does provide superior quality when compared to MPEG-1 at rates above 3 Mbit/s
  - Particularly suitable for preservation.
* - MPEG 4 (.mp4)
  - A published open standard ISO/IEC 14496-14:2003
  - The newest of the MPEG ISO/IEC (14496) standards and concerned with 'web (streaming media), conversation (videophone), and broadcast television, all of which benefit from compressing the AV stream. Based partly on Apple's QuickTime .mov format, MPEG4 has at its core audio and video but also supports 3D objects, text, sprites and other media types to allow interactive elements to be included. As with MPEG2, MPEG4 includes two main versions and vast number of 'profiles' optimised for different purposes. The format is steadily growing in popularity and is fully outlined on the [NDIIPP formats page](https://www.loc.gov/preservation/digital/formats/fdd/fdd000155.shtml)
  - MPEG 4 is suitable for data preservation and dissemination although a higher quality MPEG format should be used where appropriate.
* - DivX (.divx, .avi)
  - Proprietary and popular video codec
  - The DivX format is another implementation of MPEG-4 and is widely used for distributing movies over the Internet. The format from version 4 onwards (also known as OpenDivX) is used under licence but was initially based on an illegal 'hacked' version of the Microsoft .wmv implementation of MPEG4 (the previous illegal version is often referred to as 'DivX ;-)' i.e. with a smiley). The DivX codec is free to download but requires a licence to encode.
  - Suitable for dissemination but not suited for preservation.
* - Xvid (.avi, .xvid)
  - GNU GPL licensed codec based on MPEG-4 and a further development of OpenDivX
  - Xvid, like DivX, is based on MPEG-4 Part 2 Advanced Simple Profile (ASP)
  - Suitable for dissemination but not suited for preservation.
* - Motion JPEG 2000 (.mj2, .mjp2)
  - An [ISO/IEC 15444-3 standard](https://www.loc.gov/preservation/digital/formats/fdd/fdd000127.shtml) container format using JPG2000 encoding
  - Capable of storing both lossy and lossless video, the Motion JPEG 2000 format stores video as a series of individual images and has thus sparked interest in digital preservation circles, particularly in regard to film digitisation.
  - Suitable for dissemination and particularly for preservation.
* - Matroska (.mkv)
  - [A proprietary though open source container format](http://www.matroska.org/)
  - A highly flexible conrainer format, Matroska aim to be "the opensource alternative to existing containers such as AVI, ASF, MOV, RM, MP4, MPG ES". As a result, the format supports a virtually unlimirted number of codecs.
  - Suitable for dissemination and preservation depending on codecs used.
* - Flash Video (.flv)
  - Popular proprietary container format (e.g. YouTube)
  - The FLV format, developed by Macromedia then Adobe, is a popular format for web delivery of compressed video. The format contains limited support for codecs.
  - Suitable for dissemination.
* - Audio Video Interleave (.avi)
  - A proprietary but popular container format developed by Microsoft
  - AVI is a well supported container format that supports a wide range of codecs although certain limitations (e.g. variable bit rate support) are evident due to the age of the original specifiaction.
  - Suitable for dissemination.
* - Quicktime (.mov)
  - A proprietary container format developed by Apple
  - As stated above, the Quicktime format provided the basis for the MPEG-4 standard. Although the Quicktime format provides similar (or greater functionality) in some instances, it is recommeded that MPEG-4 is used instead where possible as an established standard.
  - Suitable for dissemination.
```

__Future directions__

Aside from the ongoing development of MPEG and DivX formats the Material Exchange Format (.mxf) format, an open standard developed by the Society of Motion Picture and Television Engineers (SMPTE) may soon become a preferred preservation container format for moving images / video [see @wright2011audiovisual, 13].