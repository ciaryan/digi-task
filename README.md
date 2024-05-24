# Shipment Delivery Prediction Project

This project aims to predict the likelihood of a delay in shipment deliveries based on historical data. The project uses Python and libraries such as pandas and scikit-learn for data processing and model building.

## Datasets

The project uses the following datasets, all in CSV format:

GPS_data.csv: Contains GPS tracking data for each shipment.


New_bookings.csv: Contains data on new bookings that the model will be used to predict on.


Shipment_bookings.csv: Contains historical data on shipment bookings. This data is used to train the predictive model.


## File Descriptions

GPS_data.csv: This file contains shipment tracking data. Each row represents a shipment with attributes like shipment number, latitude, longitude, record timestamp, etc.
New_bookings.csv: This file contains data on new bookings for which we want to predict the likelihood of delay.
Shipment_bookings.csv: This file contains historical data on shipment bookings. It includes attributes like shipment number, carrier display ID, vehicle size, vehicle build up, latitude, longitude, scheduled times, etc.
requirements.txt: This file lists all the Python libraries that your project depends on. You can use pip to install them with pip install -r requirements.txt.


## Usage

First, make sure that you have installed all dependencies by running `pip install -r requirements.txt`.

Then, you can run the Python scripts to perform data processing, exploratory data analysis, model training, and prediction on the new bookings data.
