# Extension Configuration Guide for [uBlock Origin](https://github.com/gorhill/uBlock)

### Advance Settings
- You need enable the advance settings by checkmark the "I am an advanced user ([required reading](https://github.com/gorhill/uBlock/wiki/Advanced-user-features))" box.
- set `assetFetchTimeout` to 60 if your connections cannot fast enough to fetch filterlist under timeout time. (mostly useful for slow 2G/3G mobile data)
- set `suspendTabsUntilReady` to `true` to make sure the browsing windows or tab will not be loaded before filterlist cache is initialized.

### Privacy Settings
- `Disable pre-fetching` must enabled by default.
- `Disable hyperlink auditing` must enabled by default.
- You can checkmark the `Prevent WebRTC from leaking local IP addresses` option if you didn't use any related features, such as Facebook Live, Video Call, Record Audio, etc.
  - Moreover, you can hardening your browser to completely disable the WebRTC features, such as set `media.peerconnection.enabled` to `false` in Firefox.
  - for Chrom[e|ium] users, you can obtain the [NoSync](https://chromium.woolyss.com/#windows-64-bit) build because it doesn't include that feature, but you will lost ability to sync your settings and cannot view DRM contents.
- If you curious about CSP report that some sites used this feature to track users and report to home server that user abusing web content (blocking ads or change page appearance), you can checkmark `Block CSP reports` option.

### 3rd-party filters
- Recommended to have all of uBlock Filters loaded (may include experimental, if needed)
- *More guide is yet to come...*

### Whitelist
- You're free to remove `behind-the-scene` scheme and let the `My rules` managed by default because those rules below are already set.
  - `behind-the-scene * 3p noop`
  - `behind-the-scene * 3p-frame noop`
- You can add missing schemes for your browser, e.g. adding `slimjet-scheme` if you're using [SlimJet](https://www.slimjet.com) browser.
  - **Note**: it's depend on your choice, trustworthy and reputation of your third party browsers or developers of those, this may include Google Chrome itself, [see why?](https://en.wikipedia.org/wiki/Google_Chrome#User_tracking)