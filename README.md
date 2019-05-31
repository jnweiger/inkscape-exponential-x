Inkscape extension: exponential-x-axis
======================================

This [Inkscape](https://inkscape.org) extension transforms an object along the x-axis.
The bounding box remains unchanged. Points near the center of the object move to 
create the illusion of a curved surface.
Points move left, if you choose an exponent > 1, and right if the exponent is < 1.
An exponent of 1.0 does exactly nothing.
An optional (left side) padding can be applied to soften the effect.



<img src="https://raw.githubusercontent.com/jnweiger/inkscape-exponential-x-axis/master/exponential-x-demo.png"/>


This can be used in combination with the bend path effect to create a cone projection
that retains aspect ratio.

Caution: Finding correct parameters for e.g. a cone projection is left as an exercise to the user. 
