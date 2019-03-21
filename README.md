# cython-numpy-style-transfer

I once tried to make a web application of [image style transfer](https://github.com/kewellcjj/pytorch-multiple-style-transfer) on [pythonanywhere](https://www.pythonanywhere.com/) with 500MB disk space and 500MB RAM. Funny that I wouldn't even be able to install pytorch on that small disk... 

Using following codes based on [cython version of im2col](https://github.com/samehkhamis/pydeeplearn/blob/master/pydeeplearn/image/image.pyx) and numpy, we are able to stylize an 400 by 600 input using less than 500MB memory under 13 seconds.