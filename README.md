# Stem Mixer

Stem Mixer splits a song into its instruments — vocals, drums, bass, guitar,
piano and everything else — and makes what you need to play along: the
isolated instruments, backing tracks without one instrument, and balanced
mixes with one instrument up front. Start from an audio file you have or from
a YouTube link.

It's free to use. By Tommaso Di Biase.

## Download

Get the latest version from **[Releases](https://github.com/dbtswdev/Stem-Mixer/releases/latest)**:

| Your computer | File |
|---------------|------|
| Windows 10 or 11 | `StemMixer-Setup-<version>.exe` |
| Mac with Apple Silicon (M1 and later), macOS 12 or later | `StemMixer-<version>-mac-arm64.pkg` |
| Mac with Intel, macOS 10.15 Catalina or later | `StemMixer-<version>-mac-intel.pkg` |

Not sure which Mac you have? Apple menu → **About This Mac**: "Chip" means
Apple Silicon, "Processor … Intel" means Intel.

## The first time

The installers are free and not signed with a paid certificate, so Windows and
macOS ask for one more click the first time. After that, Stem Mixer tells you
when there's a new version and installs it for you.

**Windows.** Open the setup. If a blue window says "Windows protected your
PC", click **More info**, then **Run anyway**. Then Next, accept the license,
Install. Stem Mixer is in the Start menu.

**Mac.** Open the package. If macOS says it can't verify the developer, click
**Done**, then open **System Settings → Privacy & Security**, scroll down and
click **Open Anyway** next to the message about Stem Mixer. Enter your
password, and the installer starts: Continue, accept the license, Install.
Stem Mixer is in Applications.

## Two ways to separate

- **MVSEP (online):** the best quality, especially on piano. It needs an
  internet connection and a free account at [mvsep.com](https://mvsep.com)
  (50 separations a day); paste its API token in Stem Mixer's Settings. The
  song is uploaded to mvsep.com for processing.
- **On this computer:** works without internet, less accurate. It needs an
  extra download (about 330 MB on Windows, 160 MB on a Mac with Apple
  Silicon, 245 MB on an Intel Mac), which Stem Mixer offers when you first
  choose it, or from Settings — do it at home, before you need it offline.

YouTube links need a small extra download too (about 60 MB), offered the
first time you paste one.

## Good to know

- Use only music you have the right to use. YouTube's terms and copyright
  are your responsibility.
- Stem Mixer never shows or logs your MVSEP token once saved.

## License and contact

Free to use, not open source: see [LICENSE](LICENSE). The components it's
built with keep their own licenses: see [THIRD-PARTY.md](THIRD-PARTY.md).

Questions or problems: dbt.swdev@gmail.com
