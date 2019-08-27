# These problematics below aren't verified by other peoples, but I've found by myself!
\* Feel free to say, shout out and/or share this document if you've experienced the same.

1. No matter that how long you've disabled **Chrome** app, if you've open **Play store** app, it will update itself and re-enable back! regardless of you've set to turn off automatic updates!!
   - Also, these apps are auto update itself without user consents and cannot be prevented! if you didn't disable **Google Play Store** before it does!!
	    - **YouTube** (can do same things like **Chrome** does, by re-enable and update app if you've disable before!)
     - **Google Play Store**
     - **Google Play Services**

2. When I've complete reset **Chrome** app either via *App settings* or *ADB commands* (use `am kill`, `am force-stop`, and `pm clear` together), I've re-check app info and found **Chrome** app have **Location** permission toggled on after successfully clear everything!
   - Personally, I think in case if everything must be reset, none of any permissions can be granted automatically!!
   - That's why some tech news said and found **Google Chrome** itself phone home user locations too often!!!
   > None of any forks doing the same things as **Google Chrome itself** does for this (intentionally?) problem, maybe because the marketing agreement of Android :tm: and/or Chrome itself are pre-installed as system level, which have enough priviledge for doing that thing!?

3. Because **Chrome** itself use internal **Manage storage** function, so...
   - The **Clear storage** button will launch app itself (via `activity shortcut`?) and have 3 buttons inside, to *clear unimportant site storage*, *clear all site storage* or *clear every data* (the last choice is means include your configuratoion in the app!)
     - You will wake up an app itself, sadly to say if you've decided to stop using and keep ignoring it! (esp. **Google Chrome**)
     - Default **clear data** button will only show confirmation dialog before performing completely delete everything within app and start everyting over from the beginning...
       - And yes, only just 2 taps to clear everything for default **Clear storage** button, while **Chrome itself** built-in clear storage button have extra steps than that!
   > - From the problem number 1, I prefer to clear those data through `ADB` for avoide waking it's app unintentionally.
   > - It seems like all of forks are also follow this line, include **[Bromite](https://github.com/bromite/bromite)**, **[Brave](https://github.com/brave/browser-android-tabs)**, etc.

4. They're lots of **[strange DNS hostname requests](https://i.imgur.com/gQJWGlp.jpg)** (captured, monitored and logged via [personalDNSFilter](https://github.com/IngoZenz/personaldnsfilter)) everytime I've start using, no matter about hardening within application settings and browser flags!
   - And I don't know what those requests are connected to and use for? Why they want to hide something shady and don't want to let anyone know, control by allow or block those shady connections?
   > - This problems can be found in any other forks that follow the Google Chrome / Chromium update pipeline and doesn't patch or hardening enough before build, include [Brave](https://github.com/brave/browser-android-tabs) and [Vanilla chromium](https://github.com/bromite/chromium) that built side-by-side along with [Bromite](https://github.com/bromite/bromite), maybe I need to include [routine built from the Chromium team](https://chromium.woolyss.com/#android)\*, too!? \*(See `The Chromium Authors`)
   > - Judging by myself, those connections are use for **fetching preloaded homepage sites**, **suggested articles**, etc.
   >   - Those are garbage features for me after all! If I want to read something, I will go read from the sites that I want by manually type them (and search with other engines, not ~~Google~~!), or prefer to subscribe RSS and read them in feed reader apps, e.g. [Flym](https://github.com/FredJul/Flym), [Feeder](https://gitlab.com/spacecowboy/Feeder), [Handy News Reader](https://github.com/yanus171/Handy-News-Reader), [SpaRSS DecSync](https://github.com/39aldo39/spaRSS-DecSync), etc.