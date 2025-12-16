- first download the bdd_100k data and the labels
- create the env named bdd_env
- install the pytorch and cuda (visit official library)
- install the requirements using the requirements.txt file
- also attached the requirements.txt from my bdd_env for reference.
- create the bdd_100k_dataset folder that contain the downloaded dataset and labels
- first the analysis is done to understand the data and then data prepration is done and then model
- then done the analysis to understand the complete dataset weather, scenes, background, differenct categories of the `objects` present car are most dominant ones.
- and do the data prepration to make it smaller for the training as mentioned in the requirements docs to choose the images from the `clear` weather. also use the different proposition of the clear weather images
  daytime 2500
  night 2000
  dawn/dusk 500

- also converted the labels from json to yolo format

NOTE: you need to change some of the paths according to your own folder and file structures in

- data_analysis.ipynb
- data_prepration.ipynb
- model.ipynb
- data.yaml file for train test and validation split
