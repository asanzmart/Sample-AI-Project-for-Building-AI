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
![Help Desk](https://commons.wikimedia.org/wiki/File:%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0_%D0%BC%D0%BE%D1%81%D0%BA%D0%BE%D0%B2%D1%81%D0%BA%D0%BE%D0%B3%D0%BE_%D0%BA%D0%BE%D0%BB%D0%BB-%D1%86%D0%B5%D0%BD%D1%82%D1%80%D0%B0_%D0%BF%D0%BE_%D0%B2%D0%BE%D0%BF%D1%80%D0%BE%D1%81%D0%B0%D0%BC_%D0%BA%D0%BE%D1%80%D0%BE%D0%BD%D0%B0%D0%B2%D0%B8%D1%80%D1%83%D1%81%D0%B0.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
