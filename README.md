# Smart-Joules-Hackathon

Exploratory Data Analysis

Link of dataset: [Click here](https://docs.google.com/spreadsheets/d/1ec4rYKlYbrZkMlA8ypdXSah7FmEk5Cu1ycTzjrkpQOc/edit#gid=48855503)


## Objective

Assessing the value of energy efficiency improvements can be challenging as there's no way to truly know how much energy a building would have used without the improvements.

Labels:
- building_id - Foreign key for the building metadata.
- meter - The meter id code. Read as {0: electricity, 1: chilledwater, 2: steam, 3: hotwater}. Not every building has all meter types.
- timestamp - When the measurement was taken
- meter_reading - The target variable. Energy consumption in kWh (or equivalent). Note that this is real data with measurement error, which we expect will impose a baseline level of modelling error.
