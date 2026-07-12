# WikiRadio
> Stream audio files from Wikimedia Commons

*Last updated 12 July 2026* 

## Introduction

This is a simple, browser-based application to stream random audio files from [Wikimedia Commons](https://commons.wikimedia.org/wiki/Main_Page). Remember, always provide attribution to the files you use if the license requires it!

## Instructions
* Click "Tune in" to start listening.
* "Prev" will play the last file while "Skip" will play the next file in the queue.
* Toggle the "Loop" button to repeat or stop repeating a track.
* "Pop out" will pop out a tiny streaming window with basic track information.
* Control volume with the 🔊 audio slider.
* Click the color palette icon (🎨) to randomize the page's color scheme.
* Click the paintbrush icon (🖌️) to customize the page's color scheme.

## Features
* The current file being played shows metadata info from Wikimedia Commons, including the Title, Author, English Description, Date, Attribution info, a link to the file on Wikimedia Commons, and the file's associated Categories.
* The "Session History" window shows a record of files played with a link to the file on Wikimedia Commons and the track duration. Click the title of the track to replay it.
* How it works: the app fetches 50 random audio files via the Wikimedia search API. It then removes any duplicate files and fetches file metadata, discarding files that are less than 1 minute in duration (this increases the odds of it being a song or something like a song and hopefully excludes short audio clips that aren't exactly musical). It verifies this queue and makes sure there are always 5 files ready to be played.

## Miscellaneous
This is a free tool created by **Robin Isadora Brown** as [part of her work](https://meta.wikimedia.org/wiki/Trans_Music_Archive) with [Trans Music Archive](https://www.transmusicarchive.org/). If you have any questions, please visit her [Wikipedia User page](https://en.wikipedia.org/wiki/User:RobinIsadorable).

[Vibe-coded](https://www.wikidata.org/wiki/Q133150082) with Anthropic's [Claude AI](https://www.wikidata.org/wiki/Q118876059).

## License
[GPL-3.0 license](https://github.com/RobinBBiosci/WikiRadio/blob/main/LICENSE) for code

The Robin logo is copyrighted. I retain all rights to it and its derivations.
