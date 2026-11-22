# Morrow Bakehouse: bakery website demo

A demo website for a neighbourhood sourdough bakery in Bristol. Morrow Bakehouse is a fictional business, made for my web design portfolio.

**Live demo:** https://YOUR-USERNAME.github.io/bakery_website_demo/

## What it does

- **Oven timeline (scroll effect):** as you scroll, a clock runs from 5:00 to 16:00, the background changes from night to daylight, and each bake shows when it comes out of the oven.
- **Live open/closed badge:** checks the current UK time against the opening hours and highlights today in the hours table.
- **Today's bakes:** price board with sold-out items crossed out.
- **Pre-order form:** checks every field, blocks past dates and Mondays (closed), and shows a confirmation message.
- **Responsive:** works on phones, with a mobile menu.
- **Accessible:** keyboard focus styles, form error messages, and reduced motion for people who turn animations off.

## Built with

HTML, CSS and plain JavaScript in one file. No frameworks, no build step.

## Run it

Open `index.html` in a browser, or use the VS Code **Live Server** extension.

## Photos

Without photos, the hero and shopfront show colour gradients. To add photos, put free images from Pexels or Unsplash in an `images/` folder:

- `images/hero.jpg`: loaves of bread
- `images/shopfront.jpg`: the bakery from outside

## Note

The pre-order form is front-end only: it shows a success message but sends nothing. For a real bakery, connect it to a form service such as Formspree.

Design & build by AK.
