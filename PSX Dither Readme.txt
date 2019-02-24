PSX Dither Shader

Post-processing shader to replicate PSX style dithering.

Dither gradients provided, but custom ones can also be made. The requirements for a custom dither
gradient is that each "block" has the same width as the height of the image. So a 4x4 sized dither
(just like the default psx_dither.png), the height of the image is 4 pixels, and the number of 
steps of dither is calculated automatically.

Make sure to disable compression on the dither textures, set them to Point filter, disable mipmaps and 
disable Non-power of 2 resizing.