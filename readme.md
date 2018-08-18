1. #### Run length decoding
* Given a RLE code, decode it and get the masks. This is useful in image segmentation tasks, where it is normal for masks to be represented as RLE codes. The decoded image is then used for training segmentation tasks via traditional methods like UNet, RCNN etc

* main file- [rle.py](https://github.com/rohinarora/helper_functions/blob/master/rle.py)
* ipython version- [rle.ipynb](https://github.com/rohinarora/helper_functions/blob/master/rle.ipynb)

* Data here is sampled from Kaggle's [Airbus Ship Detection Challenge](https://www.kaggle.com/c/airbus-ship-detection)

* * Original image
![](data/img1.png?raw=true "")

* * Mask generated
![](data/img2.png?raw=true "")

* * Mask superimposed with original image
![](data/img3.png?raw=true "")




* For practical implementation, check