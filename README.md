# COVID-19 Simulation
![image](https://github.com/ashan-medigodella/covid-19-simulation-netlogo/assets/57296166/9e99c5df-6e17-47be-b99c-7800af6448ea)

## Overview
### This NetLogo model simulates the spread of COVID-19 through a population. It allows exploring how various interventions like social distancing, mask wearing, and vaccination impact the spread of the disease.

This NetLogo model simulates the spread of COVID-19 through a population. It allows exploring how various interventions like social distancing, mask wearing, and vaccination impact the spread of the disease.

#### Interface Elements
The interface has the following elements:

* Setup button - Sets up the model by clearing the world and creating the initial population of turtles
* Go button - Runs the simulation one tick at a time
* Init-pop slider - Sets the initial number of people (turtles)
* Init-infected slider - Sets the initial number of infected people
* Mask-percent slider - Sets the percentage of turtles wearing masks
* Social-distancing slider - Sets the amount of social distancing; higher values make turtles stay further apart
* Vaccination-percent slider - Sets the percentage of turtles vaccinated at start
* Infection-chance slider - Chance of spreading infection to nearby turtles
* Recovery-rate slider - Chance infected turtles recover each tick
* Mortality-rate slider - Chance infected turtles die each tick
* Infected, Recovered, Susceptible plot - Tracks counts of each turtle type over time
* People alive plot - Total number of turtles alive over time

#### How it Works
At setup, the given number of turtles are created and random ones are set as infected.

Each tick:

* Turtles move randomly
* Infected turtles spread infection to nearby turtles based on infection chance
* Infected turtles either recover, die, or remain infected based on recovery and mortality rates
* Masks, social distancing, and vaccination reduce the spread of infection.

#### Things to Explore
Try different combinations of the parameters to see the impact:

* Higher mask percent and social distancing should slow spread
* Higher vaccination percent should reduce total infections
* Higher recovery rate and lower mortality leads to more recovered
* Compare different intervention strategies like:

* Masks vs social distancing
* Masks + social distancing vs vaccination
* Vaccination alone vs masks + social distancing
* Extensions

Some ways the model could be extended:

* Add age categories for turtles with different mortality rates
* Allow mask wearing or social distancing to change during the simulation
* Add a "quarantine" feature where infected turtles stop moving
* Allow vaccination to increase over time to model a rollout
* Add immunity that wears off over time

## Watch the full Test Video!
<a href="https://drive.google.com/file/d/158FZq1dRz44qPw4sUxkN5h-mMAwUIXMl/view?usp=sharing" target="_blank">
  
Credits
This model is inspired by the NetLogo Virus model. The documentation was written by Ashan Medigodella

