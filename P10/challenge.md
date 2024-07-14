### Image based Search of Lunar craters from global mosaic.

This project aims to find location (latitude and longitude) of a crater from lunar complete mosaic (Latitude: 90 to -90deg and Longitude: 0 to 360deg). The complete mosaic is in the form of single global mosaic GeoTIFF image at 100m spatial resolution from LRO mission WAC. The input crater images will be provided from Chandrayaan-2 TMC, which is at 5m spatial resolution. Users will be supplying an image chip containing a crater as input, which is to be searched in the LRO WAC mosaic and its latitude and longitude should be extracted. Preferably, name of the crater can also be extracted from the lunar crater catalogue.

## Objectives
- Develop a software to handle spatial resolution difference between Chandrayaan-2 TMC nadir images and LRO WAC mosaic for template matching.
- Develop a software to match given crater template in Mosaic image.
- Develop a software to store Lunar mosaic for quicker search and for spotting the given crater.

## Expected Outcomes
- Software for crater based template matching.
- Software for finding latitude and longitude of a given crater image and its visualization.

## Dataset Required:
- LRO WAC global mosaic (100m), June 2013 version cane be download from USGS website.
- Chandrayaan-2 TMC Nadir images cane downloaded from https://chmapbrowse.issdc.gov.in
- From “CH2_TMC_Calibrated_Product” instrument footprints, user can select PDS product id which contains “ch2_tmc_ncn_*” should be downloaded and used.
  
## Suggested Tools/Technologies:
- QGIS, and opencv.
  
## Expected Solution / Steps to be followed to achieve the objectives:
- Representative output shown below.

## Evaluation Parameters:
- Retrieved latitude and longitude should match with actual coordinate of a given crater.
- Template matching of a crater should have correlation value of ≥0.70.
