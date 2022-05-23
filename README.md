# DIE_Analysis of Gender Bias in Movies
This repository contains implementations and dataset used in our project of analyzing gender bias in Hollywood movies through emotion analysis using NLP techniques.

In our work, we first gathered scripts of films from different genres to derive sentiments and emotions using natural language processing techniques. For this, we converted text into embeddings wherein we found specific patterns in the personality traits of male and female characters in movies that are in line with societal stereotypes. Furthermore, we convert dialogues into an array of emotions by combining it with Plutchik's wheel of emotions and perform comparitive analysis among differnt genders based on their emotion scores. Our study aims to encourage reflections on gender equality in the domain of film and facilitate other researchers in analysing movies automatically instead of using manual approaches.


## Getting Started

### Dependencies
This project requires Python 3 and the following Python libraries installed:
* NumPy
* Pandas
* matplotlib
* scikit-learn
* nltk
* NRCLex
* Torch
* Stanza

This project was done using Google Colab. The code also runs in Jupyter Notebook. 

For Juputer Notebook, you will also need to have software installed to run and execute a Jupyter Notebook. If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.


### Code Usage

In order to run the code, you will also be required to use the provided datasets from dataset folder. The code can also be used for processing movie script not given in the dataset. 

All codes are provided under Code folder. It consists of following files:

* Final_notebook.py: It includes the codebase for our work performed in step-by-step order. The code is written in step-by-step format including steps for data conversion, sentiment analysis and emotion recognition. The code follows following structure:

   * Data Conversion: Converting HTML files into JSON. 
   
   * Data Preprocessing and Gender assignment: Extracting necessary information from JSON files to make CSV files including gender. 
   
   * Merging Dataset: CSV files of individual movie are then merged to form final processed dataset. 
   
   * Sentiment Analysis: Running Stanza to perform sentiment analysis on CSV files for all movies.
   
   * Emotion Analysis: Running NRCLex on the CSV file of all movies to get emotion scores in dialogues.


## Dataset Guidelines
The dataset includes 4 folders :

* PDF: It includes scripts of all the movies in pdf format.

* HTML: It includes the HTML version of all of the movie scripts converted from the original pdf. Pdfs were converted into parseable HTML format for processing the text.

* JSON: It includes two files:

    * Scenarios: It includes only the scenarios from the movie script.
    * Dialogues: It includes the dialogues from the movie sript mapped with respective character.
    
* CSV: It includes dialogues of the characters for each movie in seperate file.

### Processed Dataset

It includes the final CSVs files after processing. The datset includes following files:

 * all_characters.csv: It has dialogues and gender information of the characters in all movies combined together.
    
 * all_movies_emotions.csv: It includes emotion information of all characters including their dialogues and gender information. This is the final processed dataset. It has following columns:
      * Character: Name of the charcter in the movie
      
      * text: Dialogues of the characters in which emotion and gender detection occured.
      
      * gender: gender of the characters, classified as male and female.
      
      * movie_name: name of the movie.
      
      * year: the year in which the movie was released.
      
      * and remaining columns for the obtained emotion scores. The emotions are derieved from Plutchik's Wheel of emotions.
      







