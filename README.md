# Asl_Files

##imuVisualizeFourierFilter.py
Takes one command line parameter: A folder name.
```bash
python3 imuVisualizeFourierFilter.py folder_name
```
The file will parse all csv files in the folder and create graphs for them based on Acceleration, Linear Acceleration, and Gyroscope. The script will save these graphs to a /graph folder. This folder needs to be made prior to running the script. 
##get_features.py 
Takes one command line parameter: A folder name.
```bash
python3 get_features.py folder_name
```
The script will read in all files in the folder and run the same stats on them. Which stats can be altered by editing the end of the file.
