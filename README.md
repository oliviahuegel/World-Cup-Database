# World-Cup-Database
With the 2018 FIFA World Cup tournament under way, let us do a project based on it. There are 32 competing nations in the tournament, divided into 8 groups, A through H, with each group having 4 countries. So far, the group stage games have been played, with each country playing exactly 3 matches. A CSV file provided for this project, worldcup.csv1 , contains 32 records, one for each country. Each record has 4 fields – the name of the country, the group the country belongs to, goals scored, and points earned. In this project, your will be reading in the CSV file into an array of structure and implementing functions that will search this array based on the country name, group, or points earned (input by user). For your convenience, I have provided three base files (country.h, country.c and, worldcup.c) to start with, study them and complete this project by adding your code to these base files. country.h: This file contains definitions and prototypes of functions that are defined in country.c. The structure country is also defined to store information about a country. You do not require to modify this file. country.c: This file contains the function definitions that you need to complete. There are three functions, search_by_country, search_by_group, and search_by_points that you need to complete. In each of these function, prompt the user to enter country/group/points and print out the records that match. If there is no match, you can simply not print anything. See example execution to get an idea. worldcup.c: This file has the main function. You can see an array of structure country here. Complete the main function by reading in the records from the CSV file (name is passed from command line) into this array.
