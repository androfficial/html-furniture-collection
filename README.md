# Furniture Collection

Six-page website for Desire, a furniture store, with sliders, a filterable photo gallery and a blog. Built in May 2021 as a learning project.

**Live demo:** [androfficial.github.io/furniture-collection](https://androfficial.github.io/furniture-collection/)

## Features

- The fixed header shrinks from 120 px to 80 px once the page scrolls past 120 px on screens 767 px and wider. On narrower screens a burger button slides both halves of the menu down and locks page scroll.
- From 768 px up, a menu button in the header opens a side panel from the right. Page scroll locks, and the scrollbar width is added as padding so the layout does not jump.
- Category buttons on the home and gallery pages filter the photo grid.
- Slick powers three sliders: the fading intro slider with dots on the home page, a photo slider with arrow buttons inside a blog post, and the carousel on the contacts page, which shows from ten images down to one as the screen narrows.

## Tech stack

- **Framework:** none, plain HTML and JavaScript
- **UI:** jQuery 3 (from cdnjs), Slick
- **Styling:** SCSS compiled to `css/style.css` (the SCSS sources are not in the repository), Montserrat and Open Sans from Google Fonts
- **Hosting:** GitHub Pages

## Getting started

The repository holds the compiled site, with no dependencies and no build step, so a browser is all it needs. jQuery and the fonts load from CDNs, so the page needs a network connection.

```bash
git clone https://github.com/androfficial/furniture-collection.git
cd furniture-collection
```

Then open `index.html` in a browser.

## Pages

| Page | Description |
| --- | --- |
| `index.html` | Home: intro slider, new collection, "How it works" steps, filterable gallery and blog teasers |
| `about.html` | About page: text, progress bars with percentages, partner logos and the collection grid |
| `gallery.html` | Full photo gallery with category filters |
| `blog.html` | Blog list with a quote, a video post teaser, a post with a photo slider, a sidebar and pagination links |
| `blog-one.html` | Single post with a quote, comments and a comment form |
| `contacts.html` | Google Map, contact details, a contact form and the image carousel |

## Notes

- The forms, the play buttons and the pagination are layout only: nothing is sent, and no video is attached.
