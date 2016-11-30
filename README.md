# Project1

Artist Match Memory Game
Inspired by my time spent earning a BFA and “learning slides.” I originally envisioned it being less visual and more of a learning tool. 
Play It here: https://gisellabella.github.io/gisellabella/


A simple memory game developed in vanilla javascript with the subtle minty hint of jQuery.

I use dom manipulation to dynamically generate the game.

One of the biggest challenges in creating this was workign with the images, and arrays. I couldnt get the image values to pass and the image to actually show. I tried creating the img src property in the array but it woudl just create an object[object] error (as the "internets" recommended.) I struggled mightily figuring out the best way to not only show images, but also pass the attribute back to the app to write the logic, finally settling on a hack with "strings". Works beautifully now.

Unsolved problems first click gives me the not a match error, will try to resolve.
Would love to have a more dynamic database of images. Currently it is hard coded to only show the same 8 image over and over.

