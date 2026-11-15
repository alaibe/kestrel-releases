# Kestrel releases

The releases of [Kestrel](https://kestrel.laibe.cc), a fast, keyboard-first email client for macOS, Windows and Linux.

## Install

Download the files for your system from the newest release under **Releases**, or from
[kestrel.laibe.cc/download](https://kestrel.laibe.cc/download):

- **macOS 15 or later**: `Kestrel-<version>.dmg`, for Apple silicon and Intel, signed with a Developer ID. With
  Homebrew: `brew install --cask alaibe/tap/kestrel`. While releases aren't notarized, the first launch of a downloaded
  copy is refused once: allow it in System Settings › Privacy & Security › Open Anyway.
- **Windows 10 or later**: the installer, `…_x64-setup.exe`.
- **Linux (x86_64)**: the AppImage, the `.deb` for Debian and Ubuntu, or the `.rpm` for Fedora and openSUSE. Kestrel
  keeps sign-ins in the Secret Service, so GNOME Keyring or KWallet needs to be running.

## Updates

On the Mac, Kestrel checks <https://kestrel.laibe.cc/appcast.xml> once a day and updates itself from here. On Windows
and Linux, download each new version from here.

The source code isn't in this repository. Each release is built, signed and published here from it by the
author's own CI, not GitHub Actions.
