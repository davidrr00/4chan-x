4chan-x
=======

Fork of 4chan X 2.x (MayhemYDG) made to keep it working.

To enable hyperlinks and other stuff checkout "Other scripts for additional features"

##Installation
Link: ['4chan_x.user.js'](https://github.com/loadletter/4chan-x/raw/master/4chan_x.user.js)

#### Firefox:

Make sure you have greasemonkey installed and just click on the previous link.

#### Chrome/Chromium/Opera:

Install tampermonkey or equivalent and then just click on the previuos link.

#### dwb:
1. Install dwb with your package manager
2. Install the dwb userscripts extension with `dwbem -N -i userscripts` in your terminal.
3. Make a directory for dwb userscripts with `mkdir .config/dwb/greasemonkey`
4. Change directory to your newly created userscripts folder with `cd .config/dwb/greasemonkey`
5. Download 4chanX with `wget https://github.com/loadletter/4chan-x/raw/master/4chan_x.user.js`
6. Start dwb

##Other scripts for additional features:
- Linkify: [http://userscripts.org/scripts/show/87750](http://userscripts-mirror.org/scripts/show/87750)
    - Mirror: https://gist.github.com/loadletter/d988bbdccc99f3e341c9
- Youtube link title (varios other websites supported): https://greasyfork.org/scripts/413-youtube-link-title
- Inverted /a/: https://github.com/loadletter/4chan-x/raw/master/utils/inverted_a.user.js

##Changelog
- 2.40.52: Missed a closing tag
- 2.40.51: Various bugfixes, updated archives
- 2.40.50: Add option to run autoexpand automatically for long posts, updated some configuration defaults and archives
- 2.40.49: Fix sauce on boards cointaining a digit
- 2.40.48: Added thread in page position to threads stats (not enabled by default), updated archives
- 2.40.47: Fix after board list change
- 2.40.46: Added Replace PNG/JPG, updated archives
- 2.40.45: Compatibility fix to events for other extensions (based on ccd0 fork)
- 2.40.44: Small fix
- 2.40.43: Adapted for recaptcha2 api, also added and enabled by default automatic posting after user has been verified, updated archives
- 2.40.42: Added page index position to thread stats, fix original post form hiding
- 2.40.41: Added unique poster count, updated archives
- 2.40.40: Correct Post in Title beahviour, updated archives
- 2.40.39: Made download link in the dropdown menu work on firefox too (from ccd0 fork), added a shortcut for the Quick Reply next to the navigation arrows
- 2.40.38: Updated filtering code, now various filters should work again
- 2.40.37: Corrected small bug, updated archives
- 2.40.36: Security fixes (Many thanks to ccd0, which discovered those bugs some time ago)
- 2.40.35: Security fixes (Many thanks to ccd0, which discovered those bugs some time ago), fixed small issue, updated archives
- 2.40.34: Update archives (archive.foolz.us -> archive.moe)
- 2.40.33: Fix 404 and updated archives
- 2.40.32: Compatibility with Greasemonkey 2
- 2.40.31: Fix a possible autoupdate problem and updated all the archives
- 2.40.30: Removed the feature that duplicated captcha words since it conflicts with single-word captchas
- 2.40.29: Fix captcha loading in Opera presto (12.17)
- 2.40.28: Fix some security issues and reveal the filename when reveal spoilers is enabled
- 2.40.27: Change cooldowns on /vg/
- 2.40.26: Fix moot changing titles for all the quote stuff (Thanks to WhatIsThisImNotGoodWithComputers, from MayhemYDG's 3.x)
- 2.40.25: Fix Reveal Spoilers feature
- 2.40.24: Fix Catalog Links feature
- 2.40.23: Fix report awakening the inline extension, remove deprecated fix
- 2.40.22: Disable dropdown board selector in the catalog
- 2.40.21: Fix new posts having wrong filename
- 2.40.20: Added feature that allows to completely remove slugs (disabled by default, check Remove Slug in the settings to enable)
- 2.40.19: Fix new posts with quotes appearing as cross-thread
- 2.40.18: Change everything according to http://blog.4chan.org/post/82477681005/upcoming-namespace-changes
- 2.40.17: Apply fit to screen rules to webm too
- 2.40.16: By popular demand added (You) indication (Thanks to WhatIsThisImNotGoodWithComputers) and fixed a webm bug on chrome
- 2.40.15: Add webm support to image hover
- 2.40.13/14: Remove the video from memory when closed
- 2.40.12: Implemented support for inline webm video expansion and uploading
- 2.40.10/11: The final captcha fix (Thanks to WhatIsThisImNotGoodWithComputers)
- 2.40.9: Temporary fix to get the captcha working at least once (doesn't refresh, captcha caching dead and removed)
- 2.40.8: Fix QR captcha load again again, fuck it
- 2.40.7: Fix #4 (/jp/ cooldown and image limit) and switched boards that used installgentoo.net to warosu.org
- 2.40.6: Remove exclude rule for catalog, add /biz/
- 2.40.5: Add exclude rule for catalog
- 2.40.4: Fix QR load again, this time because of mimetype stuff (from a diff of MayhemYDG's 3.x)
- 2.40.3: Replace the thread updater with a normal one that doesn't increment the delay for inactive threads (from ahodesuka fork)
- 2.40.2: Fixed to support new captcha loading function in the Quick Response
- 2.40.1: Fixed code tags
- 2.40.0: Fixed a change in the html that caused errors with the file info and updated to support 4cdn
- 2.39.7: Latest 2.x version from MayhemYDG
