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

<p>Find the answer to *the how?*</p><!-- .element: class="fragment" data-fragment-index="1" -->

--

### Why Designing With Code?

- Promotes designers & developers to collaborate early<!-- .element: class="fragment" data-fragment-index="1" -->
- Reduces the gap between building and learning – iterate faster<!-- .element: class="fragment" data-fragment-index="2" -->
- Establishes the “UI Developer/Designer” role<!-- .element: class="fragment" data-fragment-index="3" -->
- Problems related to the “fluid canvas” become more obvious<!-- .element: class="fragment" data-fragment-index="4" -->
- Start delivering value early<!-- .element: class="fragment" data-fragment-index="5" -->

---

<!-- .slide: data-background="#ffcc33" class="th-yellow" -->
# The Problem

--

<iframe height="480" scrolling="no" src="//codepen.io/winkerVSbecks/embed/vNBBJO/?height=480&theme-id=8427&default-tab=result" frameborder="no" allowtransparency="true" allowfullscreen="true" style="width: 100%;">
</iframe>

<small>http://s.codepen.io/winkerVSbecks/debug/vNBBJO</small>

--

### The First Iteration

```css
  .header-bar { … }
  .header-bar__title { … }
  .header-bar__actions { … }

  .card { … }
  .card__body { … }
  .card__figure { … }
```

--

### The Second Iteration

~~Card + Graph~~ List + Numbers

--

1. Throwing away code<!-- .element: class="fragment" data-fragment-index="1" -->
2. Start building the new component<!-- .element: class="fragment" data-fragment-index="2" -->
3. Writing more  CSS for it<!-- .element: class="fragment" data-fragment-index="3" -->
4. Wasting time<!-- .element: class="fragment" data-fragment-index="4" -->

--

### What Problem Are
### You Trying to Solve?

<svg class="lg-svg-icon" viewBox="0 0 20 20">
  <path d="M10.25,2.375c-4.212,0-7.625,3.413-7.625,7.625s3.413,7.625,7.625,7.625s7.625-3.413,7.625-7.625S14.462,2.375,10.25,2.375M10.651,16.811v-0.403c0-0.221-0.181-0.401-0.401-0.401s-0.401,0.181-0.401,0.401v0.403c-3.443-0.201-6.208-2.966-6.409-6.409h0.404c0.22,0,0.401-0.181,0.401-0.401S4.063,9.599,3.843,9.599H3.439C3.64,6.155,6.405,3.391,9.849,3.19v0.403c0,0.22,0.181,0.401,0.401,0.401s0.401-0.181,0.401-0.401V3.19c3.443,0.201,6.208,2.965,6.409,6.409h-0.404c-0.22,0-0.4,0.181-0.4,0.401s0.181,0.401,0.4,0.401h0.404C16.859,13.845,14.095,16.609,10.651,16.811 M12.662,12.412c-0.156,0.156-0.409,0.159-0.568,0l-2.127-2.129C9.986,10.302,9.849,10.192,9.849,10V5.184c0-0.221,0.181-0.401,0.401-0.401s0.401,0.181,0.401,0.401v4.651l2.011,2.008C12.818,12.001,12.818,12.256,12.662,12.412"></path>
</svg>

--

![](img/css.gif)

We keep solving the same problems over and over again

--

Our focus should be the UI and the crafting the user interaction. Not fighting CSS.

--

Ideation <svg class="svg-icon" viewBox="0 0 20 20">
  <path style="fill: #fff" d="M12.319,5.792L8.836,2.328C8.589,2.08,8.269,2.295,8.269,2.573v1.534C8.115,4.091,7.937,4.084,7.783,4.084c-2.592,0-4.7,2.097-4.7,4.676c0,1.749,0.968,3.337,2.528,4.146c0.352,0.194,0.651-0.257,0.424-0.529c-0.415-0.492-0.643-1.118-0.643-1.762c0-1.514,1.261-2.747,2.787-2.747c0.029,0,0.06,0,0.09,0.002v1.632c0,0.335,0.378,0.435,0.568,0.245l3.483-3.464C12.455,6.147,12.455,5.928,12.319,5.792 M8.938,8.67V7.554c0-0.411-0.528-0.377-0.781-0.377c-1.906,0-3.457,1.542-3.457,3.438c0,0.271,0.033,0.542,0.097,0.805C4.149,10.7,3.775,9.762,3.775,8.76c0-2.197,1.798-3.985,4.008-3.985c0.251,0,0.501,0.023,0.744,0.069c0.212,0.039,0.412-0.124,0.412-0.34v-1.1l2.646,2.633L8.938,8.67z M14.389,7.107c-0.34-0.18-0.662,0.244-0.424,0.529c0.416,0.493,0.644,1.118,0.644,1.762c0,1.515-1.272,2.747-2.798,2.747c-0.029,0-0.061,0-0.089-0.002v-1.631c0-0.354-0.382-0.419-0.558-0.246l-3.482,3.465c-0.136,0.136-0.136,0.355,0,0.49l3.482,3.465c0.189,0.186,0.568,0.096,0.568-0.245v-1.533c0.153,0.016,0.331,0.022,0.484,0.022c2.592,0,4.7-2.098,4.7-4.677C16.917,9.506,15.948,7.917,14.389,7.107 M12.217,15.238c-0.251,0-0.501-0.022-0.743-0.069c-0.212-0.039-0.411,0.125-0.411,0.341v1.101l-2.646-2.634l2.646-2.633v1.116c0,0.174,0.126,0.318,0.295,0.343c0.158,0.024,0.318,0.034,0.486,0.034c1.905,0,3.456-1.542,3.456-3.438c0-0.271-0.032-0.541-0.097-0.804c0.648,0.719,1.022,1.659,1.022,2.66C16.226,13.451,14.428,15.238,12.217,15.238"></path>
</svg> Learning
