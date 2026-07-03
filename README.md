# jkkorn/homebrew-tap

Homebrew tap for [Night Conductor](https://github.com/jkkorn/Night-Conductor), a free, open source macOS menu bar app that resumes stalled Conductor, Claude desktop, and terminal Claude Code sessions while you sleep.

## Install

The prebuilt app is not notarized yet, so macOS blocks the first launch unless you skip the quarantine flag:

```
brew install --cask --no-quarantine jkkorn/tap/night-conductor
```

Or, without `--no-quarantine`, clear it once after installing:

```
xattr -dr com.apple.quarantine "/Applications/Night Conductor.app"
```
