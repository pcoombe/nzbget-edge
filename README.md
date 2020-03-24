<img src="img/icon48.png" align="absmiddle"> nzbget-edge
=============

Extension to interact with nzbget

### Current main features
* Browser action popup that displays active downloads, history and stats
* Browser action icons badge indicating number of current active downloads
* Adds a context menu item to links to download with NZBGet
* Notification when downloads complete
* Uses no toolkits or frameworks, just Javascript, CSS3 and chrome.*-apis
* Drag-n-drop sorting of download queue
* Flow control (pause, resume, delete) on individual items or whole queue.
* One click site intergarion on newznab sites and feedly.com
---

### Version history
#### 1.6 - (current dev)
* Forked from hpsu/nzbget-chrome 1.6, continue to raise issues there
* Renamed to nzbget-edge to satisfy microsoft extension conditions (Product Policies 1.1.2)
* Added privacy policy to satisfy microsoft extension conditions (Product Policies 1.5.2)
---

#### 1.5 - 2017-09-12
* Category support
* New site scripts for  ttRSS, FreshRSS
* Bug fixes and polish
---

#### 1.4 - 2016-01-19
* New tabbed popup appearance
* History search
* Chromium 49 compatibility fixes

---


#### 1.3 - 2015-06-05
* Make popup notifications optional and use new rich notification API.
* Try to lookup status in notified downloads
* Use category Detected from site markup when no category is present in header.
* Support one-click integration for spotweb, binsearch, nzbindex.com
* Fixes and polish

---

#### 1.2 - 2014-10-13
* Better handling of connection failures.
* support one-click integration on nzbindex.nl
* support one-click integration on fanzub.com
* support one-click integration on DOGnzb (thanks @GrimSerious)
* Minor fixes to feedly support due to layout changes
* Updated appearance
* New feature: [optional] Persistent download status on download icons.
* Progress bars now show estimated remaining download time

---

#### 1.1 - 2014-05-31
* Protocol selector (Thanks dakky)
* Less strict nzb header check (Thanks dakky)
* One-click site integration for newznab, feedly and nzbclub
* Provides category to NZBGet if available
* Show paused state on badge label color (Thanks pdf)
* Show nzb health in popup on low quality nzbs
* Use webp-icon in notifications, since rich notifications lost support for SVG
* Additional polish and bugfixes

---

#### 1.0 - 2013-12-31
* Initial release
