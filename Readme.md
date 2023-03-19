## Setup
Simply upload the provided ipynb file into Google Colab or Jupyter Notebook (Colab recommended) and run the program 

## Dataset
[Dataset downlaod link here](https://www.uvic.ca/ecs/ece/isot/datasets/fake-news/index.php)

## Order of model(ipynb file):
1. fact_opinion_SVM: SVM model to classfiy news as fact based or opinion based
2. Fake_News_Detection_using_LSTM: LSTM model to classfiy news as real or fake
3. Realtime_test: Testing our compelete model with realtime data

## Notes:
- only "fact_opinion_dataset" is provided in the zip file as ISOT dataset has very large size, one can download ISOT dataset from the above given link
- update the filepath of dataset(in ipynb files) as per the location of dataset file in your machine
- change the file path of save and load model (only required if you decide to save/load model into your machine) as per your machine