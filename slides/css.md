<!-- .slide: data-background="img/every-thing-will-be-fine-jaymantri.jpg" data-background-size="cover" -->
## Every Thing Will Be Fine<!-- .element: class="fragment" data-fragment-index="1" -->

--

### A ~~better~~ *different* approach to CSS
1. Use a type scale<!-- .element: class="fragment" data-fragment-index="1" -->
2. Use a white space scale<!-- .element: class="fragment" data-fragment-index="2" -->
3. Utility classes… a lot of utility classes<!-- .element: class="fragment" data-fragment-index="3" -->

--

### Type Scale

- [type-scale.com](http://type-scale.com)
- [modularscale.com](http://www.modularscale.com)
- [gridlover.net/app](http://www.gridlover.net/app/)

--

### Type Scale

<iframe height="460" scrolling="yes" src="//type-scale.com" frameborder="no" style="width: 100%;">
</iframe>

--

## White Space Scale

--

<!-- .slide: data-background="img/spacing.png" data-background-size="cover" -->

--

### White Space Scale
### `0.5rem`, `1rem`, `2rem` & `4rem`

--

### Utility Classes

--

<!-- .slide: data-background="img/oocss.png" data-background-size="cover" -->

--

# Metrics
<small>https://www.chromestatus.com/metrics/css/popularity</small>

--

## Immutable Utilities

--

### Immutable Utilities

Provide the backbone for typography, layout and some core visual styles.

--

### Immutable Utilities

- Once set they should never be changed or extended.<!-- .element: class="fragment" data-fragment-index="1" -->
- Should contain just one or two styles.<!-- .element: class="fragment" data-fragment-index="2" -->

--

### Immutable Utilities
> Utilities should do one thing and do it well, they should be simple and obvious to use, and they should operate independently.

&raquo; [Basscss design principles](http://www.basscss.com/docs/reference/principles/#immutable-utilities)

--

### Immutable Utilities For

- Type: `h1 - h6`
- [White space (padding & margin)](http://www.basscss.com/docs/white-space)
- Colours: `text and background`
- Borders
- [Layout](http://jxnblk.com/gravitons)
- Animations

--

<!-- .slide: data-background="img/people.png" data-background-size="cover" -->

--

### Thinking in Components

- Your app/site is just a collection of components
- Each component is independent and self sufficient

--

### Thinking in Components

- Let the JS drive components
- Wait for a pattern to appear before defining a component

--

### Thinking in Components
- Components should be responsive
- Expand to fit its parent – `100%` width
- Layout/core visual styling comes from the utility classes

--

### Basscss | Gravitons | Tachyons

--

Write Less CSS and Iterate Faster

--

<iframe height="480" scrolling="no" src="//codepen.io/winkerVSbecks/embed/vNBBJO/?height=480&theme-id=8427&default-tab=result" frameborder="no" allowtransparency="true" allowfullscreen="true" style="width: 100%;">
</iframe>

<small>http://codepen.io/winkerVSbecks/pen/vNBBJO</small><br/>
<small>http://s.codepen.io/winkerVSbecks/debug/vNBBJO</small>

--

### BEM
```css
  .header-bar { … }
  .header-bar__title { … }
  .header-bar__actions { … }

  .card { … }
  .card__body { … }
  .card__figure { … }
```

--

## [CSS Lego](http://www.basscss.com/docs/guides/ui)

BEM + OOCSS

--

### Scalability

- Single purpose classes
- Easy to understand
- Easier to reason about cascading
- No fear of impact
- Get in, update styles & get out
