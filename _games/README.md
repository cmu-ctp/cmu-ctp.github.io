# Adding a game

## Create the html file

Create a new `KEY.html` file in the `_games` directory. The key for the filename should be `YEAR-TITLE` where title is a short key for your paper. Complete the file with the following basic format.

```html
---
layout: game
year: ...
title: "..."
developers:
  - ...

platform_tags:
  - ...
tags:
  - ...

link: https://...
source: https://...
blog: https://...
video: https://...
---
Description
```

Only the properties in the first block are required. The rest is optional but encouraged (where it makes sense).

## Add a teaser and thumbnail image

Add a teaser and thumbnail image to `assets/games/` in png format. It's important that we keep download sizes small. Please use https://tinypng.com/ to reduce the file sizes of all images.

The teaser image should be at least 1920 pixels wide and wider than tall. Name your teaser image `KEY.png`.

The thumbnail may have any aspect ratio but should be recognizable when shown as a small image. The thumbnail should be at least 600 pixels wide or tall. Name your thumbnail `KEY_thumb.png`. You can programmatically achieve this with `mogrify -resize 600x600^ *_thumb.png`.
