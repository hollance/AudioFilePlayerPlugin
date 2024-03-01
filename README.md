# AudioFilePlayer

A port of the JUCE AudioFilePlayerDemo into plug-in format.

This is based on [Matkat Music's version](https://github.com/matkatmusic/AudioFilePlayer) with the following differences:

- The loaded audio file will always loop.
- It does not use JUCE as a submodule.
- Added a Visual Studio 2022 exporter.
- Enabled the JUCE splash screen for users who didn't put Projucer in GPLv3 mode.
