<h2>Introduction</h2>
Experiment with postcss using the plugins nanocss and postcss-preset-env via postcss.config.js. postcss-cli invokes postcss via the package.json scripts 


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
<ul>
<li>Use packages postcss and postcss-cli to invoke the postcss plugin nanocss. </li>
<li>Install packages postcss , postcss-cli and nanocss as dev dependencies because postcss is done on development </li>
<li>Compare the size of styles.css before nanocss minimizing - 163B with the CSS file in dist after nanocss processing - 39B. These files are the same concerning the view</li>
<li>Use postcss-preset-env here to convert CSS nesting to CSS format known to most browsers (e.g. CSS nesting is supported in chrom 120; check <a href='https://developer.mozilla.org/en-US/docs/Web/CSS/Nesting_selector'>here</a>)</li>
</ul>


<h2>More info</h2>
https://nathankrasney.com/posts/what-is-postcss

