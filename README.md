# Gourmet Menu

    This project is part of the learning in the Generation Thailand program

A modern restaurant menu web page that displays food items with images, cuisine info, and a shopping cart system.

## Features

- **Menu Display** - Food cards with images, cuisine type, origin, and veg/non-veg
- **Shopping Cart** - Add/remove items, adjust quantities, real-time subtotal, tax, and total

## Files
| File | Description |
|------|-------------|
| `index.html` | Main page — structure, styles, and JavaScript |
| `my-array.js` | Simple array of food names (`let food = [...]`) |
| `my-object.js` | Food database with objects containing `id`, `name`, `cusine`, `origin`, `vegetarian`, `image` |

## Usage

Open `index.html` in any browser. No server or build step required.

## Data Structure

Each item in `foodDatabase` (`my-object.js`):
```js
{
  id: 1,
  name: "Pizza",
  cusine: "Italian",
  origin: "Italy",
  vegetarian: false,
  image: "https://images.unsplash.com/photo-1565299624946-..."
}
```

