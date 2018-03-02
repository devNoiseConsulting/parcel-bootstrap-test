# Parcel Bootstrap Test
Testing to see what break my Parcel.JS Bootstrap production build


## Unknown browser major
```
> parcel build ./index.html --public-url ./

⏳  Building fontawesome-webfont.svg...
🚨  /Users/flynnmj/src/parcel-bootstrap-test/node_modules/bootstrap/dist/css/bootstrap.css:undefined:undefined: Unknown browser major
    at error (/Users/flynnmj/src/parcel-bootstrap-test/node_modules/autoprefixer/node_modules/browserslist/index.js:37:11)
    at Function.browserslist.checkName (/Users/flynnmj/src/parcel-bootstrap-test/node_modules/autoprefixer/node_modules/browserslist/index.js:320:18)
    at Function.select (/Users/flynnmj/src/parcel-bootstrap-test/node_modules/autoprefixer/node_modules/browserslist/index.js:438:37)
    at /Users/flynnmj/src/parcel-bootstrap-test/node_modules/autoprefixer/node_modules/browserslist/index.js:207:41
    at Array.forEach (<anonymous>)
    at browserslist (/Users/flynnmj/src/parcel-bootstrap-test/node_modules/autoprefixer/node_modules/browserslist/index.js:196:13)
    at Browsers.parse (/Users/flynnmj/src/parcel-bootstrap-test/node_modules/autoprefixer/lib/browsers.js:44:14)
    at new Browsers (/Users/flynnmj/src/parcel-bootstrap-test/node_modules/autoprefixer/lib/browsers.js:39:28)
    at loadPrefixes (/Users/flynnmj/src/parcel-bootstrap-test/node_modules/autoprefixer/lib/autoprefixer.js:56:18)
    at plugin (/Users/flynnmj/src/parcel-bootstrap-test/node_modules/autoprefixer/lib/autoprefixer.js:62:18)

```

## Links - I'm not the only one.
-   [Bootstrap issue](https://github.com/twbs/bootstrap/issues/25118)
-   [Parcel issue](https://github.com/parcel-bundler/parcel/issues/645)
-   [cssnano
issue](https://github.com/ben-eb/cssnano/issues/447)
