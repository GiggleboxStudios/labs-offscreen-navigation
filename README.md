
# Labs: Offscreen Navigation

> [Demo Link - http://giggleboxstudios.net/labs/offscreen-navigation/](http://giggleboxstudios.net/labs/offscreen-navigation/)

This is a simple framework for an offscreen navigation panel. My implementation is loosely based on the Codrops [multi-level push menu](http://tympanus.net/codrops/2013/08/13/multi-level-push-menu/) demo, however their design and implementation wasn't flexible enough for my needs. So I'm trying to build a better one that's easier to implement.

This implementation assumes a singular master level offscreen nav and currently doesn't support multiple offscreen navigation menus (yet).


## Get started:
1. `git clone` _OR_ download this repo and install it into a working localhost directory
1. ensure bower is installed globally via terminal `npm install -g bower`
1. `cd` into your working directory and run bower `bower install`
1. open your page in a web browser to view the results


### Features:

``` sass
// FILE: "css/offcanvas-structure.less"
// Make offscreen nav slide in from left
@menu-anchor:   left;

// Make offscreen nav slide in from right
@menu-anchor:   right;
```


## Dependencies
- [Node.js &amp; NPM](http://nodejs.org/) _[NPM comes installed with Node.js]_
- [Bower NPM module](https://www.npmjs.org/package/bower)
- JS: Modernizr.js _[installed via Bower]_
- JS: jQuery 1.8+ _[installed via Bower]_
- Pretty sure you could use Zepto if you REALLY wanted to ;)


## Support
If you find an issue with this repo, please report it in [issues](https://github.com/GiggleboxStudios/labs-offscreen-navigation/issues).


## Browser Support
- Chrome (Win, Mac, iOS)
- Firefox (Win, Mac)
- Safari 7 (Mac, iOS)
- Opera (Win, Mac)

_Need to test..._
- IE 9+
- Chrome (Android)
- Safari 7 (Win)
- Safari 6 (Win, Mac, iOS)
- Native Android browser
