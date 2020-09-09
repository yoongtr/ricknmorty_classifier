# Rick and Morty characters Classifier!
## Classifies Rick and Morty characters using Keras, CNN and Bing Search API. Dataset includes Rick, Morty, Meeseeks, Summer and Poopybutthole.

### Steps:
1. Create a Bing Search API on the website
2. Insert the relevant API KEY into `search_bing_api.py`
3. Create the dataset folders. I'm too lazy to upload all the character images but basically it will query 250 first images on Bing, then I do some pruning, aka delete irrelevant images
4. Run the `train.py file`. I put the number of epoch as 50.
5. Run the `test.py file`. The test datas are inside example folder.

### Datasets:
Each folder inside the `dataset2` folder is named after the class of the data
There are 5 folders of each character: Rick, Morty, Meeseeks, Summer and Poopybutthole
I tried to delete the duplicated images and images with more than one character inside, but then again I am lazy so not all data are cleaned

### References:
* (PyImageSearch tutorial)[https://www.pyimagesearch.com/2018/04/16/keras-and-convolutional-neural-networks-cnns/?__s=7inmkdkdpxwkmixwf3kb]
* (Bing Search API and look for relevant documentations)[https://azure.microsoft.com/en-us/services/cognitive-services/bing-image-search-api/]

### Update:
I uploaded the full image dataset on Kaggle: (Rick and Morty characters)[https://www.kaggle.com/yoongtran/rick-and-morty-characters]
Have fun downloading and inputting into the classifier!
