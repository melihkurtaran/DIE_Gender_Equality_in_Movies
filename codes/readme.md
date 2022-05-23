First step to do dowloading the necessary libraries as shown in following piccture.

![Screenshot 1](https://github.com/melihkurtaran/DIE_Gender_Equality_in_Movies/blob/main/codes/pictures/p1.png?raw=true)


Implementation of get_character_dictionary_from_html presented in the code. 
It takes 4 paramaters. First is the name of the html file, second the position of character's name start, third is the position of dialogue start and the
last paramater is the position of scenarios.

The function returns two dictionaries, first one is character_dialogues, name of the characters as key and their dialogues as value, Second is
the scenarios.

![Screenshot 2](https://github.com/melihkurtaran/DIE_Gender_Equality_in_Movies/blob/main/codes/pictures/p2.png?raw=true)

In datapreprocess step, all characters' gender must be assigned for the analysis so it could be automated by using the Gender API as shown in below code.

![Screenshot 3](https://github.com/melihkurtaran/DIE_Gender_Equality_in_Movies/blob/main/codes/pictures/p3.png?raw=true)
