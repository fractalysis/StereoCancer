# StereoCancer
An open-source stereo-correct screen-space shader for Unity, mainly intended for usage in animations and games such as VRChat.

![](https://github.com/xwidghet/StereoCancer/blob/master/Example%20Gifs/kaleidescope_and_voroni_shader.gif?raw=true)
![](https://github.com/xwidghet/StereoCancer/blob/master/Example%20Gifs/overboard_shader.gif?raw=true)

# Features (Shown above)
Image Overlay (Blended, Tiled, Clamped, Alpha-CutOff)  
Rotation  
Movement  
Skew  
Bar  
ZigZag  
Wave  
Checkerboard  
Quantization  
Ring Rotation  
Warp  
Spiral  
Fish Eye  
Kaleidoscope  
Simplex Noise  
Voroni Noise  
Geometric Dither  
Stripes  
HSV Color Adjustment  
Chromatic Abberation  
Scalable Static/TV Noise (Referred to as Signal Noise)  
RGB Color Displacement (Referred to as Red/Green/Blue Move)  
Screen-Space Shader Opacity

# Usage
1. Create a cube.
2. Adjust the scale of the cube. Anyone who enters the cube, or sees the cube, will see the screen-space shader. The screen-space shader effects are independent of the object scale. So if you find it was too big or small, you can always adjust it later.
3. Add StereoCancer to your unity project.
4. Create a material from the StereoCancer shader, and put it on the cube.
5. Adjust the parameters on the material to your liking, or create an animation.
