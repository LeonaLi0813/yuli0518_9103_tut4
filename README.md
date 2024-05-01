# yuli0518_9103_tut4
My first repository for IDEA9103

This is my first local change to the repo!

## Choose the technique
In the film **Doctor Strange**, Dr Strange would use magic to create a **circle** and was free to travel through space. And this magic circle would be accompanied by many **sparks**. I want to try to create such magic circle with sparks effect by using the code

[link of magic circle](https://www.youtube.com/watch?v=6BC_fbZoOdA)

![An image of the artwork](assets/magic%20circle.png)

### Blossom Particle

[link of making blossom particle in p5.js](https://editor.p5js.org/AnonymousPyro/sketches/Q2XUJXm5)

![An image of the example](assets/sparkle.png)
This is the code for an effect where particles bloom in the shape of a heart on mouse click. I think I can achieve the effect I want by turning the heart into a circle, and then changing the way the particles move, from clicking to automatic continuous emission.

**-Main code**

- Create an array of all particles 
  
  ```
  let particles = [];
  ```
- Use `function ContructHeart()`to Initialise all examples in the array.
  ```
  function ConstructHeart(h, k) {
  let partOfParticles = [];  
  }
  ```
- Create the centre of the heart and make it the central emission point of the particles.
  ```
  let center = createVector(h, k);  
  partOfParticles.push(center); 
  ```

- Print out the number of particles in the heart
  ```
  particles.push(partOfParticles);
  console.log(partOfParticles.length);
  ```
- Then use `function draw()` to paint the particles
