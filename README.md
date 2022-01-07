# Topic-modeling-Wesi

## Objective
The main objective of this project is extracting meaningful topics from Historical well reports to improve existing Information Retrivel system at WESI. Topic Modelling techniques will be applied on the text extracted that from historical well reports. Three main segments of this project are as follows.
1. Data preprocessing
2. Building Topic models
3. Visualizing end results

![Entire_method](https://user-images.githubusercontent.com/11143761/148607833-d969b6d9-3534-4667-a07b-3a7c6e0fae49.png)


### Data preprocessing
Code for preprocessing can be found in **Data preprocessing.ipynb** file. Text was extracted from the well reports using Optical Character Recognition. Since these reports date back to 1980s, most of them are handwritten, which lead to noisy text. Hence, preparing data for topic models plays a crucial role in this project. Few NLP techniques used for preprocessing are as follows.
* Character Replacement
* Spell Correction
* Language Detection
* Stemming and Lemmitization

### Topic Modelling
Code for preprocessing can be found in **Training Models.ipynb** file. Preprocessed text is tokenized and converted to Document-word matrix using Bag of words. Currently working on four topic models,
* Latent Dirichlet allocation
* Latent semantic analysis
* BERTopic
* Top2Vec

### Visualization Techniques
Since topic modelling is an unsupervised technique, human evaluation is important for examining the extracted topics. Currently working on a survey design for visualizing and presenting the end results, to a oil and gas domain expert at WESI.
