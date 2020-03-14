## paste
<img src="images/mini_empty_logo.png"/><img src="images/mini_empty_logo.png"/><img src="images/mini_empty_logo.png"/>

Pastes an image into another image at a given position.

### Usage in ImageJ macro
```
Ext.CLIJx_paste(Image source, Image destination, Number destinationX, Number destinationY);
```


### Usage in Java
```
// init CLIJ and GPU
import net.haesleinhuepf.clij2.CLIJ;
import net.haesleinhuepf.clij.clearcl.ClearCLBuffer;
CLIJ2 clij2 = CLIJ2.getInstance();

// get input parameters
ClearCLBuffer source = clij2.push(sourceImagePlus);
destination = clij.create(source);
int destinationX = 10;
int destinationY = 20;
```

```
// Execute operation on GPU
clij2.paste(clij, source, destination, destinationX, destinationY);
```

```
//show result
destinationImagePlus = clij2.pull(destination);
destinationImagePlus.show();

// cleanup memory on GPU
clij2.release(source);
clij2.release(destination);
```




### Example scripts
<a href="https://github.com/clij/clij2-docs/blob/master/src/main/macro/"><img src="images/language_macro.png" height="20"/></a> [paste_images.ijm](https://github.com/clij/clij2-docs/blob/master/src/main/macro/paste_images.ijm)  
<a href="https://github.com/clij/clij2-docs/blob/master/src/main/macro/"><img src="images/language_macro.png" height="20"/></a> [allocateBig2DImages.ijm](https://github.com/clij/clij2-docs/blob/master/src/main/macro/allocateBig2DImages.ijm)  
<a href="https://github.com/clij/clij2-docs/blob/master/src/main/macro/"><img src="images/language_macro.png" height="20"/></a> [make_super_blobs.ijm](https://github.com/clij/clij2-docs/blob/master/src/main/macro/make_super_blobs.ijm)  
<a href="https://github.com/clij/clij2-docs/blob/master/src/main/macro/"><img src="images/language_macro.png" height="20"/></a> [paste_images.ijm](https://github.com/clij/clij2-docs/blob/master/src/main/macro/paste_images.ijm)  
<a href="https://github.com/clij/clatlab/blob/master/src/main/matlab/"><img src="images/language_matlab.png" height="20"/></a> [paste.m](https://github.com/clij/clatlab/blob/master/src/main/matlab/paste.m)  


[Back to CLIJ documentation](https://clij.github.io/)

[Imprint](https://clij.github.io/imprint)