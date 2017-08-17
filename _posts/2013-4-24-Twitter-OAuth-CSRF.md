---
layout: post
title: Twitter OAuth CSRF
---

I have reported a CSRF vulnerability which allows an attacker to authorize any application in victims account on Twitter. It means that an attacker could spam victim's Twitter account by tweets, follow any profile, send/get direct messages or anything possible with Twitter API.
They patched it in 2 days after my report.

You can watch the PoC below:

<iframe width="420" height="315" src="https://player.vimeo.com/video/64714282" frameborder="0" allowfullscreen> </iframe>
