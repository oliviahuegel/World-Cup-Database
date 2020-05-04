# World Cup Database
This project is based on the 2018 FIFA World Cup teams. There are 32 competing nations in the tournament, divided into 8 groups, A through H, with each group having 4 countries. 

So far, the group stage games have been played, with each country playing exactly 3 matches. 

A CSV file for this project, worldcup.csv, contains 32 records, one for each country. Each record has 4 fields – the name of the country, the group the country belongs to, goals scored, and points earned. This project will be read in the CSV file into an array of structure and implement functions that will search this array based on the country name, group, or points earned (user input).

Files:
country.h: This file contains definitions and prototypes of functions that are defined in country.c. The structure country is also defined to store information about a country.
country.c: This file contains the completed function definitions. There are three functions, search_by_country, search_by_group, and search_by_points. In each of these function, the user is prompt to enter country/group/points and print out the records that match. If there is no match, the program will not print anything.
worldcup.c: This file has the main function. You can see an array of structure country here. The main function by reads in the records from the CSV file (name is passed from command line) into this array.
