# Extension Configuration Guide for [uBlock Origin](https://github.com/gorhill/uBlock)

### Advance Settings
- You need enable the advance settings by checkmark the "I am an advanced user ([required reading](https://github.com/gorhill/uBlock/wiki/Advanced-user-features))" box.
- set `assetFetchTimeout` to 60 if your connections cannot fast enough to fetch filterlist under timeout time. (mostly useful for slow 2G/3G mobile data)
- set `suspendTabsUntilReady` to `true` to make sure the browsing windows or tab will not be loaded before filterlists cache is initialized.

### Custom Resources
#### [Advanced/Optional] Adapt and integrate with [NanoAdBlocker](https://jspenguin2017.github.io/uBlockProtector)
Please look at the **Extra installation steps for uBlock Origin** section that appear on the site.

### Privacy Settings
- `Disable pre-fetching` must enabled by default.
- `Disable hyperlink auditing` must enabled by default.
- You can checkmark the `Prevent WebRTC from leaking local IP addresses` option if you didn't use any related features, such as Facebook Live, Video Call, Record Audio, etc.
  - Moreover, you can hardening your browser to completely disable the WebRTC features, such as set `media.peerconnection.enabled` to `false` in Firefox.
  - for Chrom[e|ium] users, you can obtain the [NoSync](https://chromium.woolyss.com/#windows-64-bit) build because it doesn't include that feature, but you will lost ability to sync your settings and cannot view DRM contents.
- If you curious about CSP report that some sites used this feature to track users and report to home server that user abusing web content (blocking ads or change page appearance), you can checkmark `Block CSP reports` option.

### 3rd-party filters
- Recommended to have all of **uBlock Filters** loaded
  - uBlock Filters *(This is the heart of uBlock that enhance the default list supscriptions)*
  - uBlock Filters - Annoyances *(Enhanced the shady [or maybe forcefully] interaction blocking, such as register, like/share, etc.)* 
  - uBlock Filters - Badware Risks *(Warn and block sits that potentially serve adware while you're trying to find and install popular programs)*
  - uBlock Filters - Experimental *(for testing new type of blocking, scriptlets and redirect to neutered resources)*
  - uBlock Filters - Privacy *(this will block more 3rd party ads/tracking hits)*
  - uBlock Filters - Resource abuse *(this block the resources/domains that use your machine performance, such as cryptomining, peer-to-peer CDN and such...)*
  - uBlock Filters - Unbreak *(to unbreak mistaken block/hide and also fool the site that can detect content blocking)*
- *More guide is yet to come...*

### Whitelist
- You're free to remove `behind-the-scene` scheme and let the `My rules` managed by default because those rules below are already set.
  - `behind-the-scene * 3p noop`
  - `behind-the-scene * 3p-frame noop`
- You can add missing schemes for your browser, e.g. adding `slimjet-scheme` if you're using [SlimJet](https://www.slimjet.com) browser.
  - **Note**: it's depend on your choice, trustworthy and reputation of your third party browsers or developers of those, this may include Google Chrome itself, [see why?](https://en.wikipedia.org/wiki/Google_Chrome#User_tracking)