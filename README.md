<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Help-the-Help Deskbot

Final project for the Building AI course
Building AI course project

## Summary

Help a Help Desk team to validate and adjust the categorizationand & prioritization of tickest in a fast growing imput queue.  

Building AI course project

## Background

A help Desk service is receiving hundreds of help tickets pre hour clasified in Incident Catergory and Severity by the requester user. Sometimes requesters clasify incidents in the wrong category and trends to overpriorize with a higher severity than needed. 

For the HD team performance is critical to have the right category clasification in other to assign incidents to the right expert. 
And with a high input ratio of incidents, priorice real higher severities is needed to resolve most critical incidents first.
While solving each incident the HD team will reclasify the ticket in a Final Category and Final Severity that they consider more usefull to increase global HD performance.


## How is it used?

The tickets will include a description of the problem and the impact writen by the requester in free text. Based on a NLP analisis of the free text the HtH Deskbot will compare the Category-Severity clasification provided as input by the user with the final clasifictions of most similar description in a collection of recent presolved samples. Then it will decide to confirm or reclasify the ticket in Bot-Category and Bot-Severity clasifications. The team will now use Bot clasification to priorize and work with tickests in the queue. 

In subsequent cycles the system will also use the experience to learn when its corrections are good or not and adjust parametrization to better guess the Final choices of the HD Team


Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Help Desk]<imh src="https://upload.wikimedia.org/wikipedia/commons/b/b4/%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0_%D0%BC%D0%BE%D1%81%D0%BA%D0%BE%D0%B2%D1%81%D0%BA%D0%BE%D0%B3%D0%BE_%D0%BA%D0%BE%D0%BB%D0%BB-%D1%86%D0%B5%D0%BD%D1%82%D1%80%D0%B0_%D0%BF%D0%BE_%D0%B2%D0%BE%D0%BF%D1%80%D0%BE%D1%81%D0%B0%D0%BC_%D0%BA%D0%BE%D1%80%D0%BE%D0%BD%D0%B0%D0%B2%D0%B8%D1%80%D1%83%D1%81%D0%B0.jpg" width="300">


## Data sources and AI methods
Data will come from the historcal data base of the HD Ticketing system. A collection of closed tickets that have a final categorization from the HD team will be used as Train Data and a selection of tickets prior to be solved will be selected as test data. Comparation of Deskbot categorization versus HD final categorization will measure the level of precision of teh Dekbot and will input optimization process.
   
Algoritms considered to be used:
   * Bayesian clasification to select the worlds that are Relevant/non-Relevant in the text
   * Nearest Neighbor to select categorization
   * Logistic Regresion to calculate priority in range [0.0 , 1.1]
   
 
## Challenges

Comunication of the system to users must be carfully planned. Users might feel unconfortable with an automatic bot changing their severity perception. 
Users which tickets priority is reduced must be explained it is in the benefit of the overall performance and faster response to higher impact incidents.

## What next?

In addition of AI programing skills experience in HD service management is requiered. Stadisticall Analisys of ticketing data will provide insight of the relevant words, probability of severity overrating, etc.


## Acknowledgments

* [Mos.ru, CC BY 4.0](https://creativecommons.org/licenses/by/4.0) / [via Wikimedia Commons](https://creativecommons.org/licenses/by/2.0)
