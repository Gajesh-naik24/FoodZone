# Food Menu API

A simple Express.js server that provides a food menu with images, descriptions, and prices. This API can be used to display food items in a frontend application.

## Features

- Serve food data including name, price, description, and image.
- Serve static images for food items.
- Enable CORS to allow cross-origin requests.

## Installation

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed on your system.

### Steps to Run the Application

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/food-menu-api.git
   cd food-menu-api

   /food-menu-web-app
  /src
    /components
      /SearchResults
        - SearchResult.js
    - App.js
  - package.json
  - README.md
  - .gitignore

/food-menu-api
  - index.js
  - package.json
  - /public/images



export const BASE_URL = "http://localhost:9000"; // Update this if your API runs on a different port

Example Response from API:
[
  {
    "name": "Boiled Egg",
    "price": 10,
    "text": "Lorem ipsum dolor sit amet consectetur adipisicing elit.",
    "image": "/images/egg.png",
    "type": "breakfast"
  },
  {
    "name": "RAMEN",
    "price": 25,
    "text": "Lorem ipsum dolor sit amet consectetur adipisicing elit.",
    "image": "/images/ramen.png",
    "type": "lunch"
  }
]
