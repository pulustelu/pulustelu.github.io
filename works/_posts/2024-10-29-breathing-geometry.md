---
layout: post
title: Breathing Geometry
slug: breathing-geometry
links:
    project website: https://olivialta.cc/breathing-geometry
    update blog: https://olivialta.cc/blog/breathing-breathing-geometry
---

{% include fig
    video="/assets/images/works/breathing-geometry/loop.webm"
    width="567"
    alt="a rotating tetrahedron, slowly pulsating to and from a sphere as if breathing"
%}

A breathing exercise with a geometric companion.

<!--more-->

I like geometric shapes, patterns, and symmetries. So when I took a university mathematics course on these topics, and had the opportunity to explore them visually through a project, I was delighted! I chose to create a breathing exercise which takes the form of pulsating geometric shapes -- with subtle detail showing off the [fundamental domain] of their [symmetry groups][symmetry group].

When working with mathematical content (or more generally "real" data, a la [sonification]), it's relevant to consider whether you're creating a piece of art or whether you're creating a visualization. To a first order, I might differentiate the two based on the amount of creative decision making used for a piece, but obviously such a border is fuzzy. Nevertheless I strived to create a piece that demonstrates some tangible mathematical idea, that is also experientially interesting in some form.

I wanted to explore the connection between [platonic solids][platonic solid] and their [spherical geometries][spherical geometry] in a way that bridged the intuitive gap between the two. I played with continuously transforming solids into spheres, and found that to be an interesting visual effect. I chose the form of a breathing exercise, because my explorations reminded me of a particular breathing exercise I had seen on social media some years ago: 

{% include fig
    img="/assets/images/works/breathing-geometry/shapes.gif"
    alt="regular polygons slowly morphing into each other to the rhythm of deep breathing"
    cap="The gif (crunchy) in question. The original source is hard to find; this gif is to my knowledge at least 10 years old."
%}

Most of my decisions were made to accomodate for relaxation. One of my choices was to refer to the shape as a companion, a characterization that forms an unlikely human connection to the page and helps with grounding. I was also particularly proud of the slow "sleep" fade, where the entire UI of the page starts to wash away after some time spent idle, leaving only the companion in the middle of the screen. I have found myself using this page to relax myself as well. I particularly enjoy the tetrahedron and the way it seems to stretch beyond its capacity, but have great empathy towards all of the companions.

{% include fig
    img="/assets/images/works/breathing-geometry/page.png"
    cap="screenshot of the Breathing Geometry web page"
%}

On the technical side, I chose to use WebGL and JavaScript to render and manipulate 3D meshes. This worked as a "sanity check" to make sure that this idea was doable in the first place, plus helped me build my web / graphics coding skills. Perhaps [p5.js] would have been an easier choice for this, but I was happy to learn the fundamentals of web-based graphics as well.

[fundamental domain]: https://en.wikipedia.org/wiki/Fundamental_domain
[symmetry group]: https://en.wikipedia.org/wiki/Symmetry_group
[sonification]: https://en.wikipedia.org/wiki/Sonification
[platonic solid]: https://en.wikipedia.org/wiki/Platonic_solid
[spherical geometry]: https://en.wikipedia.org/wiki/Spherical_geometry
[p5.js]: https://p5js.org/