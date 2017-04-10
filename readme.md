[DEMO IS HERE]

A proposition of what a carousel can be. Each slide on a carousel is a set of hexagon cells. Feels like a honeycomb.
Motivation: Sometimes hexagon is better than rectangle.
Dependancies: No dependancies required: only native JavaScript used.

How to see: download zip, unpack, open index.html in browser. On webpage everything is super self-explanatory. Works on modern browsers.

How to use: After loading script honeycomb.js and a stylesheet honeycomb.css on html-page there will be global object named honeycomb.
Honeycomb has only one method: createHoneycomb(el, data).
Accepts two parameters: el - a html element in which honeycomb will be inserted into.
data - array of datasets for each cell in honeycomb. Each element in array expected to contain following properties:
{
topText:"some text above header, it should be very small, space is limited",
headerText: "header, should be short",
bodyText: "text for the body can be longer...",
buttonText: "short text for button, be informative",
backgroundImageUrl:"some url for background image",
cellBottomButtonFunction: function(){alert("function that launches on button click in cell");}
}

Please don't judge too hard. This is a prototype of a proposition. So don't expect it to be stable, reliable or whatever else good it can be.

[//]: #
[DEMO IS HERE]: <https://3-4rm.github.io/honeycomb/>
