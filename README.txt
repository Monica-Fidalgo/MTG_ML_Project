This is a machine learning project made with MTG (Magic the Gathering) data.
The objective of the project was to create a combined (text+image features) model to predict the color of a MTG card.

a) The project uses data from MTGJSON.com:

AtomicCards.json (download here: https://mtgjson.com/downloads/all-files/#atomiccards) - 94,118KB
AllPrintings.json (download here: https://mtgjson.com/downloads/all-files/#allprintings) - 260,642KB

b) The project itself consists of the following files (the numbers represent the chronological order in which they were created/should be read):

1_data_acquisition.ipynb - 10,442KB
2_data_cleansing.ipynb - 126KB
3_data_acquisition_images.ipynb - 148KB
4_data_preparation_for_ml.ipynb - 43KB
5_ml_combined_model.ipynb - 2,429KB
ProjectPresentation.pdf - 6,295KB 

c) And, inside the jupyter notebooks, the following files are created:

AtomicData.csv - 82,590KB
DataCleansed.csv - 5,377KB
DataReady.csv - 5,186KB
ImageURLs.csv - 3,631KB
PrintingsData.csv - 197,165KB
ImageDataCrop.pkl - 1,333,106KB
