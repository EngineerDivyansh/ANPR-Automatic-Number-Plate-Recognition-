# Automatic-Number-Plate-Recognition-YOLOv8


## Project Setup


* Install the project dependencies using the following command 
```bash
pip install -r requirements.txt
```
* Run main.py with the sample video file to generate the test.csv file 
``` python
python main.py
```
* Run the add_missing_data.py file for interpolation of values to match up for the missing frames and smooth output.
```python
python add_missing_data.py
```

* Finally run the visualize.py passing in the interpolated csv files and hence obtaining a smooth output for license plate detection.
```python
python visualize.py
```
#   A N P R - A u t o m a t i c - N u m b e r - P l a t e - R e c o g n i t i o n -  
 