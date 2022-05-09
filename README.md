# video-codec-installers

A modern pair of MS-Windows installers (x86/x64) for the HuffYUV lossless video codec (fourcc code **HFYU**) version 2.1.1, replacing the `.inf` install script and complicated installation instructions for recent versions of Windows. Just click to install.

This was developed in [WiX Toolset v3](https://wixtoolset.org/) and Microsoft Visual Studio 2015. The "Prebuild" project requires [7-zip](https://www.7-zip.org/) to unpack the HuffYUV archive files.

The installers were tested on Windows 10 Enteprise 64-bit and Windows XP 32-bit.

The HuffYUV binaries were downloaded from [this post at DigitalFAQ.com](http://www.digitalfaq.com/forum/video-conversion/1727-virtualdub-filters-pre.html).

Similar lossless video codecs you might be interested in include:

* HuffYUV multithreaded (**HYMT**).
* FFV1, bundled in [FFDShow](https://www.videohelp.com/software/ffdshow) which I think also includes **UYFH**, **HVFF**, and/or **FFVH** codecs.
* [Lagarith](https://www.videohelp.com/software/Lagarith-Lossless-Video-Codec).
* [UT Video Codec Suite](https://www.videohelp.com/software/Ut-Video-Codec-Suite).
