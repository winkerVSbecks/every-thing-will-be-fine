<!-- .slide: data-background="#ffcc33" class="th-yellow" -->
# Prototyping

--

<!-- .slide: data-background="img/build.png" data-background-size="cover" -->

--

<!-- .slide: data-background="#fff" -->
<img src="img/sprint-diagram.png"
  width="400px">

--

### Prototyping Is Great for Figuring Out

- The What? <!-- .element: class="fragment" data-fragment-index="1" -->
- and the Why? <!-- .element: class="fragment" data-fragment-index="2" -->

---

<!-- .slide: data-background="#ffcc33" class="th-yellow" -->
## Designing With Code

--

Find the answer to *the how?*

--

### Designing With Code

- Promotes designers & developers to collaborate early<!-- .element: class="fragment" data-fragment-index="1" -->
- The team can continue iterating and reduce the gap between building and learning<!-- .element: class="fragment" data-fragment-index="2" -->

--

# UI Developer

---

<!-- .slide: data-background="#ffcc33" class="th-yellow" -->
# The Problem

--

<iframe height="480" scrolling="no" src="//codepen.io/winkerVSbecks/embed/vNBBJO/?height=480&theme-id=8427&default-tab=result" frameborder="no" allowtransparency="true" allowfullscreen="true" style="width: 100%;">
</iframe>

<small>http://s.codepen.io/winkerVSbecks/debug/vNBBJO</small>

--

### The CSS

```css
  .header-bar { … }
  .header-bar__title { … }
  .header-bar__actions { … }

  .card { … }
  .card__body { … }
  .card__figure { … }
```

--

### What Problem Are
### You Trying to Solve?

<svg class="lg-svg-icon" viewBox="0 0 20 20">
  <path d="M10.25,2.375c-4.212,0-7.625,3.413-7.625,7.625s3.413,7.625,7.625,7.625s7.625-3.413,7.625-7.625S14.462,2.375,10.25,2.375M10.651,16.811v-0.403c0-0.221-0.181-0.401-0.401-0.401s-0.401,0.181-0.401,0.401v0.403c-3.443-0.201-6.208-2.966-6.409-6.409h0.404c0.22,0,0.401-0.181,0.401-0.401S4.063,9.599,3.843,9.599H3.439C3.64,6.155,6.405,3.391,9.849,3.19v0.403c0,0.22,0.181,0.401,0.401,0.401s0.401-0.181,0.401-0.401V3.19c3.443,0.201,6.208,2.965,6.409,6.409h-0.404c-0.22,0-0.4,0.181-0.4,0.401s0.181,0.401,0.4,0.401h0.404C16.859,13.845,14.095,16.609,10.651,16.811 M12.662,12.412c-0.156,0.156-0.409,0.159-0.568,0l-2.127-2.129C9.986,10.302,9.849,10.192,9.849,10V5.184c0-0.221,0.181-0.401,0.401-0.401s0.401,0.181,0.401,0.401v4.651l2.011,2.008C12.818,12.001,12.818,12.256,12.662,12.412"></path>
</svg>

--

We keep solving the same problem over and over again

--

![](img/css.gif)

--

Our focus should be the UI and the crafting the user interaction. Not fighting CSS.

---

<!-- .slide: data-background="img/relax-brandon_lam.jpg" data-background-size="cover" -->
## Relax<!-- .element: class="fragment" data-fragment-index="1" -->
### Take a deep breath<!-- .element: class="fragment" data-fragment-index="2" -->

--

<!-- .slide: data-background="img/every-thing-will-be-fine-jaymantri.jpg" data-background-size="cover" -->
## Every Thing Will Be Fine

--

### A ~~better~~ *different* approach to CSS
1. Use a type scale<!-- .element: class="fragment" data-fragment-index="1" -->
2. Use a white space scale<!-- .element: class="fragment" data-fragment-index="2" -->
3. Utility classes<!-- .element: class="fragment" data-fragment-index="3" -->

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

### Utility Classes For

- Type
- White space (padding & margin)
- Colours
- Borders
- Layout

--

### Basscss | Gravitons | Tachyons

--

### Thinking in Components

- Your app/site is just a collection of components
- Each component is independent and self sufficient

--

### Thinking in Components
- Components should be responsive
- Expand to fit the parent – `100%` width
- Layout comes from the utility classes

--

<iframe height="480" scrolling="no" src="//codepen.io/winkerVSbecks/embed/vNBBJO/?height=480&theme-id=8427&default-tab=result" frameborder="no" allowtransparency="true" allowfullscreen="true" style="width: 100%;">
</iframe>

<small>http://codepen.io/winkerVSbecks/pen/vNBBJO</small><br/>
<small>http://s.codepen.io/winkerVSbecks/debug/vNBBJO</small>

