# responsive-portfolio

## Take a look

**[Responsive Portfolio](https://andrewpetersondev.github.io/responsive-portfolio/)**

## Overview

The purpose of this project was to perfectly translate images and specifications into a responsive portfolio website using pure html and css techniques.

## Criteria

1. Use three `@media screen` tags, each with one of these `max-width`s: `980px`, `768px` and `640px`.

   - You use `980px` because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.

   - `768px` is about the width of a tablet and `640px` is about the width of a phone in landscape.

2. Make the layout match the following screenshots:

   - `index.html`: [980px](./assets/images/980-index.jpg), [768px](./assets/images/768-index.jpg), [640px](./assets/images/640-index.jpg)

   - `portfolio.html`: [980px](./assets/images/980-portfolio.jpg), [768px](./assets/images/768-portfolio.jpg), [640px](./assets/images/640-portfolio.jpg)

   - `contact.html`: [980px](./assets/images/980-contact.jpg), [768px](./assets/images/768-contact.jpg), [640px](./assets/images/640-contact.jpg)

3. Make the position of the header `static` (the default positioning) when the screen is `640px` wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.

4. Be sure to include the `viewport` tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. _(Hint: You won't need to use exact pixels for anything other than the container)_
