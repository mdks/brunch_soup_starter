# DWGP

Do Work Get Paid

An app that provides a means to input your verbal contract, e.g.:
	You can get paid up to $400 per month to be a mentor to someone else.
 
For your employer it is tough to know if you're doing your job right,
he has to bother you as well as your apprentice!

Use the app to design your responsibilities and keep track of your progress
by breaking things down into daily tasks.

Your employer can then check in and confirm your actions, 
confirmation will send you an appropriate amount of bitcoins.

App construction will begin atop [Brunch Socket Soup](https://github.com/pheuter/brunch-socket-soup)

## Ingredients

  * [Bootstrap](http://twitter.github.com/bootstrap/index.html)
  * [Stylus](http://learnboost.github.com/stylus/)
  * [Coffeescript](http://coffeescript.org/)
  * [Handlebars](http://handlebarsjs.com/)
  * [Mocha](http://visionmedia.github.com/mocha/)
  * [Backbone](http://backbonejs.com)
  * [Express](http://expressjs.com/)
  * [Socket.io](http://socket.io/ )

## Getting started

Make sure to have [Brunch.io](http://brunch.io) installed.

Prepare the bowl:

    brunch new <your-project-name> -s github://pheuter/brunch-socket-soup

Throw in the ingredients:

    npm install

Serve and take sips:

    coffee server.coffee && brunch watch
