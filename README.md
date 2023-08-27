# Land-use_Land-cover
Land cover data documents how much of a region is covered by forests, wetlands, impervious surfaces, agriculture, and other land and water types. Water types include wetlands or open water. Land use shows how people use the landscape – whether for development, conservation, or mixed uses.

The studied area is in Mazandaran province, a province centered on the city of Sari in the north of Iran and on the southern shores of the Mazandaran sea, and includes the cities of Nowshehr, Chalus, Abbas Abad, Kalardasht, Tankabon and Ramsar.

![image](https://github.com/bakhshiintel/Land-use_Land-cover/assets/98385786/4ef66c94-2926-4740-bf03-8fe0323d13d2)

# Data used:
The data used in this study for three time series of 2022, 2015 and 2001 are from Landsat satellite images.
# Preprocessing of satellite images 
After taking satellite images, we have to make geometrical and atmospheric corrections and remove clouds from the images and mosaic the images.

# Image classification:
To classify the images, the Iso Data method, one of the most widely used unsupervised classification methods, is used first. In this method, pixels are divided into groups based on their reflective characteristics. These groups are called clusters. The number of clusters is specified by the user. By repeatedly defining the number of clusters and spectral groups, in addition to observing how the clusters are placed, separated classes can also be determined. In general, unsupervised classification methods are considered as a kind of pre-classification in image processing. After applying the unsupervised classification method, from several methods including the use of Google Earth software, examining spectral behaviors and various indices such as vegetation density index, urban areas index and existing maps in previous years, maximum training samples were prepared and The test of their normality was done by introducing educational samples related to land use class using the common Maxlikelihood method, and a land cover use map was prepared. After performing a large number of classification actions as trial and error, a land use map was prepared.The figure below shows the land use map in 2022 from Landsat 9 satellite images.

![image](https://github.com/bakhshiintel/Land-use_Land-cover/assets/98385786/4a822dc1-a611-4bcc-8c08-132a52fb97cf)
