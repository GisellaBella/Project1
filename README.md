# Project1

<h1>Artist Match Memory Game</h1>

Inspired by my time spent earning a BFA and “learning slides.” I originally envisioned it being less visual and more of a learning tool. 
Play It here: https://gisellabella.github.io/gisellabella/


A simple memory game developed in vanilla javascript with the subtle minty hint of jQuery.

I use dom manipulation to dynamically generate the game, track the activity, and determine matches.

One of the biggest challenges in creating this was working with the images, and arrays. I couldn't get the image values to pass and the image to show. I tried creating the img src property in the array but it would just create an object[object] error (as the "internets" recommended.) I struggled mightily figuring out the best way to not only show images but also pass the attribute back to the app for the logic, finally settling on a "hack" with string values. Works beautifully now.

Unsolved problems include first-click gives a "not a match error", will try to resolve.
Would love to include a dynamic database of images. Currently, it is hard coded  to show eight images.

