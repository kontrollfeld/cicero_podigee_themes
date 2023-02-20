# cicero-podegee-themes

## build theme
```
yarn build
```

after build you have to copy the override.css and put the content into the index.html style tag by hand and build again!

## How to use custom theme in embed code:
```
https://cicero.podigee.io/54-neue-episode/embed?context=external&themeHtml=https%3A%2F%2Fraw.githubusercontent.com%2Fpodigee%2Fpodigee-podcast-player%2Fmaster%2Fsrc%2Fthemes%2Fminimal%2Findex.html&themeCss=...
```

Use GET parameter ```themeHtml``` and ```themeCss``` to set URLs to theme files (urlencoded)

## Crete theme by copy one of the default themes:

https://github.com/podigee/podigee-podcast-player/tree/master/src/themes