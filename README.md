# Popos HouseHaven

A real estate listings website for South African properties, built with plain HTML, CSS, and JavaScript. No frameworks or libraries.

**Live demo:** https://popomompe.github.io/Popos-HouseHaven/

## Features

- Separate pages for Home, Houses, Apartments, New Developments, Map, Agent Profiles, Favorites, Wishlist, Bond Calculator, and Contact
- 27 sample property listings with price, address, photos, and the listing agent
- Agent profile cards with contact details
- Bond calculator that works out the monthly repayment from the amount, interest rate, and loan term
- Province and city dropdowns, where the city list updates when you pick a province
- Contact form with a confirmation message (demo only)
- Responsive layout for desktop, tablet, and mobile screens

## Built with

- HTML5
- CSS3 (Flexbox, Grid, media queries)
- JavaScript (DOM manipulation, event handling, template strings)

## How it works

- Listings are stored as data in the JavaScript and displayed on the page from there, so a new listing is one new line of data.
- The menu uses page links (`#houses`, `#apartments`, and so on), so each section has its own link you can share.

## How to run

1. Download or clone this repository.
2. Open `index.html` in any web browser.

No installation is needed.

## Known limitations

This is a front-end practice project, so some parts are unfinished:

- Agent names, phone numbers, and prices are sample data.
- Property photos are linked from external listing sites for demonstration only. Some may stop loading.
- The Favorites and Wishlist pages are empty and not connected yet.
- The map shows Gauteng and is not linked to the listings.
- The province and city dropdowns do not filter the listings yet.
- The contact form and property alerts are demos and do not send anything.

## Next steps

- Let users save listings to Favorites and Wishlist
- Add markers on the map for each listing
- Filter listings by province, city, and price
- Add user accounts with a proper back end

## Author

Popo Mompe
