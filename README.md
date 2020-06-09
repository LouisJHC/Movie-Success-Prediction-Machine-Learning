# Movie-Success-Prediction-Machine-Learning
Natural Language Processing &amp; Sentiment Analysis on Movie Plots to Predict the Success of Movies. The project was done in Python. Movie dataset such as OMDb, Rotten Tomatoes, Wikidata-Movies will be explored and analyzed to present insights on whether one can use plot summaries to predict the success of movies & whether the movie ratings of the audience are related to the success of movies in any significant way.

### Installing

For natural language processing & sentiment analysis on plot summary, there are few libraries that need installations. One of them is [`NLTK`]([https://www.nltk.org/](https://www.nltk.org/)), which is a natural language processing library in Python. The other ones are [`vaderSentiment`]([https://github.com/cjhutto/vaderSentiment](https://github.com/cjhutto/vaderSentiment)) and [`wordcloud`]([https://github.com/amueller/word_cloud](https://github.com/amueller/word_cloud)), which are used for sentiment analysis and generating the word cloud diagrams, respectively. For `vaderSentiment` and `wordcloud`, you would need to install them by running the following commands:
`pip install vaderSentiment`
`pip install WordCloud`
Make sure to execute the commands and install inside appropriate environment of your choice. For a conda environment, use the Anaconda Prompt. For a Python environment, simply run the commands in the command prompt/terminal. More details and alternative ways of installing the libraries can be  found at their websites (linked above).

Other than that, necessary code for downloading the `NLTK` packages are included inside the notebook, so just by running the .ipynb file, it will download the necessary packages.

## Running the Code

After all the necessary library packages are installed, you can simply run the program by running the notebook files. There are two notebooks:
1. [exploratory-data-analysis.ipynb](https://csil-git1.cs.surrey.sfu.ca/ikpark/movie-success-prediction/blob/master/exploratory-data-analysis.ipynb)
	- An exploratory data analysis with visuals
	- Correlations of key variables
	- Relationship between box office gross and audience average rating
	- Box office gross prediction using linear/polynomial regression models
2. [nautural-language-processing-with-sentiment-analysis.ipynb](https://csil-git1.cs.surrey.sfu.ca/ikpark/movie-success-prediction/blob/master/natural-language-processing-with-sentiment-analysis.ipynb)
	- An analysis on the plot summary of movies and their use in predicting the success of movies.
	- The order of execution won’t matter as the analysis are separated in two files.

## Built With

-   Python - Pandas, NumPy, Matplotlib, scikit-learn, seaborn, etc.

-   Jupyter Notebook - for combining live code with visualizations, as well as markdowns, to guide the readers through the analysis.
