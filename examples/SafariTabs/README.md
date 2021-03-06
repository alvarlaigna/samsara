A demo of the Safari tab viewer on iOS. Clicking a tab makes it full screen (you can still scroll), 
clicking the `x` button removes the tab.

This demo features, physics, scrollview, size animation and 3D transforms.

To view this demo fullscreen on a mobile device, [click here](http://samsarajs.org/demos/SafariTabs/index.html)

## Installation

Open `index.html` in your browser. That's it!

## Documentation

If you open `docs/main.html` in your browser you will see pretty documentation, rendered with [docco](https://jashkenas.github.io/docco/).

##Bundling

If you'd like to bundle the application into a single JavaScript file, run the following:
 
```
	npm install
	npm run build
```

This will create a `build` directory with a bundled `app.js` and minified `app.min.js` files. Keep in mind
you will need to copy over other assets, such as images, fonts, CSS and the index.html file.
