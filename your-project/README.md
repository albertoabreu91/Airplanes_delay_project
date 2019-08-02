<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Title of My Project
*Alberto Abreu*

*Data Analytics, Barcelona & 01/08/2019*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
his paper aims to study the flights' delays and its relationship with countries, airports, and daytime using correlation analysis and hypothesis testing from real data obtain through the Aviation Edge API from July 25, 2019, to July 29, 2019. The purpose is to compare Spain’s delay time, in terms of departure, arrival and total delay time in minutes and see if it is statistically different from the rest of Europe. Moreover, the same comparison is provided with the Barcelona Airport (El Prat de Llobregat) against the rest of the airports in Spain.

<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions
The aim of this paper is to compare and test differences between the mean departure delays on different levels.

1- The mean departure delay in Spain is greater than in the rest of Europe.

2- The Barcelona Airport mean departure delay is lower in comparison with the airports in Spain.

3- Vueling is not the best airline if you are in a hurry, as the mean departure delay is greater than the rest of the carriers.

4- Daytime in terms of morning, afternoon and evening, night has an effect in classifying the flight as a delayed flight. (By regulations, if the flight is delayed more than 15 min it should be classified as delayed).

<a name="dataset"></a>

## Dataset
The dataset corresponds to around 70 thousand flights gathered in real-time from July 25 and July 29 of 2019, using the Aviation Edge API. The response is a JSON file with more than 29 attributes of a flight departing from a specific airport and with the status of landed. Among the many attributes, this paper used were: Airline name, status, departure airport, scheduled departure time, departure delay time, arrival airport, scheduled arrival time, arrival delay time and country of departure among others.
A function was created to obtain all the flight information from all the airports of Spain, Italy, France, and Germany with a single loop, looping through a list of airports in their IATA code formats.

[Dataset](https://aviation-edge.com/) 


<a name="workflow"></a>

## Workflow

1- Setting up the objective
2- Writing down some hypothesis
3- Requesting the data
4- Cleaning the data
5- Explore the data
6- Descriptive statistics analysis
7- Inferences statistics analysis
8- Hypothesis testings
9- Recommendations

<a name="organization"></a>

## Organization
1- Trello as our project management tool. 

2- GitHub as our verion control system. 

3- Terminal to communicate with our VCS. 

4- Python as our data wrangling language and visulizations

5- SequelPro to store the data. 

6- Slides as our presentation tool.

<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/albertoabreu91/Project-Week-5-Your-Own-Project)  
[Slides](https://slides.com/albertoabreu/deck-2#/)  
[Trello](https://trello.com/b/L9GDhXas/project-4)  
[Medium](https://medium.com/@abreualberto91/flight-delays-in-europe-dad1af88711a)
