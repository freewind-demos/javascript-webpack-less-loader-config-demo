Webpack Css Loader Demo
=======================

```
npm install -g webpack
npm install
webpack ./entry.js bundle.js
```

Then open `index.html`

Note
-----

Or you can use:

```
webpack ./entry.js bundle.js --module-bind 'css=style!css'
```

that you can just write `require('./index.css')`
 in you js file.
