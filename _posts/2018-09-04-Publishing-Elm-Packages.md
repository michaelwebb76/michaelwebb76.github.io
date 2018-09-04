---
layout: post
title: Publishing Elm 0.18 packages
---

I just went through the excruciating process of trying to publish a new version of my Elm 0.18 package. If you're in the same boat, here's a few tips:

1. I published a new version of my package using `elm-package`, and subsequently gnashed my teeth as I could not seem to update that package in my other projects.
2. I was advise on the Elm Slack channel to change my `license` field in the `elm-package.json` to contain "BSD-3-Clause" and to republish a patch version.
3. After more teeth gnashing, I found that although the package was not appearing on [https://package.elm-lang.org/](https://package.elm-lang.org/), even with the specific URL entered, I could actually update to that package version in my other projects.

I hope this saves someone an hour.
