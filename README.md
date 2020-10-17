# Forked From FoundryVTT-Drag-Upload by Cody Swendrowski <cody@swendrowski.us>

![](https://img.shields.io/badge/Foundry-v0.7.2-informational)
[![](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-%243-orange)](https://www.buymeacoffee.com/T2tZvWJ)

# Drag Upload (Get Over Here!)

## WARNING - Drag Upload will NOT work if you run Foundry in Admin mode on Windows due to a Windows security feature!

Adds the ability to drag files onto the Foundry canvas to automatically create Tokens, Tiles, Journal Pins, and Ambient Audio

![](./dragupload.gif)

If the file is an audio file (.mp3, .mp4, .wav, .flac), it will be created as an Ambient Audio with easing.

Otherwise, it will be treated as an Image and created based on the current active layer:

* Token: 1x1 Actor with Token
* Tile: Tile of the same size as the image
* Notes: Journal with a corresponding Journal Pin
* Other: Same as Token


## Changelog

### v1.0.0
Initial release with support for uploading to S3 instead of the local file system
