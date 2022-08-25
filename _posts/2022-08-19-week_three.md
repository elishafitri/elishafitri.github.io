---
layout     : post
title      : "p5: Development"
date       : 2022-08-19
categories : Creative Coding
---

## W3-4
Here is the final product!
<iframe width=576 height=366 style="display: block; margin: 0 auto" src="https://editor.p5js.org/elishafitri/full/kwDo6BLOw"></iframe> 
 

### Process
Following my initial experiments with the falling text on mouse click, I came up with a concept for the project assignment: a scavenger hunt!
  
  I came up with the idea as I was playing around with this function, thinking about how I could turn it into a simple game. I did some more exploring with this function, using if else statements to create boundaries on the x-axis for the words "Creative Coding Specialisation". Each word would fall in a limited section of the screen so that the words could be read in order. An array is used for the coordinates (xpos, ypos) where each word would "drop".

  <iframe width=576 height=366 style="display: block; margin: 0 auto" src="https://editor.p5js.org/elishafitri/full/ZaJI_v3fN"></iframe>


  <br>
  In addition to this, I browsed through the RMIT Brand Guidelines document and found that the uni logo would be the perfect piece of treasure to find. With this in mind, I then went about trying to find out how to create custom shapes in p5. Although it would be easier to use the image as an asset, I wanted to explore how I could create a custom shape in p5.
     

  I first explored custom shapes (learning from [The Coding Train's tutorial](https://www.youtube.com/watch?v=76fiD5DvzeQ)) by using `beginShape ()`:

<iframe width=400 height=442 style="display: block; margin: 0 auto" src="https://editor.p5js.org/elishafitri/full/qzBzoP_BC"></iframe>
  
  <br>

  Then, I found this [great reference by sgrigg](https://editor.p5js.org/sgrigg/sketches/Ui6KxnBzh), who used an array to combine shapes together. I figured that the RMIT logo was just three shapes put together: a semi-circle, a rectangle, and a smaller rectangle;so I created those shapes using the individual shape functions and positioned them together.

  I ended up creating this:

<iframe width=400 height=442 style="display: block; margin: 0 auto" src="https://editor.p5js.org/elishafitri/full/k7u_1dvnT"></iframe>
  
  
  Now, all I had to do was combine this concept with the dropping words, and I would have my mini scavenger hunt! To add something interesting in the background, I used the same bouncing shape in the original header, but used a big fat ellipse instead. In doing so, I was able to explore using pi to create a kind of stylised sine wave graph. 
    
  And that's how i got to the final product! Thanks for taking the time to read my blog and I hope you've enjoyed reading about the my journey on this project.
  

