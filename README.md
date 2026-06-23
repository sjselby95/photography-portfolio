# Photography Portfolio

A personal photography showcase site built with plain HTML/CSS, hosted on GitHub Pages.

Live site: [sjselby95.github.io/photography-portfolio](https://sjselby95.github.io/photography-portfolio)

## About

Features albums from my [Flickr profile](https://www.flickr.com/photos/192044761@N05/), including:

- Plane Spotting
- April 8th 2024 Total Solar Eclipse
- Aurora Borealis
- Wings Over Houston 2022
- PANC

Albums are embedded directly via Flickr's embed widget — clicking into any slideshow opens the full album on Flickr.

## Structure

```
index.html   # Single-page site, no build step required
```

## Updating

To add or remove albums, edit the `.album-card` blocks in `index.html`. Each card needs:

1. A Flickr album URL
2. A cover image URL from `live.staticflickr.com`
