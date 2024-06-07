# NFT Items Management

This repository contains a simple JavaScript implementation for managing a collection of NFT items. Each NFT item has properties such as name, height, weight, and country. The functionalities include adding new items, displaying all items, and getting the total count of items.

## Functions

### addItemsNFT(name, height, weight, country)
Adds a new NFT item to the collection.

**Parameters:**
- `name` (string): The name of the item.
- `height` (number): The height of the item in cm.
- `weight` (number): The weight of the item in kg.
- `country` (string): The country associated with the item.

### displayItemsNFT()
Displays all NFT items present in the collection. The details include the item name, height, weight, and country.

### getTotalItemsNFT()
Returns the total number of NFT items in the collection.

## Usage

To use the functions, follow these steps:

1. Clone the repository.
2. Open the JavaScript file and include it in your project.
3. Use the `addItemsNFT` function to add new items.
4. Call the `displayItemsNFT` function to display all the items.
5. Use the `getTotalItemsNFT` function to get the total number of items.

### Example

```javascript
// Adding items to the collection
addItemsNFT("Kerosene Tank", 55, 70, "India");
addItemsNFT("Diesel Tank", 60, 20, "China");

// Displaying all items
displayItemsNFT();

// Getting the total number of items
console.log("Total number of items created in itemsNFT:", getTotalItemsNFT());
