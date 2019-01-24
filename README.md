# Airbus Ship Detection Challenge
![alt text](https://raw.githubusercontent.com/varunrao/airbus-ship-detection/master/logo.png)

The "Sea-Hawks" - Watch the open sea.
The goal of this project is to monitor ships in open sea. This will help maritime industry to increase knowledge, anticipate threats, trigger alerts, and improve efficiency at sea.

# Datasets
- train_ship_segmentations_v2.csv
    - This data setup holds the ground truth with Image Id's and the run-length encoding (rle) data
    - Actual images tied to this dataset are in train_v2.zip
- train_v2.zip
    - This is the data tied to the train_ship_segmentations_v2.csv
- sample_submission_v2.csv
- test_v2.zip



# Modeling Strategy
- Plan is to use Sagemaker's "Object detection" in full training mode
    - It uses the "Single Shot MultiBox Detector" framework
- "transfer learning mode" will be applied to help improve the model

# Test

# End Goal
