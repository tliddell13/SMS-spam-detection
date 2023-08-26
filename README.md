Read Me:

The CBOW and Random Forest sms spam detection is implemented as one notebook for clarity. 
The imports at the top of the page must be run first.
After the imports are done the baseline models and primary model can be ran exclusively
as they don't rely on any of the other cells. After the primary model I have included my 
analysis of the dataset and following this some intermediate results and experimentation.
Note that some of the analysis and experimentation can take awhile to run as they run loops
around 100 times. These are clearly labeled.

The link for the coolab notebook is provided here:
https://colab.research.google.com/drive/12rm6c93b4bX-RIyVU01HIVHv21k38rU-?usp=sharing

The datasets must be uploaded to coolab before the notebook can run. 

Also please note the following:
1. The dataset is provided and is already split into training and testing data.
These can be seen as:
- train_data.csv
- test_data.csv

2. The notebook is structured as follows
- Baseline Models
- Primary Model
- Dataset Analysis
- Intermediate Results

3. The following libraries are used and can be installed with the corresponding pip
- numpy: pip install numpy
- pandas: pip install pandas
- matplotlib: pip install matplotlib
- seaborn: pip install seaborn
- spacy: pip install spacy
- gensim: pip install gensim
- nltk: pip install nltk
- imblearn: pip install imbalanced-learn
- wordcloud: pip install wordcloud
- sklearn: pip install scikit-learn
