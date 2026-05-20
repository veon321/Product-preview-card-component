# Frontend Mentor - Product preview card component solution

This is a clean, responsive, and modern solution to the Product preview card component challenge on Frontend Mentor.

## The challenge

The challenge was to build a product preview card component and get it looking as close to the design as possible using HTML and CSS. The component needed to be fully responsive, handling both mobile and desktop layouts seamlessly.

## Links

- Solution URL: [https://github.com/veon321/Product-preview-card-component](https://github.com/veon321/Product-preview-card-component)
- Live Site URL: [https://veon321.github.io/Product-preview-card-component/](https://veon321.github.io/Product-preview-card-component/)

## Built with

- Semantic HTML5 markup
- CSS Custom Properties (Variables)
- Flexbox layout (with advanced `flex-wrap` and `align-items` positioning)
- Modern CSS Math Functions (`clamp()` for fluid typography, dynamic paddings, and responsive scaling)
- Advanced "Holy Albatross" CSS design pattern for container switching
- Mobile-first approach transitioning into fluid desktop layout
- Google Fonts (Montserrat & Fraunces)

## Features

- **No Media Queries (@media):** The entire responsiveness and layout switching between mobile and desktop is handled dynamically. The component uses a smart mathematical `max-width: clamp()` formula (The Holy Albatross pattern) based on a `560px` breakpoint, forcing the image and content to switch layout instantly without any awkward intermediate states.
- **Fluid Typography & Paddings:** Instead of rigid breakpoints, the headers, product prices, and container paddings scale smoothly and proportionally using `clamp()` and `rem` units, which ensures perfect accessibility for user browser font settings.
- **Flawless Image Cropping:** Uses `object-fit: cover` and `align-self: stretch` combined with `overflow: hidden` on the parent container to keep the product image perfectly aligned with the text block height on desktop, while automatically maintaining a beautiful aspect ratio on mobile devices.
