# Another custom recipes for uMatrix

Note that I have a custom default setup and not be same like stock or out-of-box settings, please make sure to look the recipe first and also my default settings before apply.

I will not responsible about breakage, both from my default settings and recipes, your need to fix by your own or contact experienced users of uMatrix extension.

### My default settings lists (exclude `matrix-off:` entry)
```
cname-reveal: * true
https-strict: * true
no-workers: * true
noscript-spoof: * false
referrer-spoof: * true
* * * block
* * cookie block
* * css allow
* * doc inherit
* * frame block
* * image allow
* 1st-party * allow
* 1st-party cookie allow
* 1st-party frame allow
* behind-the-scene * inherit
```

### Recipes List Table
| Ruleset Name | Copy Raw Location |
| ------------ | ----------------- |
| Custom Recipes | [:cat:](https://github.com/kowith337/PersonalFilterListCollection/raw/master/ruleset/recipes_custom.txt) [:pill:](https://gitlab.com/kowith337/PersonalFilterListCollection/raw/master/ruleset/recipes_custom.txt) |
| Thai Sites Recipes | [:cat:](https://github.com/kowith337/PersonalFilterListCollection/raw/master/ruleset/recipes_th.txt) [:pill:](https://gitlab.com/kowith337/PersonalFilterListCollection/raw/master/ruleset/recipes_th.txt) |

### Additional notes

#### About turning off `noscript-spoof` globally by default
Disable all of JavaScript doesn't mean to allow secondary or alternative function to be run, If users decide to not allow any scripts, even inline scripts, then leave it as is and don't call any alternative function at all!

The `noscript` are often use for abusive, such as reload ads and/or tracking code, images, frames, etc. in alternative way, and their also know that the ads and tracking were loaded while JavaScript was turned off.