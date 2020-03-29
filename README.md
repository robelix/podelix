# podelix
This should become a Web-Based Podcast Player one fine day

# Status
Concept. No code yet.

Currently selecting frameworks, tools, libs:

* Backend: Python (3, of course), Django
* Frontend: vue.js
* Audio Player: propably Podlove-Web-Player
* Video Player: not yet decided

# Why?

My main podcast player still is Miro - But it's a dead project and increasingly difficult to keep it running. It's Python 2, GTK 2, gstreamer 0.10 - updating it to current stuff would be more or less a complete rewrite.

On the phone AntennaPod is OK - but mobile only.

I've looked at a lot of podcast players - and don't like them all for diffrent reasons - and there is one feature I'm currently missing and none of the existing tools provides: cross-device syncing.

Recently I had a look to funkwhale after they added rss-support - But it's not the tool for me. It has a completely diffrent focus, but maybe I can "steal" some code there.


Finally I realized that the two hardest parts should be simple with a web-based player:
* Browsers got pretty good at playing media.
* No syncing needed - all devices can just access the same backend.

So i decided to start this.
