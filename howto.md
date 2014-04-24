How to become a mirror
======================

.) subscribe to the qmailtoaster-mirror list
.) notify the list of the host's IP address you'll be using
.) The project DNS manager (Dan) will assign you a mirror# name
.) The project repo manager (Shubes) will authorize your host to rsync

You need to set up an http server that serves the resulting structure from mirror#.qmailtoaster.com/repos/. You should include mirrors.qmailtoaster.com as a server alias, but rewrite that to your server's real name.

You can omit the archive/ if you have limited space. There is presently 1.6G of stuff, with 1.1G of archives.

That's it for now. This document could use some work. Pretty formatting to come.

Thanks.
