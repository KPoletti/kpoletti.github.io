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

:wave: Hi, I'm Keith Poletti, a data scientist, ML researcher, and grad student.
I'm currently pursuing a PhD in Computational Science, Engineering, and Mathematics at UT Austin and I am advised
by [Dr. Stella S. R. Offner](https://sites.google.com/view/stellaoffner/home) and [Dr. Rachel A. Ward](https://sites.google.com/prod/view/rward/home).

My research interests include Scientific Machine Learning, Uncertainty Quantification, and Bayesian Inference.
At the moment, I am working on developing neural operators for solving partial differential equations and inverse problems in astrophysics.

My Links
- [GitHub](https://github.com/KPoletti/)
- [LinkedIn](https://www.linkedin.com/in/keith-poletti/)

#### Personal
In my free time, I enjoy climbing, running, and film photography. When I am not doing one of those things, I am probably listening to an album or watching a movie.

#### Side Quests
- [Album per Day](/sideQuests/album)
- Marathon Training
- Film Photography
