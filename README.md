# Board4Free.js

I just started work this 3/14/15 and I've not done a whole lot yet.
This is a **work in progress** modification of the JavaScript port of the popular 1991 PC game [SkiFree](http://en.wikipedia.org/wiki/Skifree) by [Chris Pirih](http://ski.ihoc.net/).

[**You can play skifree.js by Dan Hough here**](http://basicallydan.github.com/skifree.js) (opens a demo page).

## Features so far:
* Being a snowboarder instead of a boring old skier.
* Skiing down a never-ending ski slope with randomly-generated trees which do not have transparent backgrounds
* Collision detection with trees - and the appropriate reaction
* Turning left and right
* Stopping
* MONSTAHS! GRAAAAHHH! They even eat you and then run away because they're full
* Distance tracking so you can see how far you've gone you absolute badass
* Speed boost (this was a little-known feature to get away from monsters) using the F key
* **MOBILE SUPPORT** - This is cool - try loading the [**the demo page**](http://basicallydan.github.com/skifree.js) on a mobile device and then use your finger to direct the skier around the pistle. Also try double-tap ;)
* Rainbow jump platforms & jumping - though a couple of improvements could be made
* LocalStorage high-score (thanks, [@ddoolin](https://github.com/ddoolin)!)
* Custom-sized Hitboxes
* Big trees & crashing into them both whilst boarding and jumping

## So, what's left to do?


* Stumps
* Dog
* Ski Lift
* Burning Tree
* Frozen Skier
* Killing Snow Monster
* Slalom Course


Some features which weren't in the original which I'd like to give a go:


* Ability to choose snowboarder or skier.
* Multiplayer (ooooo wouldn't that be fun?!)

## Let me play the game goddammit!

Game Controls:
================
Use the mouse, arrow keys or WASD to control the player.

F 			Player Speed Boost
T 			Player Attempt Trick While Jumping
M			Spawn Snow Monster
B 			Spawn Enemy Snowboarder
Space		Reset Game

MOBILE SUPPORT** - Use your finger to direct the snowboarder. Also try double-tap ;)



* Open up index.html in Chrome, or maybe even Firefox - I haven't tested it in anything but Chrome, and I probably won't I'm afraid
* Go.

## I like to run Unit tests before I do ANYTHING.

* Right, well first you need to do an `npm install`
* Run `mocha` and you should see some beautiful passing tests

## This is pretty frickin' sweet but it's clearly not finished. I can totally improve it. Let me improve it, dammit.

* Dan Hough is #seekingcontributors
* Make a pull request with your awesome additions.
* Maybe raise an issue?

## Contributors

Here's some lovely people who were kind enough to have opinions and spirit enough to make a pull request.

* [@tomgrim1](https://github.com/tomgrim1)
* [@ddoolin](https://github.com/ddoolin)
* [@andersevenrud](https://github.com/andersevenrud)

Thanks!

## Third-party credits

* [HTML5 Boilerplate](http://html5boilerplate.com) provided a bunch of useful markup and stuff
* [Wing Wang Wao](http://spriters-resource.com/submitter/Wing%20Wang%20Wao) of the [Spriters Resource Forum](http://spriters-resource.com) did an amazing job of providing the sprites which I have extended slightly. Thanks!
* Thank you [Chris Pirih](http://ski.ihoc.net/) for making the original.

## License

See [license.txt](blob/master/license.txt)
