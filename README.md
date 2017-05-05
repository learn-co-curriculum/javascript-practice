# JavaScript Practice

## Objectives

* Build out a JavaScript only application that hits an external API. **Note:** Find an API that doesn't require authentication. You can use one of the API's suggested below.
* Create an event listener for the button on your DOM that will trigger your API request when clicked.
* Use AJAX to make the request.
* Create objects out of the data returned. Each object should have a `render()` function that just returns a string of html that will eventually be appended to the DOM. You will also need a constructor attribute called `all` that's an array of all of your objects. Ex: if you're working with the Pokemon API each pokemon should be made into it's own object.
* Use jQuery to update the DOM by iterating through your `all` attribute and calling the `render()` function for each object within a jQuery append.

## Instructions

Use the index.js and index.html files in this repo to create your application. 

Notice that our HTML file is using a [CDN](https://en.wikipedia.org/wiki/Content_delivery_network) to grab the jQuery library and a script tag to load up our index.js. We have also brought in the [Bootstrap](https://getbootstrap.com/) library for some pretteh' stylin'.

## APIs

* [Reddit](https://www.reddit.com/.json) - just append /.json to the url you want to GET data from.
* [Pokemon](http://pokeapi.co/)
* [Deck of Cards](http://deckofcardsapi.com/)
* [Wikipedia](https://www.mediawiki.org/wiki/API:Main_page)
* [Google Books](https://developers.google.com/books/docs/v1/getting_started)