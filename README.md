
# Lung-and-COVID-19-Disease-segmentation

> It is done as a part of course project M1 master course Scene Segmentation and Interpretation.
> And, It is implemented on Google Colaboratory in Tensorflows-Keras.


The implementation is based on [1] & [2].


Here, [COVID-19-CT-Seg_20cases](https://zenodo.org/record/3757476#.Xpz8OcgzZPY) are used for training and testing.


## File Descriptions

`Segmentation_COVID_MultiRes_UNET.ipynb` - This file is for the data preparation, training, testing and performance evaluation.

## Discussion

Though, for disease prediction, it is not performing well but this project is good hands on experience for covid segmentation. 

For improvement, one can work on taking consideration of only disease mask dice coefficient while training metric rather than taking the global dice coefficient. Moreover, amont of data is less for disease mask, we can also look upon taking the bigger dataset.


## References
<a id="1">[1]</a>
Ronneberger, Olaf, Philipp Fischer, and Thomas Brox. "U-Net: Convolutional Networks for Biomedical Image Segmentation." arXiv preprint arXiv:1505.04597 (2015).

<a id="2">[2]</a>
Ibtehaz, Nabil, and M. Sohel Rahman. "MultiResUNet: Rethinking the U-Net architecture for multimodal biomedical image segmentation." Neural Networks 121 (2020): 74-87.


