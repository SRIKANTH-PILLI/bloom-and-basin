Bloom & Basin — Pop-Up Shop
A front-end e-commerce demo built for a fictional three-day beauty pop-up shop. Browse products by category, add them to a cart, adjust quantities, and see a running subtotal — all with no backend, no build tools, and no dependencies beyond Google Fonts.
Features
Product catalog — 12 products across 4 categories (Skincare, Makeup, Fragrance, Hair & Body)
Category filtering — instantly filter the grid without a page reload
Shopping cart — slide-out drawer with add, remove, and quantity (+/−) controls
Persistent state — cart contents are saved to `localStorage`, so they survive a page refresh
Custom SVG illustrations — hand-built line-art icons per product (no external images/API calls, so it works fully offline and on any static host)
Responsive design — works from mobile up to desktop
Dark mode support — respects the user's system theme automatically
Built with
HTML5
CSS3 (custom properties for theming, no framework)
Vanilla JavaScript (ES6+, no libraries)
Google Fonts (Fraunces + Inter)
No build step, no `npm install` — it's a single self-contained `.html` file.
Running locally
Clone this repo
Open `index.html` directly in a browser, or
Use a local dev server for live-reload (e.g. the VS Code "Live Server" extension)
bash
git clone https://github.com/SRIKANTH-PILLI/bloom-and-basin.git
cd bloom-and-basin
# open index.html, or right-click → "Open with Live Server"

Project structure

bloom-and-basin/
└── index.html   # all HTML, CSS, and JS in one file

What I'd add next
A checkout flow with form validation
Product detail view / modal
Search bar alongside category filters
Unit tests for the cart logic
Design notes
The visual direction avoids stock e-commerce patterns (photo grids, rounded SaaS cards) in favor of a plum / porcelain / gold palette with a serif + sans type pairing (Fraunces + Inter), and custom line-art product icons instead of photography.

Built as a portfolio project by [p.srikanth].