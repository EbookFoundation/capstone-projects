# Gutenberg in a Box Project

## Background

Project Gutenberg is a 47 year old organization whose mission is to make public domain works available for free on the internet. To date, over 60,000 works, mostly books, have been posted.

Today, there are still parts of the world where access to the global internet is limited or non-existent. Rural parts of world from Alaska to Africa are still have little or no bandwidth to connect to the internet. Other parts of the world may be disconnected because of censorship or social strife.

In response, the [Internet-in-a-Box project](http://internet-in-a-box.org/) has produced open-source designs for self-contained hotspots based on RaspberryPi computers. Content modules can be installed by plugging in USB drives with self-contained websites.

USB flash drives costing <$50 are now available that can contain all 60,000 works from Project Gutenberg. Only a small fraction of these books are available among the Internet-in-a-box content modules.

## Plan

To build off of open source software which will effectively circumvent distribution cost, compression concerns, and the improve the overall adoption rate of Project Gutenberg In A Box. Currently Internet in A Box (internet-in-a-box.org) and Kiwix (kiwix.org) are open source platforms which serve webpages that have been scraped from online. These scraped webpages must be stored as STATIC webpages and then compressed into the ZIM file type. ZIMs are the portable modules which iiab and kiwix support. https://en.wikipedia.org/wiki/ZIM_(file_format)   

Currently project gutenberg exists as a ZIM and the source code to create it is open source, https://github.com/openzim/gutenberg. We plan to edit the source code of the project gutenberg zim repository to support our goals and distribute it to the open source platforms.

## Goal

Gear project gutenberg for teachers to use in areas where internet is not accessible. 

MVP: Add search features and tabs for book categories to the current ZIM implementation. 

Additional: 
    
    1) Support the ability for teachers to add a reading list. 
    
    2) Create a most popular reading list based off of what users are looking at. Most likely will require a seperate backend.

## Team
[Zion Fung](https://www.linkedin.com/in/zionfung/)  
[Vincent Lee](https://www.linkedin.com/in/vincent-lee98/)   
[Alex Schlumpf](https://www.linkedin.com/in/alex-schlumpf-1317a314a/)  
[Sean Trinh](https://www.linkedin.com/in/sean-trinh/)   
[Hariharan Vijayachandran](https://www.linkedin.com/in/hariharan-vijayachandran-16a5b8133/) 

## More about our team 
We are all 4/4 (senior) computer science students at Stevens Institute of Technology in Hoboken, NJ. We are passionate in supporting this non-for-profit project. We all highly value early childhood education and the sharing of knowledge. Each member posseses a wide range of knowledge and expertise varying from creating creative front ends to complicated backends and are enthusiastic to be contributing to a project that highlights our skills and provides an outlet to demonstrate them with an impact.   