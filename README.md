# MyBike — Landing Page

A responsive landing page for a bike brand: hero, about section, bike comparison, product details and a contact form.

## Live Preview

[nester02.github.io/mybike-landing](https://nester02.github.io/mybike-landing/)

## Design Reference

[Figma — BIKE New Version](https://www.figma.com/file/NZQAIydtHo5QkINyGLHNcq/BIKE-New-Version?node-id=0%3A1)

## Technologies Used

- HTML5 (semantic markup)
- SCSS with BEM naming, variables and mixins
- Flexbox and CSS Grid
- Parcel (via `@mate-academy/scripts`)
- Stylelint, LintHTML

## Getting Started

You need Node.js and npm installed.

```bash
git clone https://github.com/nester02/mybike-landing.git
cd mybike-landing
npm install
npm start
```

`npm start` runs a local dev server; open the address shown in the terminal.
`npm run build` makes a production build.

## Features

- Responsive layout with three breakpoints: mobile (from 320px), tablet (from 576px) and desktop (from 1024px)
- Full-screen mobile menu that opens and closes without JavaScript, using the CSS `:target` selector
- Navigation links to page sections and a "back to top" link
- Sections: About us, Compare bikes, Details, Contact us
- Contact form with required name, email and message fields
- Hover effects with smooth transitions on links, icons and cards
