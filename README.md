# Hyperspectral-Change-Detection-Dataset-Wetland-Area
A hyperspectral data set can be used for testing binary and multi-class change detection techniques.

## File Description
All the files are in .mat format that can be loaded in Matlab.

**_PreImg_2006_:** Pre-processed Hyperion image acquired on May 3, 2005;

**_PostImg_2007_:** Pre-processed Hyperion image acquired on April 23, 2007;

**_Reference_Map_Binary_:** A binary reference map for evaluting the binary change detection performance (Two classes: change and no-change).

**_Reference_Map_Multiclass_:** A multiclass reference map for evaluting the multiclass change detection performance (Six classes: five change classes and no-change).

## Data Set Description
This dataset is made up of a pair of bitemporal hyperspectral images acquired by the Hyperion sensor mounted on board the EO-1 satellite on May 3, 2006 and April 23, 2007. The study area is wetland agricultural land in Yancheng, Jiangsu Province, China, which has a size of 220 × 430 pixels.

**Preprocessing operations** were made (i.e., repairing bad stripes, removal of uncalibrated and noisiest bands, atmospheric correction, co-registration) on two images, where **128 bands** (i.e., bands 13–53, 85–96, 103–118, 135–164, 188–199, and 202–218) out of original 242 bands were selected.

In this scenario, ﬁve major land-cover change classes are present, mainly associated with the changes between vegetation, bare land, water, and soil.

![2006](https://user-images.githubusercontent.com/102267920/169227421-73a3083b-b2e7-4cea-9fd8-1e59547b8d7f.jpg)
![2007](https://user-images.githubusercontent.com/102267920/169227433-dc0f3bf6-b695-4c24-8c21-7b8c12256ac1.jpg)
![binaryCD](https://user-images.githubusercontent.com/102267920/169227448-5a2c2b91-d5f8-4b62-b696-95085ddf8e89.jpg)
![Reference_Map_Multiclass](https://user-images.githubusercontent.com/102267920/169227458-4f663a84-89b4-4711-b967-b134c3e3ce11.jpg)
![微信图片_20220519123039](https://user-images.githubusercontent.com/102267920/169230231-b04ae511-8813-4e09-8523-85ea8561934d.png)

 (a) May 3, 2006; (b) April 23, 2007; (c) Binary CD Reference Map; (d) Multiclass CD Reference Map

## Class Information

**_Change Class 1 (C1)_**: 8937 pixels

**_Change Class 2 (C2)_**: 14520 pixels

**_Change Class 3 (C3)_**: 115 pixels

**_Change Class 4 (C4)_**: 423 pixels

**_Change Class 5 (C5)_**: 163 pixels

**_No-change Class (NC)_**: 70442 pixels

**_Total_**: 94600 pixels


## Citation

If you use this data set for your research, please cite the following papers.

[1] S. Liu, D. Marinelli, L. Bruzzone and F. Bovolo, "A Review of Change Detection in Multitemporal Hyperspectral Images: Current Techniques, Applications, and Challenges," IEEE Geoscience and Remote Sensing Magazine, vol. 7, no. 2, pp:140-158, 2019. [DOI: 10.1109/MGRS.2019.2898520](https://ieeexplore.ieee.org/document/8738052)

[2] S. Liu, Q. Du, X. Tong, A. Samat, H. Pan , X. Ma, “Band Selection based Dimensionality Reduction for Change Detection in Multitemporal Hyperspectral Images,” Remote Sensing, vol. 9, no.10, pp:1008, 2017. [DOI: 10.3390/rs9101008](https://www.mdpi.com/2072-4292/9/10/1008)

[3] S. Liu, Q. Du, X. Tong, A. Samat, L. Bruzzone, “Unsupervised Change Detection in Multispectral Remote Sensing Images via Spectral-Spatial Band Expansion,” IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, vol. 12, no. 9, pp:3578-3587, 2019. [DOI: 10.1109/JSTARS.2019.2929514](https://ieeexplore.ieee.org/document/8807196)

