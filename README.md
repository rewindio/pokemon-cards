# Pokémon Cards

Create a working copy of the site https://pokemontcg.io/ using only HTML and Javascript.

## Task

You have been given an HTML page with a form and a placeholder for displaying content as well as copies of the basic media files from https://pokemontcg.io/.

In the given index.js file, replace the "Your code goes here" comment with JavaScript that will enable the following functionality in the index.html page:

- The API text field must accept parameters to return cards by set, name, and colors (at a minimum).
- When the search button is pressed, the page must display a grid of card images based on the provided API string.
- Each card in the grid must be clickable.
- When a card in the list is clicked, the list must be replaced with a detailed view of the clicked card.
- The detailed view of a clicked card must display all data from the card, including appropriate energy-types.
- When the JSON button is pressed, the page must toggle the detailed view of the card with the JSON based on the provided API string.

## Notes

- Don't modify the given index.html file in any way; you can modify the DOM through Javascript.
- You must write JavaScript, not a language that compiles down to JavaScript. You must only use features from the ES5 standard. No 3rd party libraries — i.e., no jQuery, no React, etc.
- Do not recreate the navbar or the footer content from https://pokemontcg.io/; focus on replicating the search and view experience.
- The focus here is on the quality and design of your JavaScript as well as the look/feel of your implementation.
- Your solution should be mobile friendly.
- Assume you only need to support Google Chrome.
