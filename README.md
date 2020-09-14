# Exploratory_Data_Analysis_Project_One

## Introduction
This assignment uses data from the UC Irvine Machine Learning Repository, a popular repository for machine learning datasets. In particular, we will be using the “Individual household electric power consumption Data Set” which I have made available on the course web site. Our overall goal here is to examine how household energy usage varies over a 2-day period in February, 2007.

First you will need to fork and clone the following GitHub repository [here](https://github.com/rdpeng/ExData_Plotting1). 

For this assignment you should:

- Construct the plot and save it to a PNG file with a width of 480 pixels and a height of 480 pixels.

- Name each of the plot files as `plot1.png` and `plot2.png` etc. 

- Create separate R code files, `plot1.R` and `plot2.R`etc. 

- Constructs the corresponding plots. 

## Data
### Dataset
Electric power consumption [here](https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip). 

### Data Discription
Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.

The following descriptions of the 9 variables in the dataset are taken from the UCI web site:

- `Date`: Date in format dd/mm/yyyy

- `Time`: time in format hh:mm:ss

- `Global_active_power`: household global minute-averaged active power (in kilowatt)

- `Global_reactive_power`: household global minute-averaged reactive power (in kilowatt)

- `Voltage`: minute-averaged voltage (in volt)

- `Global_intensity`: household global minute-averaged current intensity (in ampere)

- `Sub_metering_1`: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).

- `Sub_metering_2`: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.

- `Sub_metering_3`: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.

## Tips
You may find it useful to convert the Date and Time variables to Date/Time classes in R using:

- `strptime()` and `as.Date()`functions.
