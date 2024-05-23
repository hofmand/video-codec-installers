# video-codec-installers

A modern pair of MS-Windows installers (x86/x64) for the HuffYUV lossless video codec (fourcc code **HFYU**) version 2.1.1, replacing the `.inf` install script and complicated installation instructions for recent versions of Windows.

## Installation

To install:

1. Download the `.msi` file that matches your VirtualDub ('x86' or 'x64') from [releases](https://github.com/hofmand/video-codec-installers/releases).
2. Press the Windows key, type `cmd`, find the "Command Prompt" or "cmd.exe" App, and click "Run As Administrator". *You may need to right click on "Command Prompt" or "cmd.exe" to find "Run As Administrator".*
3. In the command prompt, switch to the directory where you downloaded the `.msi` file, then type in the name of the `.msi` file to run it. For example:
```
cd C:\Users\hofmand\Downloads
HuffYUV_x86_v2_1_1.msi
```

If it says, "Microsoft Defender SmartScreen prevented an unrecognized app from starting.", click on "More info" and then "Run anyway".

## Development

This was developed in [WiX Toolset v3](https://wixtoolset.org/docs/wix3/) and Microsoft Visual Studio 2019 with the WiX v3 Visual Studio Extension. The "Prebuild" project requires [7-zip](https://www.7-zip.org/) to unpack the HuffYUV archive files.

The installers were tested on Windows 10 Enteprise 64-bit and Windows XP 32-bit.

The HuffYUV binaries were downloaded from [VideoHelp](https://www.videohelp.com/software/HuffYUV).

## See Also

Similar lossless video codecs you might be interested in include:

* HuffYUV multithreaded (**HYMT**).
* FFV1, bundled in [FFDShow](https://www.videohelp.com/software/ffdshow) which I think also includes **UYFH**, **HVFF**, and/or **FFVH** codecs.
* [Lagarith](https://www.videohelp.com/software/Lagarith-Lossless-Video-Codec).
* [UT Video Codec Suite](https://www.videohelp.com/software/Ut-Video-Codec-Suite).
