For this piece, I decided to create something similar to an audio visualizer. I used sliders to create the visual and then I
colored the "on" configuration individually, trying to represent the color scale to make it visually appealing and interesting. 
For the sound, I used a basic makenote setup that is randomized but also scaled to generate the numbers in a certain numeric area. I also
set the duration of the sound to 700 to not make it overlap, but also not make it short that you can barely hear it. The scaling is set as 
so to make sure that the volume does not fall below 50 so that you can still hear the sound, and of course maxing at 127. For the makenote 
itself, I scaled it so that the sound will not go too low and not too high as well, so a balance. After that, its all packed and then sent
to midiformat and then out to the sliders which react to the volume and velocity of the sound. 
