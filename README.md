# Getting Started with Create React App
# Property Booking App

A property booking application built with React. Users can browse property listings, filter properties based on various criteria, add properties to a cart, and proceed to checkout.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)


## Technologies Used

- React
- Create React App
- CSS for styling
- JSON for static data

## Features

- Browse property listings with images, descriptions, and prices.
- Filter properties based on location, price range, number of bedrooms, and amenities.
- Add properties to a cart and view the cart.
- Proceed to checkout with a form to enter booking details and payment information.
- Responsive design for mobile and desktop.

## Setup and Installation

### Prerequisites

- Node.js and npm installed. You can download them from [here](https://nodejs.org/).

### Installation Steps

1. **Clone the repository:**
    
    git clone https://github.com/your-username/property-booking-app.git
     
    git config --global user.email  "ajaydevra1999@gmai.com"
    git config --global user.name "ajaydevra"
    git init
    git remote add origin https://github.com/ajaydevra/-totality-frontend-challenge-
    git add -A
    git commit -m "solution"
    git branch -M main
    git push -u origin main



2. **Install dependencies:**
    
    npm install
    

3. **Run the application:**

    npm start
    

4. Open your browser and navigate to `http://localhost:3000` to see the application in action.

Demo
## Link : https://totality-frontend-challenge-five-inky.vercel.app/

## Usage

### Browsing Properties

- The homepage displays a list of available properties.
- Use the filter options to narrow down the listings based on your criteria.

### Adding to Cart

- Click on the "Add to Cart" button on any property listing to add it to your cart.
- View your cart by clicking on the cart icon/button.

### Checkout

- Click on "Proceed to Checkout" from the cart to go to the checkout form.
- Fill out your booking details and payment information.
- Submit the form to confirm your booking.

## Folder Structure

property-booking-app/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── Property.js
│   │   ├── Filter.js
│   │   ├── Cart.js
│   │   └── Checkout.js
│   ├── data/
│   │   └── properties.json
│   ├── App.js
│   ├── App.css
│   └── index.js
├── package.json
├── README.md
└── ...