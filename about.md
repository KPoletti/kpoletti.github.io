---
layout: about
title: About
---

<!-- al -->
<!-- Random image from Zach Stoebner-->
<div id="random-image"></div>

<script>

// **when adding new images, run rename_images.py and paste output here**
var images = ['1.jpg', '2.jpg', '3.jpg', '4.jpg'];  

// Function to select and display a random image
function displayRandomImage() {
    var randomImage = images[Math.floor(Math.random() * images.length)];
    var imgElement = `<img src="assets/images/profiles/${randomImage}" alt="random image of Keith Poletti" style="height:500px;max-width:100%;" >`;
    document.getElementById("random-image").innerHTML = imgElement;
}

// Call the function to display the random image
displayRandomImage();
</script>

## About Me

:wave:: Hi, I'm Keith Poletti, a data scientist, ML researcher, and engineer.
I completed my Master's in Computational Science, Engineering, and Mathematics at UT Austin,
and my advisors were [Dr. Stella S. R. Offner](https://sites.google.com/view/stellaoffner/home) and [Dr. Rachel A. Ward](https://sites.google.com/prod/view/rward/home).
My research interests include Scientific Machine Learning, Uncertainty Quantification, and Bayesian Inference.
I worked on developing neural operators to aid in solving partial differential equations and inverse problems in star formation.

For my undergrad, I majored in Astrophysics and Aerospace Engineering from the University of Colorado Boulder. I researched [image tracking software](https://github.com/KPoletti/GaN-NanoWire-Image-Tracking-) for GaN nanowires with [Dr. Charles Rogers](https://spot.colorado.edu/~rogersct/index.html) and [Dr. Daniel Dessau](https://dessau.appspot.com/). Later as part of Dr. Robert Marshall's [LAIR Lab](https://culair.weebly.com/), I designed, tested, and manufactuered very low frequency analog circuit board for the [CANVAS CubeSat](https://culair.weebly.com/canvas.html).

My Links
- [GitHub](https://github.com/KPoletti/)
- [LinkedIn](https://www.linkedin.com/in/keith-poletti/)

#### Personal

I enjoy climbing, running, and film photography in my free time. When not doing one of those things, I am probably listening to an album or watching a movie.
#### Side Quests
- [Album per Day](/sideQuests/album)
- [Marathon Training](https://blue-tarsier-068.notion.site/Best-Little-Marathon-Plan-in-Texas-bd873a0100cc4dbc8e8aab4ef1a37f60)
- [Film Photography](/sideQuests/film)
