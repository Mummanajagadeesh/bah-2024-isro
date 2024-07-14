### Spectral classification of Chandrayaan-2 IIRS using AI/ML for understanding geological diversity of the Moon

CThe IIRS is the highest spectral and spatial resolution hyperspectral dataset of the Moon, available from Chandrayaan-2 mission. The data has immense use in understanding the Moon’s geology. The data will be classified after categorising them based on similar spacecraft geometry to minimize the geometry-based effects. A well-covered region on the Moon will be selected for further analysis. The AI/ML tools will be used for quick spectral classification that can be further linked to mineral characterisation.

## Objectives
- Create a visualisation data that will aid in classifying the IIRS data based on similar data acquisition parameters.
- Select a set of data with similar observation characteristics and apply AI/ML algorithms for grouping the spectral classes
- Understand the potential advantages and limitations of using AI/ML for spectral classification

## Expected Outcomes
- Understanding on hyper spectral data analysis
- A GUI that can be used by users for identifying area of interest with display of main observational parameters used
- Spectral classification of data that can be further used for minerals identification and for understanding geological context at local and global scales

## Dataset Required:
- IIRS data will be downloaded from Indian Space Science Data Center: https://www.issdc.gov.in
- Supportive data for validation and comparison will be downloaded from: https://ode.rsl.wustl.edu/moon/

## Suggested Tools/Technologies:
- Python/MATLAB

## Expected Solution / Steps to be followed to achieve the objectives:
- Download IIRS data of a specified period
- Classify data based on geometry and header file information
- Display the IIRS strips on Moon globe with its main parameters in a tabular form
- Select a well-covered region with mentors help for further processing
- Apply AI/ML algorithms for removing noisy spectra and for spectral classification
- Compare the spectral classification with available scientific outcomes for validating the method
  
## Evaluation Parameters:
- User Experience: Ease of use of GUI and satisfaction in querying and retrieving data through the system.
- Classification: Validation by comparing with published results
- Relevance: comparing outcomes using multiple AI/ML algorithms
