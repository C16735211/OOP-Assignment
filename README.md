# OOP-Assignment

# H1Assignment-1 O.O.P DT228/2

**R**

Main page includes the controlP5 and minim libraries as well as the sound AudioPlayer functions that are needed to import the required libraries that enable the program to function and display. PImages, radio buttons, radar interactions need these libraries to display the content and sound of all files and images. Variable, arrays, images and buttons are all declared and initialised on the R file page. Where the functions draw and setup enable the program to work. 

**Star class**

The start of the project I wanted to do a Halo HUD. I worked on the starfield at first after seeing a few of the previous students assignments we were shown in class. I wanted to create a hyperspace sound when traveling through the dimension, as you 
move the mouse across screen to the right the stars speed up giving you the feeling of travelling at high speed through space. Moving back across from right to left slows right down almost creating a stuck in time feeling as everything stops. The star class is made up of an array of size 800 which randomly creates the stars at different locations each frame rate at an angle that gives you a feeling of hurtling through space towards the planets.

**Planet class**

The planet class uses PVectors and PShapes and nicely displays the planets as spheres. They are positioned in the topleft corner of the screen they randomly select the planet texture each time the program is run. Example there could be two earths, mercurys etc. I had them at first in the center and used the function peasyCam which enabled you to zoom around the galaxy. However I couldn't get it to fully functioning to how I would like so I removed it. The planet class enables the orbitspeed, size and rotation of the planets, moons and the sun. I used PImage to import the wrap around textures of the planets, sun and moon.

**Sound frequency that changes/vibrates using the AudioPlayer player; // to activate audio frequency**
**ellipse(400, 650, player.left.get(1)*800, 50);**

The ellipse vibrates when the sound is played, you can use lines, or any shapes to implement this. On this occassion I used an ellipse.

**Orbiter class**

Orbiter class creates a portal like rotation image, I positioned it on the radar. I wanted to include cortana when activated. Cortana's voice is included through a .wav file telling the Master Chief that she wants to activte his suit to detect incoming enemy.

**WaveGraph class**

The wave graph class is when the enemy is within a certain radius the wave changes from a neutral/friendly green wave to an alert signal purple wave. This can be activated by the mouse cursor. HALO is dislayed in green when everything is safe and sound. Once activated the purple sine wave creates a purple ALERT INCOMING message to the Master Chief alerting him to the incoming danger.

**Ship class**

The ship class creates space ships limited to an arraylist of 4 for demo purposes, that I wanted to allow the user to be able to shoot down the space ships as you hurtle through space. Never got it to fully function to how I would have liked.

**Radar class**

The radar class is positioned to the bottom left corner it works with the orbiter class. The orbiter is displayed like a portal to activate cortana. 





