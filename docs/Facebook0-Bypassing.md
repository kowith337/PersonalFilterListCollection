# Break the limit that made by Facebook and their Ø services!

A guide to (partially) bypassing the restriction of using certain Facebook mobile web version, e.g.
- `mbasic.facebook.com`
- `touch.facebook.com`

on any mobile carrier that participating with Facebook to have `Free Basics` services available for their consumers.

### Know the enem(y|ies)
As you probably know, `Free Basics` or Ø (Somehow formerly `internet.org`) is a services that owned by Facebook to allow any cellphone carrier who participating to deploy the services for all users in their carrier, it's allow users to access Facebook, related services and some websites (depend on your region) free of charge by not count the data usage in the data plan for specific sites, include Facebook itself.

However, there are the downside of it... (and probably why some regions resist this!)
- You need to login to Facebook first to integrate Facebook app in their platforme named `Free Basics` into your account.
- You may not see any photos and videos on Facebook and supported sites, even profile pictures in Facebook. (maybe...?)
- Your personal data will be trade-off for this service, to sharing to mobile carrier that you're using, websites (on your region) that participating to `Free Basics` services to improve their ads for more accurate targeting to you!
- Also it's share your data to common 3rd-party ads and tracking like `Google`!

Even Facebook itself, **no matter that you're opted in to this service or not!**

If you open `www.facebook.com` in desktop browser, you will be redirected and re-routed to use on `web.facebook.com` instead.

And worst things happen if you're trying to access Facebook on the mobile browser, either you want to go `mbasic.facebook.com` or `touch.facebook.com` or just `m.facebook.com`, This time Facebook will not play nice!

1. It's redirect to `h.facebook.com` on the **normal HTTP protocol**
2. And then passing to `mobile.facebook.com`, *at least it's back to HTTPS for now.*
3. It's depend on your browser's user agent, if your mobile browser are modern enough, you will probably trapped and lock down to force use only touchscreen version of Facebook mobile web.
4. From the 1., since the connection that made to `h.facebook.com` isn't encrypted, it's an easier way to let the advertisers, local government, military or law enforcement to spy on your data, even it's just a few some readable data. (HECK YEAH!)
5. From the 1. (Take 2), imaging if some hackers hijack the mobile network and make a replacement of `h.facebook.com` to steal your sensitive data instead (e.g. cookies, login session, unencrypted username, e-mail address, passwords, etc.), then pray for yourself and your account! (finger crossed!!)

And not just it have problem that can see on web browser, even Facebook apps and their platform are also in somewhat problematic!
- If you using their official productivity apps (such as Pages manager, Ads Manager, etc.) certains navigation will not done in each apps itself, instead, it will open your main app or default web browser if you didn't have main app installed.
- Somehow about any videos that you've got on or share to someone or chat group in Facebook MESSenger, the video will prevent to play and prompt about using data cost, but unfortunately, you're still can't play any videos while using mobile data!
- If you remember since the first introduce of "Instant Games" in MESSenger, many users who use mobile data are unable to play games unless connect to regular networks (Wi-Fi for example, exclude hotspot share.)
  > I knew that they've resolved this problem at later time, but for me, **I WILL NOT FORGET THIS!**
- Even third party full game and apps that can integrate with your Facebook account, an API connections will be redirected to an another way, and cause the app sometime cannot retrieve any user informations from Facebook, or even cannot use apps. (As I remember, Disa messenger via App password, for example.)
- If you didn't block the social widget that appear as third party, you will noticed from the network logger (or from uBlock/uMatrix) tell that the widget isn't loaded from `www.facebook.com`, but it's loaded from `web.facebook.com`

### Time to strike back! now prepare your tools!!

#### First of all, if you are using Android phone, make sure you have these things already.
- [Firefox for Android](https://play.google.com/store/apps/details?id=org.mozilla.firefox&hl=en_GB) *or other forks like...*
  - [Fennec F-Droid](https://f-droid.org/packages/org.mozilla.fennec_fdroid)
  - [Waterfox](https://play.google.com/store/apps/details?id=org.waterfoxproject.waterfox&hl=en_GB)
  - [IceCatMobile](https://f-droid.org/packages/org.gnu.icecat)
- [uBlock Origin](https://github.com/gorhill/ublock) (It's probably optional, but I recommended, also use with [Facebook Zuckestion Killer](https://github.com/kowith337/PersonalFilterListCollection/raw/master/filterlist/facebook/FacebookZuckestionKiller.txt) to eliminate unwanted things.)

#### Other way workaround... (but not so recommend)
- Any web browser that **can change "User Agent"** e.g.
  - [Web Apps](https://f-droid.org/packages/com.tobykurien.webapps)
  - [Lightning](https://f-droid.org/packages/acr.browser.lightning)
  - [Face Slim](https://f-droid.org/packages/org.indywidualni.fblite) (Facebook wrapper app)

For other system, I have no idea...
> yet, as well as I don't know how to revert back from `web.facebook.com` to `www.facebook.com`.

### All you need to do is replace user agent!
However, make sure you part of user agent will not point to mobile devices, these are few example from me.

##### Correct example
- `Mozilla/5.0 (X11; Linux armv7l) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.77.34.5 Safari/537.36` :white_check_mark:
- `Mozilla/5.0 (X11; Linux x86_64; rv:52.5) Gecko/20100101 Cyberfox/52.5.1` :white_check_mark:

##### Incorrect example
- `Mozilla/5.0 (Android 5.0.2; Mobile; rv:52.0) Gecko/52.0 Firefox/52.0` :x:
- `Mozilla/5.0 (Linux; Android 4.4; App Runtime for Chrome Build/41.4410.238.0) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/99.77.34.5 Safari/537.36` :x:

You shouldn't expose that you're using on Android, and any phone OS either, also your real device name, to prevent both things...
- Nagging banner or panel that trick you to download their official app(s)
- Redirect to unwanted route, since you're using on mobile browser and mobile data, you will not allow to connect other subdomains than `m.facebook.com` or `mobile.facebook.com`, that try to forcing you to apply their `Free Basics` services.

And so, don't point the user agent that you're using `Windows`, otherwise, you cannot even visit any mobile sites and it keep force you to enter `web.facebook.com`!

> Somehow, if your browser cannot change user agent but can request desktop sites, you will try turn that options on and then test on your hand.

#### For Firefox (and/or other forks) users.
- Open `about:config`
- Make sure `general.useragent.site_specific_overrides` set to `true`
- Create `general.useragent.override.mbasic.facebook.com`, set config type as `String` and paste the correct user agent
- Optional, as well as above, this time you create `general.useragent.override.touch.facebook.com` instead.
- Test your configuration, if you didn't see any attempts to redirect, congratulations!

#### Moreover (as your wish)
- Create custom user agent for `facebook.net` and `fbcdn.net` to (probably) faking the OS and device info (appear in `Settings > Security and Login > Where you're logged in`)
  - `general.useragent.override.facebook.net` String
  - `general.useragent.override.fbcdn.net` String

#### But I'm not guaranteed that fully work on `touch.facebook.com`
Because Facebook still know that you're connect the site over mobile carrier network, any transitions will be stuck because it's redirect `AJAX/XHR` requests to `mobile.facebook.com` rather than stay on `m.facebook.com` or `touch.facebook.com`, even I didn't block that subdomain, it's still stuck and show "No network connections" because most browsers even in-app or WebView are forbid the connections that not made to the same origin.