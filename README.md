# HW 0: Intro to Javascript and WebGL

<p align="center">
  <img width="360" height="360" src="https://user-images.githubusercontent.com/1758825/132532354-e3a45402-e484-499e-bfa7-2d73b9f2c946.png">
</p>
<p align="center">(source: Ken Perlin)</p>

[Live Demo Link] (https://diana-ou.github.io/hw00-intro-base/)

## Objective
- Start learning Typescript and WebGL2
- Practice implementing noise

## Inspiration
Coming fresh off of making mini-minecraft, I was looking to procedurally create a pixellated and unstable lava block. 

## The tools 
On the site, you will have customization with the following controls: 
* Shape: slider to change between cube, plane, and sphere view.
* Color: the primary base color of the lava block 
* Secondary Color: the secondary glow color of the lava block
* Pixellation: the amount the blocks are "pixellated"

## Implementation details
* Simple sine-based grow/shrinking + in-sync glow
* Random sine-based noise for the "shaking" of the vertices 
* Used worley noise as the backing lava cell shaping & protrusions
* "Bucketed" sampling locations for pixellated effect
