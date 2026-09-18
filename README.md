# HaMorena Website Project

## Project Title
HaMorena Fine Watches &amp; Men's Accessories &ndash; Website (WEDE5020 Portfolio of Evidence)

## Student Information
- Student Name: Naledi Mohoje
- Business: Star_Works &ndash; Web Design &amp; Development
- Module: Web Development (Introduction) &ndash; WEDE5020

## Project Overview
This project is the development of a responsive, functional website for
HaMorena Fine Watches & Men's Accessories, a South African men's
accessories retailer with stores in Sandton, Cape Town (V&A Waterfront)
and Umhlanga, Durban. The website showcases HaMorena's product range
(watches, chains, belts and shoes), and is being built in three parts
across the module's Portfolio of Evidence: HTML foundation (Part 1),
CSS styling and responsive design (Part 2), and JavaScript
functionality and SEO (Part 3).

## Website Goals and Objectives
- Build a basic online store so HaMorena isn't only relying on people
  walking into a mall store.
- Let customers browse products online and enquire about purchasing.
- Let customers request to "Reserve to Try In-Store" for watches.
- Show up better on Google when people search things like "men's
  watches Johannesburg".

## Key Features and Functionality
- Multi-page responsive website (Home, About Us, Shop, Enquiries,
  Contact).
- Consistent navigation across all pages.
- A product catalogue organised by category (Watches, Chains, Belts,
  Shoes), with an individual page per product.
- Enquiry and contact forms (to be made functional with client-side
  validation in Part 3).
- A cart and checkout page structure (to be made functional in Part 3).
- Store location details for all three HaMorena branches.

## Timeline and Milestones
| Milestone | Description | Status |
|---|---|---|
| Part 1 | Project initiation, planning, and HTML foundation | Complete |
| Part 2 | CSS styling and responsive design | In progress (this repository) |
| Part 3 | JavaScript functionality and SEO optimisation | Not started |

## Part 1 Details
Part 1 focused on building the foundation of the HaMorena website:
- Selecting HaMorena as the target organisation, based on Proposal 1 of
  the Star_Works website proposal document.
- Establishing a well-organised file and folder structure, matching the
  structure used for the FORMEZ project.
- Creating the HTML structure for five core pages: `index.html`,
  `about.html`, `services.html` (Shop), `inquiries.html`, and
  `contact.html`.
- Creating 8 individual product pages, organised across the Watches,
  Chains, Belts and Shoes categories.
- Creating `cart.html` and `checkout.html` as static page structures.
- Linking all pages together with a functional navigation menu.
- Adding placeholder product images to the `_images` folder. These are
  simple generated placeholders (no real HaMorena product photography
  was supplied), and should be replaced with real product photos before
  the site is styled in Part 2.

## Part 2 Details
Part 2 applies CSS styling and responsive design on top of the Part 1
HTML foundation, via a single stylesheet at `css_assets/mystyle.css`:
- CSS custom properties for a consistent colour palette (`--dark-brown`,
  `--brown`, `--medium-brown`, `--light-brown`, `--cream`, `--gray`,
  `--light-gray`, `--white`, `--black`).
- Flexbox header/navigation and CSS grid for the category and product
  highlight sections.
- Responsive breakpoints at `900px` and `600px`, collapsing the header,
  hero and grid layouts down to a single column on mobile.
- Real product photography added to `_images` (watches, chains, belts,
  shoes and the storefront hero image), replacing the Part 1
  placeholders where available.

**Known gap against the Part 1 plan:** this repository currently
carries forward `index.html`, `about.html`, `services.html`,
`inquiries.html`, `contact.html`, and 4 of the 8 planned product pages
(gold curb chain, gold-tone dress watch, black leather belt, leather
dress shoes). The remaining 4 product pages (classic steel watch,
chronograph watch, silver rope chain, tan leather belt), `cart.html`,
`checkout.html`, and the `js_assets` / `private` folders from the Part
1 structure have not yet been carried into this repository. These need
to be added back in &ndash; either before Part 2 is finalised, or
explicitly deferred to Part 3 &ndash; so the delivered site matches the
sitemap below.

## Sitemap
```
HaMorena Website
|
|-- Home (index.html)
|-- About Us (about.html)
|-- Shop (services.html)
|   |-- Classic Steel Watch (product-classic-steel-watch.html)            [pending]
|   |-- Gold-Tone Dress Watch (product-gold-dress-watch.html)
|   |-- Chronograph Watch (product-chronograph-watch.html)                [pending]
|   |-- Gold Curb Chain (product-gold-curb-chain.html)
|   |-- Silver Rope Chain (product-silver-rope-chain.html)                [pending]
|   |-- Leather Belt - Black (product-leather-belt-black.html)
|   |-- Leather Belt - Tan (product-leather-belt-tan.html)                [pending]
|   `-- Leather Dress Shoes (product-leather-dress-shoes.html)
|-- Enquiries (inquiries.html)
|-- Contact (contact.html)
|-- Cart (cart.html)                                                      [pending]
`-- Checkout (checkout.html)                                              [pending]
```
Pages marked `[pending]` are documented in the Part 1 plan but are not
yet present in this repository (see "Known gap" above).

## File Structure
```
/
|-- index.html
|-- about.html
|-- services.html
|-- inquiries.html
|-- contact.html
|-- cart.html                          (pending)
|-- checkout.html                      (pending)
|-- product-classic-steel-watch.html   (pending)
|-- product-gold-dress-watch.html
|-- product-chronograph-watch.html     (pending)
|-- product-gold-curb-chain.html
|-- product-silver-rope-chain.html     (pending)
|-- product-leather-belt-black.html
|-- product-leather-belt-tan.html      (pending)
|-- product-leather-dress-shoes.html
|-- _images/        (product and site images)
|-- css_assets/     (CSS files - added in Part 2)
|-- js_assets/       (JavaScript files - to be added in Part 3)   (pending)
|-- private/         (project working files not published on the site) (pending)
`-- README.md
```

Note: the finished site is intended to have 15 HTML pages in total (5
core pages plus 8 individual product pages, a cart page, and a
checkout page), per the Part 1 brief. This repository currently
contains 9 of those 15 pages.

## Changelog
### Part 1
- Set up project folder structure (`_images`, `css_assets`, `js_assets`,
  `private`), matching the structure used for the FORMEZ project.
- Added placeholder product images to `_images` (to be replaced with
  real HaMorena product photography).
- Created HTML structure and content for `index.html`, `about.html`,
  `services.html`, `inquiries.html`, and `contact.html`.
- Added 8 individual product pages (`product-*.html`), each displaying
  the product's image, category, description, price in Rands, and a
  form (size, colour, quantity, Add to Cart) as static HTML.
- Added `cart.html` and `checkout.html` as static page structures for
  the future shopping cart and checkout flow.
- Linked navigation across all pages.
- **Note on scope:** these pages are HTML structure only, with no CSS
  or JavaScript. The "Add to Cart" forms, cart contents, and order
  totals are not yet functional &ndash; this will be implemented with
  JavaScript in Part 3, as specified in the module brief.

### Part 2
- Added `css_assets/mystyle.css`, a single stylesheet covering all
  pages currently in the repository.
- Replaced placeholder imagery with real product and storefront photos
  in `_images` (still pending for the 4 product pages not yet carried
  into this repository).
- Applied a consistent colour palette, typography, and responsive
  layout (flexbox header/nav, CSS grid for product/category sections)
  across breakpoints at `900px` and `600px`.
- **Outstanding from Part 1:** `cart.html`, `checkout.html`, the
  remaining 4 product pages, and the `js_assets` / `private` folders
  still need to be added and styled to bring this repository in line
  with the full Part 1 sitemap.

## References
- The Independent Institute of Education (Pty) Ltd, 2026. *WEDE5020
  Portfolio of Evidence*. Module guide. IIE.
- Content sourced from the Star_Works Website Proposal for HaMorena
  (Proposals_WEDE_Naledi_.docx, Proposal 1).
