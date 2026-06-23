# Photography Portfolio

A personal photography showcase site built with plain HTML/CSS, hosted on GitHub Pages.

Live site: [sjselby95.github.io/photography-portfolio](https://sjselby95.github.io/photography-portfolio)

## About

Features a scrollable filmstrip showcase and embedded albums from my [Flickr profile](https://www.flickr.com/photos/192044761@N05/), including:

- Plane Spotting
- April 8th 2024 Total Solar Eclipse
- Aurora Borealis
- Wings Over Houston 2022
- PANC

Albums are embedded directly via Flickr's embed widget — clicking into any slideshow opens the full album on Flickr. Filmstrip photos link to their individual Flickr pages.

## Structure

```
index.html    # Single-page site, no build step required
favicon.png   # Site favicon
README.md
```

## Updating

**Adding a filmstrip photo:** add a new `<a class="filmstrip-item">` block inside `<div class="filmstrip">` in `index.html`:
```html
<a class="filmstrip-item" href="FLICKR_PAGE_URL" target="_blank" rel="noopener">
  <img src="PHOTO_URL" alt="">
</a>
```

**Adding an album:** add a new `.album-card` block inside `<div class="albums">`. Each card needs:
1. A Flickr album URL
2. A cover image URL from `live.staticflickr.com`

## Features

- Dark gallery theme
- Scrollable horizontal filmstrip showcase
- 3-column embedded album grid
- Google Analytics traffic tracking
- Open Graph meta tags for link preview cards
- Custom favicon
