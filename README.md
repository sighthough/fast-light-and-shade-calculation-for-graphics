# fast-light-and-shade-calculation-for-graphics
tech demo of fast light and shade calculations for graphics

the main idea was to take the light value from the faces of the 3d object and use them as the opposite if its on the backside 
so that evolved to taking the calculations of the back part of the normal 
and lets say its light is 0.8 and max value is 1 
you do 1-0.8 so you figure out it should have 0.2 light on the back
with multiple lights it gets trickier as you have to divide by the number of lights only the luminocity value
lets say light A is 0.2 calculated and light b is 0.3 calculated on the backside what you would do 
is 0.2 + 0.3 /2 (number of lights) so 0.5 /2 = 2.5 total value and you would give each light half of it
so each light would get 1.25 light value to it so it would add up to 2.5 total for that side 

[here is a tech demo](https://sighthough.github.io/fast-light-and-shade-calculation-for-graphics/)
idk if its done 100 percent right as i used ai for it but its something 
feel free to rip anything you want from this its mit licensed 

