# Bento Grid — Social Media Tool

A responsive bento-style grid section built with CSS Grid, showcasing the features of a social media management tool: post creation, AI writing, scheduling, multi-account management, and audience growth stats.

![Desktop view](./pictures/desktop.jpg)
![Mobile view](./pictures/mobile.jpg)

## Live Demo

[View the live site](https://m-mubashir014.github.io/Bento-grid-project/)

## Features

- **Bento grid layout** built with `grid-template-areas`, arranging 8 unevenly sized cards into one cohesive layout
- **Fully responsive**: the grid collapses to a single column and reflows in a set order on screens under 768px
- **Feature cards** for:
  - Creating and scheduling posts
  - Writing content with AI
  - A star-rating / social proof card
  - Managing multiple accounts and platforms
  - Scheduling and optimizing post timing
  - Maintaining a consistent posting schedule
  - Audience growth percentage stat
  - Growing followers with content
- **Custom typography** using the DM Sans Google Font throughout

## Built With

- HTML5
- CSS3 (CSS Grid, `grid-template-areas`, media queries)
- [Google Fonts](https://fonts.google.com/) (DM Sans)

## Project Structure

```
├── Bento-grid.html   # Page markup
├── Bento-grid.css     # Grid layout and card styles
└── pictures/          # Card illustrations (.webp)
```

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/m-mubashir014/Bento-grid-project
   ```
2. Open the project folder.
3. Open `Bento-grid.html` in your browser.

No build tools or dependencies needed. The only external resource is Google Fonts, so you'll need an internet connection for the font to load.

## How the Grid Works

The `.bento-grid` container uses `grid-template-areas` to name each region (`hero`, `create`, `write`, `accounts`, `schedule`, `maintain`, `growth`, `followers`), and each card is assigned to its area with `grid-area`. This makes the layout easy to read and rearrange without touching the HTML. On mobile, a second `grid-template-areas` stacks every card into a single column in a chosen order.

## What I Learned

- Building an asymmetric grid layout with named `grid-template-areas` instead of manual row/column numbers
- Reflowing a complex grid into a single mobile column just by redefining the areas
- Layering text over images with `position: absolute` inside a card

## Possible Improvements

- Add a tablet breakpoint between the mobile and desktop layouts
- Add hover or focus states to make the cards feel more interactive

## Author

**Mohammed Mubashir**

- GitHub: [@m-mubashir014](https://github.com/m-mubashir014)
