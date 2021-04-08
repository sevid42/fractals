# fractals
This is a Python class "Fractal" to create different fractals (Mandelbrot and Julia).
This is a nice first aproach, if you want to do something faster I will recomend you use Tensorflow 

Libraries:
import numpy as np
import matplotlib.pyplot as plt

There are a lot of images in the code developed on colab

The logic in basically is:
1.- create point and define the parameters
2.- create am atlas (a data set) that will be the max number of iteration over "z = (z*z) + c" until reach the max number of iterations or diverge
3.- Draw and love the simplicity of math.

To make this they use complex numbers in the iteration, but do not afrais, it is easier than you could think, I recomend you the book "MAKE YOUR OUWN MANDELBROT" by TARIQ RASHID

![image](https://user-images.githubusercontent.com/46327577/114108550-49307080-98a1-11eb-874d-3ae6deb6dd0e.png)
![image](https://user-images.githubusercontent.com/46327577/114108563-50577e80-98a1-11eb-9aa9-b4d169158f27.png)
![image](https://user-images.githubusercontent.com/46327577/114108579-59485000-98a1-11eb-9ff8-2f4b6c49487f.png)
![image](https://user-images.githubusercontent.com/46327577/114108597-61a08b00-98a1-11eb-9e00-ba553fd78447.png)


