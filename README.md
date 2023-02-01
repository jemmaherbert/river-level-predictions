# River Level Predictions
The intent of this project was to predict river levels in NSW based off historical levels, and predicted rainfall in the area. 

The data was orginally scrapped from the Bureau of Metorology http://www.bom.gov.au/climate/data/index, the NSW Office of Water http://realtimedata.water.nsw.gov.au/water.stm and Kayak Canberra http://www.kayakcanberra.com/heights/ . It  was cleaned and collated in a seperate project, this project makes use of that data. The cleaned data is available here: [https://drive.google.com/drive/folders/11DyR0JGGIvAgv9m2Bq2aIFkbDgE-Tz_W?usp=sharing] . This code expects that data to be in a directory called 'Data' in the root of this project. The file `Reports_Concatenated.pdf` (a uni assignment report) describes in details how this dataset was generated. 

The file `initial_exploration.ipynb` is just a quick look at the data itself to check exactly what is included in the dataset and ensure its validity. 

The file `example_river.ipynb` is a first attempt to create a model to predict river levels for a single river. It:
 - works through some of the reasoning around river gauge and rainfall station selection
 - creates some datasets for testing and training
 - defines evaluation metrics
 - creates a few rudimentary models
 ** this file doesn't actually make much use of the data.db which was validated in the 'inital_exploration.ipynb' becuase the chosen river isn't present in that dataset. 
 ** some of the models which apparently worked when this code was originally created no longer run