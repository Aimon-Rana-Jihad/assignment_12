# assignment_12
# **Normalized Difference Indices Thresholding and Area Calculation Using Google Earth Engine**
Normalized Difference inidices, thresholding is a widely used technique in remote sensing and satellite imagery analysis for classifying different land coveer conditions. In this repository we have demonstrated how to perform NDVI thresholding and calculate the area for each threshold class using the Google Earth Engine JavaScript API.
## **Step-1: Import Image Collection**
First, import the image collection containing the satellite images with bands required for NDVI calculation.
## **Step 2: Calculate NDVI**
Next, calculate the NDVI for each image in the collection using the formula: (NIR - Red) / (NIR + Red), where NIR (Near-Infrared) is band 5 and Red is band 4.
## **Step 3: Thresholding**
Define threshold classes based on NDVI values to classify different vegetation types or conditions. For example, we'll define classes for bare land, low vegetation, and high vegetation. You can change the upper and lower limit of the value as far your requirement.
## **Step 4: Area Calculation**
Calculate the area for each threshold class using area-weighted multiplication and the reduceRegion function.


1) A  NDVI map of Fatikchari by using Landsat 9 imagery for 2022.By Generating 4 different classes and calculating area for each class by thresholding. Here the [GEE](https://code.earthengine.google.com/84b75d1669b35c85a246477a6ec98555) link & [Sceenshot](https://github.com/Aimon-Rana-Jihad/assignment_12/commit/f291da308367de99bb0f8daa14bc0e20ccb2c34a).

2)A Normalized Difference Moisture Index (NDMI) map of Fatikchhari by using Landsat 9 imagery for 2023.Here the [GEE](https://code.earthengine.google.com/170378bf756568dd6dbdf10635da20ac) link & [Sceenshot](https://github.com/Aimon-Rana-Jihad/assignment_12/commit/5749d462c0bb3580f237c87ec26b13ee188e08d6) link.

3)Two PNG image of my NDVI, and NDMI map by using getThumbURL() function.here the[ GEE](https://code.earthengine.google.com/5aa12408a13c360e451c15bc6cf8eb53) link & [Sceenshot](https://github.com/Aimon-Rana-Jihad/assignment_12/commit/04f5386e6f2f544fafdd5fc52f0c57f2887cac6e) link.
