## Local development

As usual, the best place to begin is:

```npm install``` or ```yarn```

Then to transpile and combine the JavaScript:

```npm run build```*

(This just runs the `rollup` commands for the app source code and the service worker script).

To run the app:

```npm start```*

Or you can use any static web server for the `public` directory - it's all just front-end.

To watch for changes (in a separate terminal):

```npm run watch```*

(This just uses `watch` to rebuild the JS when a change is detected in the src directory).

*NB. You should be able to replace `npm` with `yarn` here, but it's not working with yarn v0.15.1. 
Sounds like it should work once [this gets released](https://github.com/yarnpkg/yarn/pull/809).


## Snapwat the name

Snapwat is called Snapwat because it's a snapshot with "pwa" in it - for Progressive Web App. 
Also, it's abbreviated to SW, like Service Workers. Good eh?  It's pronounced "snap what?" to rhyme with snapshot. 
Any resemblance to other social apps is purely coincidental...


## Further reading

* [Things I learned making a PWA for 'super selfies'](https://medium.com/samsung-internet-dev/things-i-learned-making-a-progressive-web-app-for-super-selfies-49e76d154e4f)
* [Chrome Developers guide on capturing images](https://developers.google.com/web/fundamentals/native-hardware/capturing-images/).


## Credits and Thanks

* Emoji images provided free by [EmojiOne](http://emojione.com/).
* Icons by [Iconic](https://useiconic.com/).
* Camera shutter sound by [xef6](https://www.freesound.org/people/xef6/sounds/61059/).
* Thanks to Rich Harris for making a [rollup cache manifest example](https://gitlab.com/Rich-Harris/rollup-cache-manifest-example) 
for me (and for [rollup](http://rollupjs.org/) in general!)


## Contact

Please [tweet me](https://twitter.com/poshaughnessy) or email: peter dot oshaughnessy at gmail dot com.


# Licence

MIT
