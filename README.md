# Dithering
Demonstration of image dithering (Ordered and Error Diffusion)
This a simple application of this blogpost: https://tannerhelland.com/2012/12/28/dithering-eleven-algorithms-source-code.html

1. Launch the top-level vi.

2. Choose a jpg to display (the companion cube is an example taken from the blogpost).

3. Select which algorithm to choose, among:

  Floyd-Steinberg
  
  Jarvis, Judice, and Ninke
  
  Stucki
  
  Atkinson
  
  Burkes
  
  Sierra, Two-Row Sierra, Sierra Lite
  Bayer 2*2, 4*4, 8*8
4. Stop with the "Stop" button.

![Example](https://github.com/Sylvain-Deposit/Dithering/blob/master/ExampleDithering.jpg)

There might be some white or black lines appearing on the display. This is not due to the algorithm, but bevause of the way Labview interpolate between data when using Intensity Graphs. 
It can be solved by rescaling the graph panel. 
