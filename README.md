## FAQ

### Why yet another PostgreSQL GUI client? Why not just pgAdmin?
Well, pgAdmin is great for its feature-richness. However, I found its UI is clumsy and complicated. I know there is [a list of PostgreSQL GUI Tools](https://wiki.postgresql.org/wiki/Community_Guide_to_PostgreSQL_GUI_Tools). However, they are either web-based, Java-based<sup>*</sup> or don't support the features I want. In the good old MySQL world, my favorite client is [Sequel Pro](http://sequelpro.com/), but its support for PostgreSQL doesn't seem to be happening. So, I decided to make one myself.

**&nbsp;No offense to the Java community. I am a Java developer myself and I like JVM a lot. I just dislike Java desktop apps personally.*

### Is PSequel open source?
No. There is no plan to open source it at this moment.

### Is PSequel a forked version of Sequel Pro?
No, PSequel is written from scratch in Swift 2, although PSequel's UI is highly inspired by Sequel Pro. 

### Why macOS 10.10+ only?
I am developing PSequel in my spare time. By supporting macOS 10.10+ only, I can keep the codebase simpler and save time by not testing it in older versions of macOS. And, less code, less bugs.

### What's the current status of PSequel?
PSequel is still in its early stage. My plan to implement most features in Sequel Pro. If you think a feature is important, please let me know and I'll adjust its priority based on its popularity.

### How do I report bugs or suggest new features?
Use [Github issue tracker](https://github.com/psequel/psequel/issues). Please try not to create duplicate issues. If you are reporting multiple bugs or suggesting multiple features, please create separate issues for each bug/feature. Please include your macOS, PostgreSQL and PSequel versions when reporting a bug. If you don't have a Github account, you could report bugs [here](http://www.psequel.com/report_bugs).

### How do I support the development of PSequel?
If you like PSequel, please report bugs and/or [help spread the word](https://twitter.com/psequel).
