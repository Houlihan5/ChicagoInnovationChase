#Scaling Images


[ImageMagick](http://www.imagemagick.org/) provides a number of command-line tools for image manipulation, which are relatively simple to use for simple tasks.

To simple scale an image, say from 2000x3000 to 200x300:

    convert FOO.png -geometry 200x FOO-scaled.png
    
