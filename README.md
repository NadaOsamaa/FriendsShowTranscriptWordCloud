# Friends TV Show Transcript Analysis (WordCloud)

This is a Python script that analyzes the text data from the transcripts of the popular TV show "Friends". The script extracts the most frequently used words in the text, cleans the text data by removing punctuations and stop words, generates a bar chart to display the count of the top 20 most frequently used words, and creates a WordCloud image of the most frequently used words with the shape of the Friends doorframe.

## Requirements

To run this script, you will need the following Python libraries:

- pandas
- numpy
- re
- nltk
- spacy
- PIL
- matplotlib
- plotly
- wordcloud

You can install these libraries using pip:

```
pip install pandas numpy re nltk spacy Pillow matplotlib plotly wordcloud
```

You will also need to download the stopwords from the nltk library by running the following command in a Python console:

```
import nltk
nltk.download('stopwords')
```

## Usage

To use this script, follow these steps:

1. Download the "Friends_Transcript.txt" file, which contains the transcripts of all 236 episodes of Friends.
2. Download the "the_friends_door_frame.png" file, which contains the image of the popular Friends doorframe.
3. Replace the file paths in the script with the paths to the "Friends_Transcript.txt" and "the_friends_door_frame.png" files on your local machine.
4. Run the code using Jupyter Notebook, Google Colab, or any Python IDE.

The script will generate a bar chart and a WordCloud image of the most frequently used words in the Friends TV show transcripts (You can check out the "WordCloud Output.png" file to see the final WordCloud image).

## Credits

This code was created by Nada Osama, The Friends TV show transcripts were obtained from Kaggle, And the doorframe image was obtained from Google.


The source link of the transcript used in the code:
```
https://www.kaggle.com/datasets/divyansh22/friends-tv-show-script?resource=download
```
