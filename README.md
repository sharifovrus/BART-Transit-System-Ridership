# BART-Transit-System-Ridership
BART Transit System Ridership prediction might provide information which people may use to save their time in commute. 
## Install
This project requires following Python libraries installed:

- NumPy
- Pandas
- scikit-learn

Visualization:
- matplotlib
- seaborn

## Data
Dataset source: https://www.kaggle.com/jonathanbouchet/bart-transit-system/data
The dataset includes date-hour-soo-dest-2017.csv file which contains daily inter-station ridership for (part of) 2017. 
There are over 2000 station-to-station combinations in the dataset.
date-hour-soo-dest-2017.csv is number of passengers (Throughput) that went between two stations of Origin and Destination in a given time (DateTime) in (part of) 2017, including:

- Origin - Short name of the origin station
- Destination - Short name of destination station
- Throughput - Capacity, number of passenger went b/n origin and destination stations
- DateTime - Capacity timeframe.
    Total: 3.31m rows and 4 columns.
    
Throughput is a target variable, this is number of passenger went b/n origin and destination stations.

## Project Report
Report with the detailed description of the steps of the Project contains Analysis, Methodology sections, ML pipeline description and conclusion as a basis for related ideas.
## License
The content of this repository is licensed under a MIT License https://choosealicense.com/licenses/mit/
