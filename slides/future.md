
<!-- .slide: data-background="#ffcc33" class="th-yellow" -->
# PostCSS

--

### PostCSS

1. API for transforming styles with JS
2. The PostCSS plugin ecosystem

--

### Some PostCSS Plugins

- `autoprefixer` adds vendor prefixes
- `cssnano` optimize CSS size for use in production
- `cssnext` use future CSS features today
- `stylelint` lint your stylesheets

--

### What Else Can PostCSS Plugins Do
- Future CSS Syntax
- Fallbacks
- Language Extensions
- Colors
- Optimizations
- Sass in your CSS!
- etc.

--

### Usage

```js
var postcss = require('postcss');

postcss(['autoprefixer', 'cssnano', 'stylelint'])
  .process(css, {
    from: 'src/app.css',
    to: 'app.css',
    map: { inline: true }
  })
  .then(function (result) {
    fs.writeFileSync('app.css', result.css);
    if ( result.map ) fs.writeFileSync('app.css.map', result.map);
  });
```

--

### Usage

- Gulp plugin
- Webpack loader

--

## Immutable CSS

- A CSS linter for immutable selectors
- Written using PostCSS

--

## Immutable CSS

- Ensures that CSS imported from libraries is not modified
- Ensures that selectors are used once only

&raquo; [immutablecss.com](http://immutablecss.com)

--

## Future Stack

- `Sass` ➡ `CSS Next`
- `Bourbon` ➡ `Autoprefixer`
- `Bootstrap` ➡ `Basscss`
- `scss-lint` ➡ `stylelint` & `postcss-bem-linter` (?)
- `immutable-css`

--

### CSS Next?

```css
/* custom properties */
:root {
  --fontSize: 1rem;
}

/* custom media queries */
@custom-media --viewport-medium (width <= 50rem);

/* some var() & calc() */
body {
  font-size: var(--fontSize);
  line-height: calc(var(--fontSize) * 1.5);
}

/* custom media query usage */
@media (--viewport-medium) {
  body { font-size: calc(var(--fontSize) * 1.2); }
}
```

http://cssnext.io/playground
