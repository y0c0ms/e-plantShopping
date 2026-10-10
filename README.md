# e-plantShopping

A React and Redux front end for Paradise Nursery, a plant shop with a landing page, an About section, and a plant catalog organized by use.

## Features

- Landing page for "Paradise Nursery" with a Get Started button that reveals the shop
- About Us section describing the nursery
- Navbar with Home, Plants, and cart links
- Plant catalog data for 5 categories and 30 entries (air purifying, aromatic fragrant, insect repellent, medicinal, low maintenance), each with name, image, description, and price
- Redux Toolkit store with a `cart` slice, and a cart view component

Work in progress: the product grid is not rendered yet, and the cart reducers (`addItem`, `removeItem`, `updateQuantity`) and the cart item handlers are empty stubs.

## Stack

- React 18
- Redux Toolkit and React Redux
- Vite
- ESLint

## Run it

Requires Node.js and npm.

```bash
npm install
npm run dev      # start the dev server
npm run build    # production build into dist/
npm run lint     # run ESLint
```

## Project layout

```
src/
  App.jsx          landing page and view switching
  ProductList.jsx  navbar, plant catalog data, cart toggle
  AboutUs.jsx      About Us section
  CartItem.jsx     cart view (stubbed)
  CartSlice.jsx    Redux cart slice (stubbed reducers)
  store.js         Redux store configuration
  main.jsx         app entry point
```

## License

Apache License 2.0. See [LICENSE](LICENSE).

This project started from [ibm-developer-skills-network/e-plantShopping](https://github.com/ibm-developer-skills-network/e-plantShopping).
