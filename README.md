# Ima206_project_final
U-Net for cardiac MRI segmentation

We used the data from the ima205 kagglechanllenge as the training validation set. A test set from the acdc dataset was used. 

As the test set is too large, the testing.zip file at the following link needs to be used: 
https://drive.google.com/file/d/1uOyat62EtP0P5SVsYxSQ9isCU0H4sLDc/view?usp=sharing

When preprocessing the data, we used two ways of unifying the slice sizes, resize and padding. 
The code and results for the resize method are in resize_test.ipynb.
The code and results for the padding method are in padding_test.ipynb. 
The only difference between the two files is the resize and padding operations.

We use the model unet.py conv.py encoding.py decoding.py conv.py init.py from:
Pérez-García, Fernando. (2020). fepegar/unet: PyTorch implementation of 2D and 3D U-Net (v0.7.5). Zenodo. https://doi.org/10.5281/zenodo.3697931
