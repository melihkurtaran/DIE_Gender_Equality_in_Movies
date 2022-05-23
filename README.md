# DIE_Gender_Equality_in_Movies
Data-Intensive Engineering Two Semesters Project

## Dataset Guidelines
The dataset includes 4 folders :

* PDF: It includes scripts of all the movies in pdf format.

* HTML: It includes the HTML version of all of the movie scripts converted from the original pdf. Pdfs were converted into parseable HTML format for processing the text.

* JSON: It includes two files:

    * Scenarios: It includes only the scenarios from the movie script.
    * Dialogues: It includes the dialogues from the movie sript mapped with respective character.
    
* CSV: It has dialogues and gender information for characters in each movie.

* Processed DB: It includes the final CSVs files after processing. The datset includes following files:

    * all_characters.csv: It has dialogues and gender information of all the characters in the movies.
    
    * all_movies_emotions.csv: It includes emotion information of all characters including their dialogues and gender information. This is the final processed dataset. It has following columns:
      * Character: Name of the charcter in the movie
      
      * text: Dialogues of the characters in which emotion and gender detection occured.
      
      * gender: gender of the characters, classified as male and female.
      
      * movie_name: name of the movie.
      
      * year: the year in which the movie was released.
      
      * and remaining columns for the obtained emotion scores. The emotions are derieved from Plutchik's Wheel of emotions.







