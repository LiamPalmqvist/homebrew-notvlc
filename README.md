# Homebrew tap for LVP

[LVP](https://github.com/LiamPalmqvist/LVP) (Liam's Video Player) is a media player built on VLC's
engine with a redesigned interface. The app includes VLC's engine, so VLC itself is not needed.

```bash
brew install --cask liampalmqvist/notvlc/lvp
```

It needs an Apple silicon Mac. The app used to be called NotVLC; `cask_renames.json` moves an
installed `notvlc` over to `lvp` on the next `brew update`.

The cask is updated by LVP's release workflow; its source is
[`packaging/homebrew/lvp.rb`](https://github.com/LiamPalmqvist/LVP/blob/main/packaging/homebrew/lvp.rb)
in the LVP repository.
