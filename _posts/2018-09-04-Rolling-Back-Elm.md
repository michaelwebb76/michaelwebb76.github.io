---
layout: post
title: Rolling back to Elm 0.18
---

Before you get excited about upgrading your projects to Elm 0.19, you might want to check a few things:

1. That there's a clear step-by-step guide that will walk you through it (there isn't, at least at the time of writing)
2. That the developers of your projects dependencies have upgraded those packages already

If those two things are true, there are useful tools for upgrading. The [elm-upgrade tool](https://github.com/avh4/elm-upgrade) does what it says on the tin. It does leave some Elm 0.18 artefacts lying around which is confusing.

If you get flustered and want to go back, you have a couple of alternatives. You can reinstall (Elm 0.18 using NPM)[https://discourse.elm-lang.org/t/installing-elm-0-19-alongside-elm-0-18-on-macos/1673] or by using a language version manager like [asdf](https://github.com/asdf-vm/asdf). I found that deleting the elm binary and reinstalling with NPM got everything back to normal.
