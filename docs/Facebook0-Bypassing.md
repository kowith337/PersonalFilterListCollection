# Break the limit that made by Facebook and their Free Basics services!

A guide to (partially) bypassing the restriction of using certain Facebook mobile web version, e.g.
- `mbasic.facebook.com`
- `touch.facebook.com`

on any mobile carrier that participating with Facebook to have `Free Basics` services available for their consumers.

### Know the enem(y|ies)
As you probably know, `Free Basics` (Somehow formerly `internet.org`) is a services that owned by Facebook to allow any cellphone carrier who participating to deploy the services for all users in their carrier, it's allow users to access Facebook, related services and some websites (depend on your region) free of charge by not count the data usage in the data plan for specific sites, include Facebook. 
However, there are the downside of it... (and probably why some regions resist this!)
- You need to login to Facebook first to integrate `Free Basics` into your account.
- You may not see any photos and videos on Facebook and supported sites, even profile pictures in Facebook. (maybe...?)
- Your personal data will be trade-off for this service, for sharing to mobile carrier that you're using, websites (on your region) that participating to `Free Basics` services to improve their ads for accurate targeting to you!
- Also it's share your data to common 3rd-party ads and tracking like `Google`!

Even Facebook itself, if you open `www.facebook.com` in desktop browser, you will be redirected and re-routed to use on `web.facebook.com` instead.

And worst things happen if you're trying to access Facebook on the mobile browser, either you want to go `mbasic.facebook.com` or `touch.facebook.com` or just `m.facebook.com`, This time Facebook will not play nice!

1. It's redirect to `h.facebook.com` on the **normal HTTP protocol**
2. And then passing to `mobile.facebook.com`, __at least it's back to HTTPS for now.__
3. It's depend on your browser's user agent, if your mobile browser are modern enought, you will probably trapped and lock down to force use only touchscreen version of Facebook mobile web.
4. From the 1., since the connection that made to `h.facebook.com` isn't encrypted, it's an easier way to let the local government, military or law enforcement to spy on your data, even it's just a few some readable data. (HECK YEAH!)
4. From the 1. (Take 2), imaging if some hackers hijack the mobile network and make a replacement of `h.facebook.com` to steal your sensitive data instead (e.g. cookies, login session, unencrypted username, e-mail address, passwords, etc.), then pray for yourself and your account! (finger crossed!!)

### Prepare your tools

#### First of all, if you are using Android phone, make sure you have these things already.
- Firefox for Android __or other forks like...__
  - Fennec F-Droid
  - Waterfox
  - IceCatMobile
- uBlock Origin (It's probably optional, but I recommended, also use with [Facebook Zuckestion Killer](https://github.com/kowith337/PersonalFilterListCollection/raw/master/filterlist/facebook/FacebookZuckestionKiller.txt) to eliminate unwanted things.)

#### Other way workaround... (but not so recommend)
- Any web browser that **can change "User Agent"** e.g.
  - Web Apps
  - Lightning
  - Face Slim (Facebook Wrapper App)

For other system, I have no idea... (yet, as well as I don't know how to revert back from `web.facebook.com` to `www.facebook.com`, so...)