[![license](https://img.shields.io/badge/license-MIT-orange)](https://shields.io)  

# National-Parks
                                                                  
## Table of Contents

[Description](#description)  
[Installation](#installation)
[Technologies](#technologies)  
[Usage/Link](#usage/link)  
[Collaborators](#collaborators)

## Description
                                                                  
This is an application that allows people to search for National Parks in their state by the activity they want to do and see current weather conditions for that park.

## User Story
As an outdoor person, I want to be able to plan activity at a National Park based on the weather conditions.

## Features

Visit our website! It is desktop and mobile friendly. Simply choose the state and what activity you’re into and click search. You will be presented with any national parks in the state, link to park’s website, and address that with one click can get you directions to have you on you way! Not sure whether you need an umbrella or a parka… simply select the park and the current weather conditions will be displayed. Now you’re ready to explore the beautiful national park system.

## Motivation for development ##

Currently, you have to search the national parks and the weather separately. The need here is to see the weather for any park in a state and the weather without having to go between sites.

## Challenges ##
GitHub merge conflicts! 

## Successes ##
Amazing investment and collaboration within the group
Creating a tool that has real life value and application

## Directions for future development ##
Add NPS alerts (danger, closure, caution, and information) posted by parks
Incorporate Google Maps API with OpenWeather API to display weather maps for each search result.
Have index page display a random image from the national parks, so it’s different each visit.
Have the selected park highlight a different color when selected on search results

## Installation

Clone Repository 
*git clone https://github.com/herokuapp/HotSpot.git

 Install Dependencies
*All NPM packages required for this application (Express, Compression, Mongoose, Lite-Server and Morgan) are already listed as dependencies in the package.json file. Run the command 'npm i' command in your terminal at the root directory level to install the packages.
Ensure you have Node.js installed on your machine. The application will be invoked by entering node server.js in the command line.

Start Application
*You will see App running on port 3000! in the console. You can then view the app on http://localhost:3000/.


## Technologies
                                                        
Materialize CSS framework
National Park API
Open Weather API

## Usage 
                                                              
*Select a state of interest from the first dropdown on the main page, then select an activity of interest from the second dropdown on the same page, and click the Search button to retrieve an appropriate list of parks from the NPS database. 

*On the Search Results page, you will find a list of parks and national reserves that best fit your search criteria. Clicking on any one of these result cards will trigger the current weather in that location to the right of your list, as well as a current webcam image if one exists at that park. 

*Within each result card, there will be a link to the park's NPS webpage, as well as a link to Google Maps showing the geographical location of that park's address should you need to see it.

## Demo 

![project - one](https://user-images.githubusercontent.com/87610840/141856851-2aa1ecb0-b649-4144-b4a7-edee816ab367.JPG)
![project-one-state-activity](https://user-images.githubusercontent.com/87610840/141856860-fba9a962-a801-425b-99e1-d3fad6d3cde8.JPG)
![project-one 1](https://user-images.githubusercontent.com/87610840/141856856-06240e2e-2a50-4abf-90ee-3d83b1b97e43.JPG)
![project-one-weather and webcam](https://user-images.githubusercontent.com/87610840/141856861-8952340a-a51f-486c-8be5-b918423357f1.JPG)


## Installation

See deployed Site here:  (https://bkhanal87.github.io/National-Parks/)

See repository here:  (https://github.com/bkhanal87/National-Parks)

## Collaborators

**Main Branch**: 

Matt Bow GitHub Repo (https://github.com/mdbow22)

**Additional contributors**: 

 Anthony Korneagay GitHub Repo (https://github.com/TKShadowBlade)

 Basu Khanal GitHub Repo (https://github.com/bkhanal87)
                             
 Susie Skorncika GitHub Repo (https://github.com/Su5ieS
 
## Breakdown of tasks and roles ##
 Matt: coding fetch requests and displaying them on the results page
Anthony: selecting and adding background img for index page, setting search button on index to send search params to search results page, writing out READ.ME file
Basu: adding HTML and CSS for index page, writing/enhancing copy for index page
Susie: wireframing, search results page HTML/css, local storage

                             
