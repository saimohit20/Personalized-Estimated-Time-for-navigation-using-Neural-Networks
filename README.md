# Predict individual driving habits

## Repository Link

https://github.com/maciejlipski/opencampus_travel_time

## Description

This project primarily focuses on predicting cyclists' speed based on GPX files retrieved from Slovenian pro-cyclists. Initially, the idea was to calculate the estimated time based on the GPX files. However, as we built our base model and conducted further evaluations, we found that the data was insufficient to predict the estimated time. Hence, we decided to focus on predicting speed instead.

 For the estimation of speed we considered following features.
- Elevation
- Slope
- Angle
- Distance
- Cumulative Slope

### Task Type
#### Preprocessing of Data
- Converting GPX files into xlsx using _openpyxl_ python library and retrieved Latitude, Longitude, Elevation and Time stamp.
- Delete files recorded outside of Europe
- Based on retrieved information calculated distance and time difference using _geopy_ python library.
- Further processing was done to calculate slope and angle using goepy and math python libraries

#### Splitting the data set
- Train 90%
- Test 10%

#### Model Configuration
- Sequential model
- Input Layer
- Hidden layers
- Output Layer
- Model Compliation
- Callbacks

#### Model Evaluation
- Trainig the model
- Testing the model

### Results Summary

- **Best Model:** Simple Neural Network
- **Evaluation Metric:**
- Training = Loss: 3.0195 - mae: 1.2467 Test Loss: 3.0246357917785645, Test MAE: 1.2471673488616943
- Testing = File: f437.csv | Mean Absolute Error: 1.4185177288381339,
            File: f537.csv | Mean Absolute Error: 1.3679558181952007,
            File: f566.csv | Mean Absolute Error: 1.5116033694708106,
            File: f144.csv | Mean Absolute Error: 1.3004845544151193,
            File: f24.csv | Mean Absolute Error: 1.280538647109091,
            File: f114.csv | Mean Absolute Error: 1.3838351290294801
            File: f559.csv | Mean Absolute Error: 1.241506570306826
            File: f234.csv | Mean Absolute Error: 1.3852115782484578
            File: f47.csv | Mean Absolute Error: 1.7581804723629753
            File: f647.csv | Mean Absolute Error: 1.4378520738654519
  
- **Result:**
- Absolute percentage difference in Linear Regression model: 15.358912331780052
- Absolute percentage difference in Neural Network model: 11.856650636508206

## Documentation

1. **[Literature Review](0_LiteratureReview/README.md)**
2. **[Dataset Characteristics](1_DatasetCharacteristics/README.md)**
3. **[Baseline Model](2_BaselineModel/README.md)**
4. **[Model Definition and Evaluation](3_Model/README.md)**
5. **[Presentation](4_Presentation/README.md)**

## Cover Image

![Cover Image](https://github.com/user-attachments/assets/df766913-9171-4ce0-9a3b-39d5a1d329fe)

