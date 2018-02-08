# DWGP

App construction will begin atop [Brunch Socket Soup](https://github.com/pheuter/brunch-socket-soup)

## References

[Bitcoin on Node.js](https://en.bitcoin.it/wiki/API_reference_\(JSON-RPC\)#Node.js)

[Bitcoin API calls](https://en.bitcoin.it/wiki/Original_Bitcoin_client/API_calls_list)

## Ingredients

  * [Bootstrap](http://twitter.github.com/bootstrap/index.html)
  * [Stylus](http://learnboost.github.com/stylus/)
  * [Coffeescript](http://coffeescript.org/)
  * [Handlebars](http://handlebarsjs.com/)
  * [Mocha](http://mochajs.org/)
  * [Backbone](http://backbonejs.com)
  * [Express](http://expressjs.com/)
  * [Socket.io](http://socket.io/ )

## Getting started

Make sure to have [Brunch.io](http://brunch.io) installed.

Prepare the bowl:

    brunch new <your-project-name> -s github://pheuter/brunch-socket-soup

Throw in the ingredients:

    npm install

Start the SERVER

    coffee server.coffee

Start the APP

    brunch watch

Go to http://localhost:3000

Don't forget tests:
    
    mocha --compilers coffee:coffee-script  
