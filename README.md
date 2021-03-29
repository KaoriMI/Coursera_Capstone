# Applied Data Science Capstone
This is my final capstone project for [IBM Data Science Professional Certificate Course](https://www.coursera.org/professional-certificates/ibm-data-science?utm_source=gg&utm_medium=sem&campaignid=2087860785&utm_campaign=10-IBM-Data-Science-ROW&utm_content=10-IBM-Data-Science-ROW&adgroupid=79675709271&device=c&keyword=ibm%20data%20science&matchtype=e&network=g&devicemodel=&adpostion=&creativeid=489197596485&hide_mobile_promo&gclid=Cj0KCQjw0oCDBhCPARIsAII3C_GJ_EmComqKvklmH26c7OVgh9VtcI6gIqDurMjlWmX9s8NuoMTP-EUaArQsEALw_wcB) on Cousera, which I finished May 2020.

## Introduction
In this project, I used the skills and the tools for location data to explore a geographical location.
I explored **Japanese restaurants** in **New York**. I am originally from Japan and it's been 5 years since I left my country. And, I enjoy trying out a Japanese restaurant when I travel. The reason could be because I am not completely happy with the quality of Japanese restaurants in my city or simply I want to try a new restaurant as the number of the Japanese restaurants in my city is limited.
This report is targeted for people like me, who want to have Japanese food during the trip especially to a big city, New york. <br>

When people look for a restaurant, people mostly check the price, rating and location. Therefore, we will explore Japanese restaurants in New York based on these criteria.

## Dataset
* Geographic coordinate of the boroughs and the neighborhoods in New York:
  https://geo.nyu.edu/catalog/nyu_2451_34572

* Getails of restaurants including price tier, rating, and location in New York: **Foursquare API**.

* Number of hotels in each Neighborhood Tabulation Areas (NTA):
  https://data.cityofnewyork.us/City-Government/Hotels-Properties-Citywide/tjus-cn27

* Gis data of Neighborhood Tabulation Areas (NTA) in New York:
  https://data.cityofnewyork.us/City-Government/Neighborhood-Tabulation-Areas-NTA-/cpf4-rkhq

* Geographic coordinate of New York: **Google Maps API geocoding**.

## Methodology 
In this project, we will find Japanese restaurants which are well balanced between price and rating.<br>

In the first step, we will collect the required data: rating and price tier of every Japanese restaurant in New York.<br>
In the second step, we will cluster each restaurant and find the well-balanced restaurants.<br>
In the final step, we will map the recommendation on the map.<br>