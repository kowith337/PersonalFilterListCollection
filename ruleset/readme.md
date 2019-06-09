# Another custom recipes for uMatrix

Note that I have a custom default setup and not be same like stock or out-of-box settings, please make sure to look the recipe first and also my default settings before apply.

I will not responsible about breakage, both from my default settings and recipes, your need to fix by your own or contact experienced users of uMatrix extension.

### My default settings lists (exclude `matrix-off:` entry)
```
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