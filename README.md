# Partitura

Find your part in the music. Partitura is a native Mac app that separates a recording into instruments and creates editable transcription drafts for practice.

This public repository contains the download website and packaged Mac releases. Application source is maintained separately.

## Download for Mac

Get the ZIP from [the latest release](https://github.com/iamjason/partitura-site/releases/latest), unzip it, and move **Partitura.app** into Applications.

Requires **macOS 14 or later and an Apple silicon Mac**. Intel Macs are not supported by this release. Published Mac builds are signed with Developer ID and notarized by Apple; each release includes a SHA-256 checksum.

The audio engine is included. You do not need to install Python or run a setup command. First use may download model weights; allow several GB of free space for the models and your recordings. Longer songs can take several minutes to process.

## From a recording to your part

1. Open an audio file or record with your microphone. Allow microphone access when recording.
2. Separate the recording into drums, guitar, bass, piano, vocals, and other accompaniment.
3. Choose an instrument, listen to its isolated audio, and explore its notes.
4. Export isolated WAV audio, MIDI notes, or a MusicXML score for your music software.

Recordings can be up to 10 minutes and 120 MB. Automatic notation is a draft: check pitches, rhythm, and bar alignment against the audio. The starting meter assumes 4/4. Drum hits use approximate kick, snare, and hi-hat detection, and guitar and piano separation may contain sound from other instruments.

## Your recordings stay with you

Instrument separation and transcription run on your Mac. Recordings and results are stored locally, and audio is not uploaded to a cloud transcription service. Model downloads need an internet connection on first use.

## iPhone and iPad

The native iPhone and iPad companion is in development. It requires Partitura's audio engine running on a Mac; it does not run instrument separation independently on the phone or tablet.

To pair a development build, keep both devices on the same private network and use the Mac's address and pairing token. Keep the token private, and leave Partitura running on your Mac during processing. Audio sent from a companion device is processed and stored on that Mac.

There is no public TestFlight download yet. The public download in this repository is the Mac app.

[Website](https://iamjason.github.io/partitura-site/) · [Release history](https://github.com/iamjason/partitura-site/releases) · [Hyrule Compendium](https://iamjason.github.io/hyrule-compendium-site/tools/partitura/)
