# draw_images
Translate image files into your favourite paint software.

DrawImages
-------------

### How it works?

User selectes position of paintable canvas on screen, along with colour selection and layer creation within the paint software.

OpenCV reads image files into numpy arrays, reduces the colours to a predefined value (if there were millions of colours to paint it would take an age)

The image is then resized to the desired output size.

Using pyautoaui and pynput the array is itterated translating the colours onto the screen.


## Is it not a copy of the image?

Who knows but I think its more than just a carbon copy. Defining different brushes, different sizes and opacities creates an image that resembles the original but is not a copy. Its more like a representation of the original. 


### Todo

[ ] Add ability to reduce / increase brush size or opacity as you go through the colours 


### Examples

[<img src="/painted_images/youtube.png">](https://www.youtube.com/watch?v=7w4nqVOsBeM)

![Nebula](/painted_images/spacenebula.png)

![Savana](/painted_images/SAVANA.png)

![Flowers](/painted_images/art.png)

