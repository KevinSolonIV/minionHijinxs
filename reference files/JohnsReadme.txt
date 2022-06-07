This is just a mock up of something I was brainstorming that you guys can play around with if you want.

If the any aspects conflict with what you work on tonight then feel free to edit at will.
If you load the html file up in your browser it should give you a mock up ui that lets us click the start game button and deals the cpu (top) and the player (bottom) 5 randomly generated cards each.

I tried to annotate the JS file to make things easy to follow.

Unless i'm mistaken, the class constructor and the first function(generateHand()) in the JS file would be our server side code and will return an array of 10 cards called generatedCards

I think this array is what we need to grab from our server side and await after we click the start game button

Then, the populateHand() and createDomObject() functions should allow our client side to use that array of 10 cards to both distribute the cards to the players and model them in the DOM.

NOTE: The generateHand() function in THIS foler is different than the one that I put into the JS file in the REPL so that function won't give the same outputs (but I think this version works better).

Feel free to make suggestions/edits!

[this is Kevin] I've integrated everything into the existing repl as a starting point for sat. evening's work session.