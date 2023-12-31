<h2>Introduction</h2>
Experiment with postcss using the plugin nanocss and postcss.config.js. postcss-cli invokes postcss via the package.json scripts 


<h2>Installation</h2>

```
pnpm i
```

<h2>Usage</h2>

```
npm run build-css-watch
```
Run index.html in the browser, and changing styles.css in the root directory will automatically change the file in the dist directory.



<h2>Points of interest</h2>
Compare the size of styles.css before nanocss minimizing - 163B with the CSS file in dist after nanocss processing - 39B. These files are the same concerning the view

<h2>More info</h2>
https://nathankrasney.com/posts/what-is-postcss

