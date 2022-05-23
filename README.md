# DIE_Analysis of Gender Bias in Movies
This repository contains implementations and dataset used in our project of analyzing gender bias in Hollywood movies through emotion analysis using NLP techniques.

In our work, we first gathered scripts of films from different genres to derive sentiments and emotions using natural language processing techniques. For this, we converted text into embeddings wherein we found specific patterns in the personality traits of male and female characters in movies that are in line with societal stereotypes. Furthermore, we convert dialogues into an array of emotions by combining it with Plutchik's wheel of emotions and perform comparitive analysis among differnt genders based on their emotion scores. Our study aims to encourage reflections on gender equality in the domain of film and facilitate other researchers in analysing movies automatically instead of using manual approaches.




## Dataset Guidelines
The dataset includes 4 folders :

* PDF: It includes scripts of all the movies in pdf format.

* HTML: It includes the HTML version of all of the movie scripts converted from the original pdf. Pdfs were converted into parseable HTML format for processing the text.

* JSON: It includes two files:

    * Scenarios: It includes only the scenarios from the movie script.
    * Dialogues: It includes the dialogues from the movie sript mapped with respective character.
    
* CSV: It has includes dialogues of the characters for each movie.

## Processed Dataset

It includes the final CSVs files after processing. The datset includes following files:

 * all_characters.csv: It has dialogues and gender information of the characters in each movies.
    
 * all_movies_emotions.csv: It includes emotion information of all characters including their dialogues and gender information. This is the final processed dataset. It has following columns:
      * Character: Name of the charcter in the movie
      
      * text: Dialogues of the characters in which emotion and gender detection occured.
      
      * gender: gender of the characters, classified as male and female.
      
      * movie_name: name of the movie.
      
      * year: the year in which the movie was released.
      
      * and remaining columns for the obtained emotion scores. The emotions are derieved from Plutchik's Wheel of emotions.
      
## Codes

All of the codes can be found under codes folder. It consists of following files:

* Final Notebook: It includes the codebase for our work performed in step-by-step order. 







