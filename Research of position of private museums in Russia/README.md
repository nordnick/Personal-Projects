# Research of position of private museums in Russia

## Quick Intro

This is a part of my current course project in the University. The project is done in collaboration with [Garage](https://garagemca.org/en) museum and this part presents a research into the main statistics of different types of museums divided by their main benefactor

## Problem statement

Ministry of Culture of Russia has created a registry for all museums in Russia ([VRM](http://vrm.museum.ru/)). This registry is poorly organized, lacks documentation and is filled in inconsistently. Furthermore, the registry is available in a website format only. 

My tasks were: 
1. Download all the information available in the registry for all museums
2. Standardize data representation
3. Present key findings for private museums and their difference from other groups

## Approach

I used [BeautifulSoup 4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) for datascraping and [Pandas](https://pandas.pydata.org/docs/) for storage and manipulation of extracted information. During the standartization part of the project I mainly used different methods of string analysis. For visualization i used [Matplotlib](https://matplotlib.org/stable/index.html#) and [Seaborn](https://seaborn.pydata.org/#) libraries.

## Results
<p float = "left" align="center">
    <img src = "https://github.com/nordnick/Personal-Projects/blob/master/Research%20of%20position%20of%20private%20museums%20in%20Russia/plots/proportion-of-museums-by-their-budget-status.png?raw=true" width = 400>
    <img src = "https://github.com/nordnick/Personal-Projects/blob/master/Research%20of%20position%20of%20private%20museums%20in%20Russia/plots/proportion-of-area-of-museums-by-their-budget-status.png?raw=true" width = 400>
<p>
