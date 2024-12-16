# making-png-file
How can we make a transparent png file with python?
An alpha channel, representing transparency information on a per-pixel basis, can be included in grayscale and truecolor PNG images.
An alpha value of zero represents full transparency, and a value of (2^bitdepth)-1 represents a fully opaque pixel. Intermediate values indicate partially transparent pixels that can be combined with a background image to yield a composite image. (Thus, alpha is really the degree of opacity of the pixel. But most people refer to alpha as providing transparency information, not opacity information, and we continue that custom here.)
