# Twitter Hatefull Speech Detection
I developed a hateful speech detection model using the dataset named "turkish offensive language detection" available on Kaggle, which can be found at this link: [https://www.kaggle.com/datasets/toygarr/turkish-offensive-language-detection](https://www.kaggle.com/datasets/toygarr/turkish-offensive-language-detection). 
The steps I followed are as follows:  
* Found a suitable dataset and reviewed it.  
* Removed symbols like @ and # along with the accompanying text using regex.  
* Solved the Turkish character problem.  
* Applied tokenization and stopwords removal as part of NLP (Natural Language Processing).  
* Extracted features using the TF-IDF feature extraction library from Scikit-learn.  
* Created my own neural network model using the NN class from PyTorch.  
* After training the model, I performed validation to evaluate the model's success.  
* Saved the model.
