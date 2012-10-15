Maui Wiki
=========

Maui uses MoinMoin for its wiki.

This repository contains only a theme for MoinMoin based on Twitter's Bootstrap.

Edit *wikiconfig.py* and change the *theme_default* value to *bootstrap*.
Now install the theme:

```sh
cp -R theme/maui $wikidir/htdocs/maui
cp theme/maui.py $wikidir/theme/maui.py
```

where *$wikidir* is wiki deployment directory.
