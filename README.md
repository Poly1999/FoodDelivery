# FoodDelivery

A modern React-based food ordering frontend that lets users browse categories, add items to cart, and proceed through a checkout flow.

## Live Demo

[View Live Demo](https://my-fooddelivery.vercel.app/)

## Overview

`FoodDelivery` is a single-page application focused on a smooth ordering experience:

- Browse menu categories and discover featured dishes
- Add or remove items from the cart in real time
- View a dynamic cart total with delivery fee calculation
- Fill in delivery details on a checkout page
- Use responsive UI sections for menu exploration and app download promotion

## Tech Stack

- React
- React Router DOM
- Context API for global state management
- CSS for component-level styling
- Create React App toolchain (`react-scripts`)

## Project Structure

```text
FoodDelivery/
├── public/
├── src/
│   ├── assets/            # Static images and menu data
│   ├── components/        # Reusable UI components
│   ├── context/           # Global store (cart and totals)
│   ├── pages/             # Route-level pages
│   ├── App.js             # App routes and layout
│   └── index.js           # App entry point
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- npm

### Installation

```bash
npm install
```

### Run Locally

```bash
npm start
```

The app will run at `http://localhost:3000`.

## Available Scripts

- `npm start` - Starts the development server
- `npm run build` - Builds the app for production
- `npm test` - Launches the test runner

## Key Application Routes

- `/` - Home page with category exploration and food listing
- `/cart` - Cart page with quantity and pricing summary
- `/order` - Place order page with delivery information form

## Future Improvements

- Backend integration for real orders and payments
- Authentication with persistent user sessions
- Promo code validation logic
- Order history and tracking

## License

This project is open-source and available under the MIT License.
