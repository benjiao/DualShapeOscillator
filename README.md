# Random Triggers
by Benjie Jiao

I based this oscillator model on All About Electronics' Exponential VCO article. I removed the exponential converter section and added some additional features.

### Inputs

*CV1* - DC voltage for controling pitch

*CV2* - Another DC voltage that can be added to CV2. 

### Output

*Audio Out* - An audio signal. Can be a triangle wave, square wave, or a blend of the two.

<img src="./Images/Scope - Triangle.png">

<img src="./Images/Scope - Square.png">

<img src="./Images/Scope - Blend.png">

### Controls

*Triangle* - Controls the amount of triangle wave blended into the output signal.

*Shape* - Controls the amount of square wave blended into the output signal. 

*CV2 Trim* - Controls how much of CV2 is added into CV1. This can be used to make modulation signals more subtle.

## Version History

**Version 1.0**
The initial version.
<img src="./DualShapeOscillator v1.0.svg">
