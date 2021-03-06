# Modem.js
A lightweight JavaScript UI library in under 100 lines of code.

### Getting started
First, clone this repository.

![Clone this repo](../ezgif.com-video-to-gif.gif)

Then, create an `index.html` file with the following code:
````html
<div id="YourAppNameHere"></div>
````

After that, write this in a `.js` file:
````javascript
import { ModemCore } from 'modem_0.5-es.js';

var x = new ModemCore();
x.setup();
x.setElement("YourAppNameHere");
````
Finally, add elements using the `addComponent` method:

````javascript
x.addComponent("P", "Hello, World!");
````

### Contributing
Want to contribute? [Leave a pull request](https://github.com/redstone2010/modem-js/pulls) and we'll get to it as soon as possible.


Encountering bugs? Simply [file an issue](https://github.com/redstone2010/modem-js/issues) describing what happened and we'll fix it!

### More
(reserved for later)
