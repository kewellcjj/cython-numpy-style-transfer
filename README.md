# cython-numpy-style-transfer

I once tried to make a web application of my [pytorch image style transfer](https://github.com/kewellcjj/pytorch-multiple-style-transfer) on [pythonanywhere](https://www.pythonanywhere.com/) with 500MB disk space and 500MB RAM. Funny that I wouldn't even be able to install pytorch on that small disk... 

Using [cython im2col](https://github.com/samehkhamis/pydeeplearn/blob/master/pydeeplearn/image/image.pyx) and numpy, I'm able to stylize an 400 by 600 input using less than 500MB memory under 15 seconds on my desktop. The example is given in the notebook. 

The .model file can also be found in [pytorch image style transfer](https://github.com/kewellcjj/pytorch-multiple-style-transfer) which provides 19 image styles.
