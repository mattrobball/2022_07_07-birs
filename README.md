## A double feature derived categories talk

This is a talk I gave at the Banff International Research Station for the workshop
Derived categories, arithmetic, and reconstruction. 

As I couldn't choose a single topic, I decided to try a double feature. Perhaps 
it was doubly opaque. 

The presentation uses the [Reveal.js](https://revealjs.com/) framework, the 
[KaTeX](katex.org) engine to render math, and is hosted 
with [GitHub Pages](pages.github.com).

### Generation in prime characteristic 

Generators are essential to understand any algebraic structure and triangulated 
categories are no different. In this half(?) of the talk, we discuss joint work
with [Pat Lank](patlank.com) where we show that higher iterated pushforwards of 
the category perfect complexes under Frobenius generates the bounded derived 
category of a Noetherian F-finite scheme over a field of prime characteristic. 

### A GUT for flops and derived categories

We discuss a general proposal (or grand unified theory) for associating 
integral kernels to flips due to myself, Colin Diemer, and 
[David Favero](https://sites.ualberta.ca/~favero/). 

We focus on recent joint work with 
[Nitin Chidambaram](https://guests.mpim-bonn.mpg.de/kcnitin/") 
and David Favero where this construction is used to obtain Fourier-Mukai 
kernels for stratified Mukai flops. 

### Installation and use

Reveal.js comes with server which hot reloads on changes to the html files. If you 
don't have your own server, I recommend using this. 

To use this as template for your talk, first install node. The simplest way 
for an up-to-date version is via [npm](https://github.com/nvm-sh/nvm/blob/master/README.md). 
Then install [npm](https://www.npmjs.com/package/npm). 

Next, clone this repository. Inside the main folder of the repository, run 
`npm install` to build the node module dependencies. 

Run `npm start` to initialize the server. It will provide a url address for the server. 

Now edit `index.html` to author your talk and point your favorite browser to 
the url to see the results. 
