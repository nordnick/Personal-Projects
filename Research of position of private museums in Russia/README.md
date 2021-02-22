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
    
Private (Red pie) museums account for a miniscule proportion of all museums in Russia, they also represent only 4% of all museum area of Russia. That makes them rather rare and small which could be an indicator of little demand for their services from Russian citizens.
    
<p float = "left" align="center">
    <img src = "https://github.com/nordnick/Personal-Projects/blob/master/Research%20of%20position%20of%20private%20museums%20in%20Russia/plots/median-exhibition-area-by-budget-status.png?raw=true" width = 470>
    <img src = "https://github.com/nordnick/Personal-Projects/blob/master/Research%20of%20position%20of%20private%20museums%20in%20Russia/plots/median-temporary-area-by-budget-status.png?raw=true" width = 470>
<p>
    
As for area management, private museums tend to choose a more flexible strategy, preferring a bigger area for temporary projects than other groups of museums while median exhibition area is noticably smaller than in other groups. Therefore, we may assume that customers prefer temporary museum projects to stationary exhibitions and this may imply that further increase in museum area flexibility is a right choice for a private museum if it wants to attract more visitors.

<p float = "left" align="center">
    <img src = "https://github.com/nordnick/Personal-Projects/blob/master/Research%20of%20position%20of%20private%20museums%20in%20Russia/plots/median-number-of-employees-by-budget-status.png?raw=true" width = 470>
    <img src = "https://github.com/nordnick/Personal-Projects/blob/master/Research%20of%20position%20of%20private%20museums%20in%20Russia/plots/average-square-meters-per-employee-by-budget-status.png?raw=true" width = 470>
<p>
    
Private museums have one of the lowest median number of employees on the market, and, as a consequence they have to manage a bigger area than they counterparts. It is not a strictly negative feature of private museums. A lesser number of employees may result in their better productivity and creativity, as well as their ability to better attract customers by inventing and executing topical projects.

<p float = "left" align="center">
    <img src = "https://github.com/nordnick/Personal-Projects/blob/master/Research%20of%20position%20of%20private%20museums%20in%20Russia/plots/museum-classes-proportion-by-budget-status.png?raw=true" width = 800>
<p>

Top three classes for private museums are "Art", "Historical" and "Science and Technology", in all other classes there are few private museums. It is also noticable that more than 60% of private museum are classified as art-museums and this is the highest proportion of this class among all other groups of museums. This may be a sign that private museums are a very favorable environment for artists and probably a place of artistic development of Russian culture. This may be used by private museums to their advantage if marketed correctly.

<p float = "left" align="center">
    <img src = "https://github.com/nordnick/Personal-Projects/blob/master/Research%20of%20position%20of%20private%20museums%20in%20Russia/plots/median-units-of-storage-per-square-meter-of-storage-area.png?raw=true" width = 500>
<p>
    
Storage area management in private museums must be further researched to achieve an unambiguous conclusion. Median units per square meter of storage area in private museums is very low when compared to other museum groups. This may indicate one of two things:

1. Private museums ineffitiently use their storage area by upholding better storage standards
2. Other museums have smaller objects to store and, therefore units/sq meter of storage area are higher for other groups

After further research into the topic it seems like the second reason affects the statistic heavily due to other museums holding large collections of ceramics, coins and particles of instruments which all are very small in size. However, I couldn't rule out the first possible reason due to lack of publicly available information on this topic.

## Conclusion
Private museums are in a relatively unfortunate market circumstances.Their range of classes is limited to only "art", "history" and "science and technology". The demand for their services appears to be low, however, they have a potential to be important centres for artistic development and are more flexible an dready to appeal their visitors. Private museums employees have bigger area of responsibility than an average museum worker which demands professionalism and skills higher than average on the market.
### Contact me
|Contact Method    |                     |
|------------------|---------------------|
|Professional Email|nabaranovhq@gmail.com|
|Telegram          |@nordnick            |
|VK                |@nordnick            |
