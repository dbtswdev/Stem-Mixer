# Third-party components

Stem Mixer is free software under its own license (see `LICENSE`), not open
source. It is built with the components below, each under its own license.

## Shipped with the app

| Component | What for | License |
|-----------|----------|---------|
| Python (python-build-standalone build) | runs the app | PSF License |
| Tcl/Tk | the window | Tcl/Tk License (BSD-style) |
| CustomTkinter | the window's widgets | MIT |
| tkinterdnd2 (and tkdnd) | drag and drop | MIT |
| Pillow | the icon on the About page | MIT-CMU (HPND) |
| darkdetect, packaging | light/dark mode, versions | BSD-3-Clause / Apache-2.0 or BSD-2-Clause |
| yt-dlp | YouTube links | Unlicense |
| FFmpeg (ffmpeg and ffprobe, version 9.0.2) | audio conversion and mixing | GNU GPL; used as a separate program |

FFmpeg's source code: https://ffmpeg.org/releases/ffmpeg-9.0.2.tar.xz. The
builds shipped come from gyan.dev (Windows), Martin Riedl (Mac, Apple
Silicon) and evermeet.cx (Mac, Intel); each app folder keeps a note next to
the programs.

## Downloaded only when you ask (extra downloads)

| Component | What for | License |
|-----------|----------|---------|
| Demucs (Meta AI) | separating on this computer | MIT |
| PyTorch, torchaudio | Demucs's engine | BSD-3-Clause |
| soundfile, and Demucs's own dependencies | audio files | BSD-3-Clause and others |
| deno | YouTube's token provider | MIT |
| bgutil-ytdlp-pot-provider | the token YouTube asks for | GPL-3.0 |

## Services

MVSEP (https://mvsep.com), used online with your own account, under its terms.
