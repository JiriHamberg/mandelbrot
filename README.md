# mandelbrot
Simple interactive Mandelbrot set zoomer made using C, openGL and GLUT.

# Usage
Build using make. Built only linux in mind, but any platform with gcc, openGL and GLUT might work, I suppose.

Run the executable. Use mouse left click to zoom in, right click to zoom out.

#Limitations
The precision of long double limits the depth to which you can zoom. One can zoom to scales of about e-17 or so before the image starts getting blurry. There is still plenty to look at.

It is slow. Zooming in might take couple of seconds depending on the "complexity" of the current scene. One can speed up the painting by playing with "settings.h" options and recompiling. Reducing the size of the canvas or the maximum number of iterations will significantly improve speed at the cost of image prettiness.

# Images

![mandelbrot_001](https://cloud.githubusercontent.com/assets/2308612/17386163/923a9494-59f0-11e6-8f14-c18376e3140b.png)

![mandelbrot_002](https://cloud.githubusercontent.com/assets/2308612/17386221/21c7d734-59f1-11e6-8065-348efa36d916.png)

![mandelbrot_003](https://cloud.githubusercontent.com/assets/2308612/17386272/b8158416-59f1-11e6-8cab-7fcee2758663.png)
