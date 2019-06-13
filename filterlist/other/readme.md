| List Name | Subscribe via ABP link | Copy raw location |
| --------- | ---------------------- | ----------------- |
| Anti Survived Tracking Link Warning | [:cat:](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fgithub.com%2Fkowith337%2FPersonalFilterListCollection%2Fraw%2Fmaster%2Ffilterlist%2Fother%2FSurvivedTrackingLinkWarning.txt&amp;title=Anti%20Survived%20Tracking%20Link%20Warning) [:pill:](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fgitlab.com%2Fkowith337%2FPersonalFilterListCollection%2Fraw%2Fmaster%2Ffilterlist%2Fother%2FSurvivedTrackingLinkWarning.txt&amp;title=Anti%20Survived%20Tracking%20Link%20Warning) | [:cat:](https://github.com/kowith337/PersonalFilterListCollection/raw/master/filterlist/other/SurvivedTrackingLinkWarning.txt) [:pill:](https://gitlab.com/kowith337/PersonalFilterListCollection/raw/master/filterlist/other/SurvivedTrackingLinkWarning.txt) |
| - Overdone version | [:cat:](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fgithub.com%2Fkowith337%2FPersonalFilterListCollection%2Fraw%2Fmaster%2Ffilterlist%2Fother%2FSurvivedTrackingLinkWarning-Overdone.txt&amp;title=Anti%20Survived%20Tracking%20Link%20Warning%20(Overdone%20Edition)) [:pill:](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fgitlab.com%2Fkowith337%2FPersonalFilterListCollection%2Fraw%2Fmaster%2Ffilterlist%2Fother%2FSurvivedTrackingLinkWarning-Overdone.txt&amp;title=Anti%20Survived%20Tracking%20Link%20Warning%20(Overdone%20Edition)) | [:cat:](https://github.com/kowith337/PersonalFilterListCollection/raw/master/filterlist/other/SurvivedTrackingLinkWarning-Overdone.txt) [:pill:](https://gitlab.com/kowith337/PersonalFilterListCollection/raw/master/filterlist/other/SurvivedTrackingLinkWarning-Overdone.txt) |
| Uncategorised Miscellaneous Annoyance | [:cat:](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fgithub.com%2Fkowith337%2FPersonalFilterListCollection%2Fraw%2Fmaster%2Ffilterlist%2Fother%2FMiscAnnoyance.txt&amp;title=Miscellaneous%20Annoyance) [:pill:](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fgitlab.com%2Fkowith337%2FPersonalFilterListCollection%2Fraw%2Fmaster%2Ffilterlist%2Fother%2FMiscAnnoyance.txt&amp;title=Miscellaneous%20Annoyance) | [:cat:](https://github.com/kowith337/PersonalFilterListCollection/raw/master/filterlist/other/MiscAnnoyance.txt) [:pill:](https://gitlab.com/kowith337/PersonalFilterListCollection/raw/master/filterlist/other/MiscAnnoyance.txt) |


- - - - -

# Anti Survived Tracking Link Warning
I intentionally create this to prevent future problem that common extensions and user scripts created for unfold tracked URL and turn into the real destination.

However, some big company won't play nice and currently produce new problematic that the creator of extensions and user scripts not yet fixed, include...
- Facebook outbound tracking parameter, some parameter was survived after unfold. ([example issue](https://github.com/kowith337/PersonalFilterListCollection/issues/19))
- New layout of Google Images that broke any extensions and user script that trying to replace real URL instead of tracked link, navigating with keyboard doesn't help anymore!

I will let the uBlock0 or Nano for block and prevent navigation before it's follow that way, then give the same internal ability to expose real URL under blocked URLs but...
- Some URL that have multiple parameters is possibly to be messed, making you confuse and don't know what to do next! you may need to make a manual text selection (don't forget to exclude some path that possibly tracking you!!), copy and paste to address bar or use the **Go to 'your address'** instead.
- Some sites that can do the seamless navigations will not prevent tracked URL in the same tab, however, it's work properly if you open it into new tab or subscribe to [**Overdone**](https://github.com/kowith337/PersonalFilterListCollection/raw/master/filterlist/other/SurvivedTrackingLinkWarning-Overdone.txt) version instead.

I cannot help you much if you still stuck, but **I have no choice, just privacy first!!!**

- - - - -

# Miscellaneous annoyance is a custom list that not yet categorized!
As usual, only uBlock Origin (also other forks, but I don't recommend anything of those except [Nano](https://github.com/NanoAdblocker/NanoCore)) can use the list that I've created, due to...
- No `[AdBlock Plus x.xx]` compatibility header.
- Have many syntax that `AdBlock Plus` cannot understand!
  - Also [old uBlock](https://github.com/uBlock-LLC/uBlock), and you should avoid it as possible! ([1](https://github.com/uBlock-LLC/uBlock/commit/76b89c0a22d20f3a66d7feab14e024f56ca65539), [2](https://old.reddit.com/r/sysadmin/comments/8k4ot6))

### Supported sites (for current)
- Chocolate Minecraft [`chocolateminecraft.com`]
- Google (wildcard TLD) [`google.*`]
- GitHub [`github.com`]
- GreasyFork [`greasyfork.org`]
- Linkis [`linkis.com`]
- Minecraft Forge [`files.minecraftforge.net`]
- Ookla Speed Test [`speedtest.net`]
- Optifine [`optifine.net`]
- Reddit [`reddit.com`]
- Randomness Thing [`randomnessthing.com`]
- Stack Networks (Partial) [`stackoverflow.com`, `stackexchange.com`, `superuser.com`]
- Taobao Mobile [`m.intl.taobao.com`, `m.taobao.com`]
- Twitter [`twitter.com`]
- YouTube [`youtube.com`]
- WallGif [`wallgif.com`]
- Wordpress Dashboard (aka. Gravatar) [`wordpress.com`]

### Blocking mode
- Add0n [`add0n.com`]
- Mozilla AMO [`addons.mozilla.org`] (May not work for **Firefox quantum** (v57+) due to [privileged page](https://github.com/gorhill/uBlock/wiki/Privileged-Pages))

- - - - -