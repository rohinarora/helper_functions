1. #### Run length decoding
* Given a RLE code, decode it and get the masks. This is useful in image segmentation tasks, where it is normal for masks to be represented as RLE codes. The decoded image is then used for training segmentation tasks via traditional methods like UNet, RCNN etc

* main file- [rld.py](https://github.com/rohinarora/helper_functions/blob/master/rld.py)
* ipython version- [rld.ipynb](https://github.com/rohinarora/helper_functions/blob/master/rld.ipynb)

* Data here is sampled from Kaggle's [Airbus Ship Detection Challenge](https://www.kaggle.com/c/airbus-ship-detection)

* ### Example

* * Original image
<img src="https://github.com/rohinarora/helper_functions/blob/master/data/img1.png" width="300" height="300">

* * Mask generated
<img src="https://github.com/rohinarora/helper_functions/blob/master/data/img2.png" width="300" height="300">
* * Mask superimposed with original image
<img src="https://github.com/rohinarora/helper_functions/blob/master/data/img3.png" width="300" height="300">




* For practical implementation, check [Airbus Ship Detection Challenge](https://github.com/rohinarora/Airbus_Ship_Detection_Challenge)
.
