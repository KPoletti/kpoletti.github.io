---
layout: about
title: Daily Albums
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

## Daily Albums for 2024

:musical_note: I am listening to an album every day in 2024. Here are the some of the albums I have listened to so far:
![October 16,2024](https://open.spotify.com/album/1pOl0KEC1iQnA6F0XxV4To)
![October 15,2024](https://open.spotify.com/album/0A13JySVHzBoRZFk2o89Wl)
![October 14,2024](https://musicboard.app/album/automata-ii/between-the-buried-and-me/)