# DIE_Gender_Equality_in_Movies
Data-Intensive Engineering Two Semesters Project

## Dataset Guidelines
The dataset includes 4 folders :
* PDF: It includes scripts of all the movies in pdf format.
* HTML: It includes the HTML version of all of the movie scripts converted from original pdf. 
* JSON: It includes two files:
* * Scenarios: It includes 
* * Dialogues: 
* CSV: It has dialogues and gender information for characters in each movie.
* Processed DB: It includes the final CSVs files after processing. The datset includes following files:
 * all_characters.csv: It has dialogues and gender information of all the characters in the movies.
 * all_movies_emotions.csv: It includes emotion information of all characters including their dialogues and gender information. This is the final processed dataset. It has following columns:
   * Character: Name of the charcter in the movie
   * text: Dialogues of the characters in which emotion and gender detection occured.
   * gender: gender of the characters, classified as male and female.
   * movie_name: name of the movie.
   * year: the year in which the movie was released.



## The Movie Database

### PDF
- The very row data that we use
- The pdf versions of the scripts of the movies that we use for our project.

### HTML
- Converted HTML versions of the PDF files. 
- Since it is not possible to work with PDFs directly, they are converted into parseable HTML format.

### JSON
- We create two types of JSON files
- One is for dialogues and the other one is for the scenarios.

### CSV
- CSV files are easily readable by Pandas Framework we use
- We keep dialogues of characters and also their gender information in CSV files.

## Processed DB

Contains our final CSV files, all_characters.csv is for all the character information from all over the movies that we use and all_movies_emotions.csv is all the processed data (all emotion scores of all the dialogues)

## Codes

### StepByStep Conversion
- Shows how we convert the data into different formats


### Clustering FinalDB
- Shows how we cluster the characters based on emotions

### Final Notebook
- Shows all the codebase we have in sections
