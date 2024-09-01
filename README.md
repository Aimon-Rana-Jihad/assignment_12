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




### **We have made an NDVI map of my Fatikchhari upazila by using Landsat 9 imagery for 2022. Then generated 4 different classes and calculated areas for each class by thresholding.Here are the results:**


*  [ GEE LINK](https://code.earthengine.google.com/84b75d1669b35c85a246477a6ec98555)
*   [Screenshot](https://github.com/Aimon-Rana-Jihad/assignment_12/commit/f291da308367de99bb0f8daa14bc0e20ccb2c34a)


### **We have made a Normalized Difference Moisture Index (NDMI) map of my Fatikchhari upazila by using Landsat 9 imagery for 2023.It looks like this:**



*   [GEE link](https://code.earthengine.google.com/170378bf756568dd6dbdf10635da20ac)
*   [Screenshot](https://github.com/Aimon-Rana-Jihad/assignment_12/commit/5749d462c0bb3580f237c87ec26b13ee188e08d6)


### **Then we have generated two PNG images of our NDVI and NDMI map by using getThumbURL() function.The outcome:**

*   [GEE link](https://code.earthengine.google.com/5aa12408a13c360e451c15bc6cf8eb53)
*  [ Screenshot](https://github.com/Aimon-Rana-Jihad/assignment_12/commit/04f5386e6f2f544fafdd5fc52f0c57f2887cac6e)
