# Studio Desk

<img src="assets/studio-desk-on-air.png" alt="Studio Desk ON AIR icon" width="128" />

A Windows studio dashboard for the original RØDECaster Pro, with MIDI channel
status, jingles, clocks, timers, weather, news and independent monitor views.

**[Download Studio Desk](https://github.com/kevlaws/studio-desk-releases/releases/latest)**

## Install

Download **StudioDesk-1.0.0-Setup-x64.exe** from the release page and run it.
Setup installs for the current Windows user, adds a Start menu entry and offers
a desktop shortcut. It includes .NET and an uninstaller. Alternatively, extract
the portable **StudioDesk-1.0.0-win-x64.zip** and open `StudioDesk.exe`.

Requires Windows 10 22H2 or Windows 11 on an x64 PC. The app and installer are
unsigned; Windows may display an unknown-publisher or reputation warning.
SHA256 checksums are included with each release.

## Features

- Studio, Presenter, Jingle board, Prep desk and Studio display views.
- Separate monitor windows with remembered views and full-screen settings.
- MIDI fader positions, mute synchronisation, channel labels and visibility.
- Red ON AIR lamp, digital/circular clock, countdown and stopwatch.
- Stereo input meters, local jingle banks, fades, loops and Stop All.
- Saved show notes, multiple labelled RSS feeds, weather and sourced prep.

Read the **[setup guide](START%20HERE.txt)** before using the app with your desk.
ON AIR reports tracked mixer controls, not whether a stream is broadcasting.
MIDI status needs confirmation after startup/reconnection. Headphone-knob
telemetry, other RØDECaster models and external playout APIs are not verified.
Optional news, weather and prep require internet; core studio tools work offline.

## Your data

Settings, notes and imported sounds are stored in `%LOCALAPPDATA%\StudioDesk`.
Upgrades and uninstall preserve that folder. Back it up separately.
No jingles or personal data are supplied with the download.

## Releases and feedback

This repository hosts **public downloads and documentation**. Application source
is maintained privately; GitHub's automatic source archives here contain only
this repository's documentation and artwork.

[Release notes](CHANGELOG.md) · [Report a problem](https://github.com/kevlaws/studio-desk-releases/issues)

Studio Desk is an independent utility and is not affiliated with or endorsed by
RØDE. Third-party notices are included in each download.
