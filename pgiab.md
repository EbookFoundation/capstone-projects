# Gutenberg in a Box Project

## Background

Project Gutenberg is a 47 year old organization whose mission is to make public domain works available for free on the internet. To date, over 60,000 works, mostly books, have been posted.

Today, there are still parts of the world where access to the global internet is limited or non-existent. Rural parts of world from Alaska to Africa are still have little or no bandwidth to connect to the internet. Other parts of the world may be disconnected because of censorship or social strife.

In response, the [Internet-in-a-Box project](http://internet-in-a-box.org/) has produced open-source designs for self-contained hotspots based on RaspberryPi computers. Content modules can be installed by plugging in USB drives with self-contained websites.

USB flash drives costing <$50 are now available that can contain all 60,000 works from Project Gutenberg. Only a small fraction of these books are available among the Internet-in-a-box content modules.

## Plan

This project will create a Project Gutenberg web service for the Internet-in-a-Box. The team will develop an [Ansible script](https://docs.ansible.com/ansible/latest/index.html) to install a web server and search database into the module. Building on elements from the global Gutenberg website, the team will build a set of special-interest book lists to supplement the search facility - classics, scifi, history, etc. along with general directions on how to use the module.

## Goal

Build a demo with RasperryPi hardware, a Project Gutenberg plugin, amaze our friends and family.

## Whitespace

Although the scope of this project is to build a Project Gutenberg plugin, wherever possible, we should think about making sure that we pave the way for future plugins with free ebooks from other content sources - for example textbooks or academic books. We should also think about the needs of users who are disconnected from the global internet.

## Proposed Team
[Zion Fung](https://www.linkedin.com/in/zionfung/)   
[Vincent Lee](https://www.linkedin.com/in/vincent-lee98/)   
[Alex Schlumpf](https://www.linkedin.com/in/alex-schlumpf-1317a314a/)  
[Sean Trinh](https://www.linkedin.com/in/sean-trinh/)   
[Hariharan Vijayachandran](https://www.linkedin.com/in/hariharan-vijayachandran-16a5b8133/) 

## More about our team 
We are passionate in supporting an open source non profit. We have a wide range of skill sets that would be directly applicable to this project from dealing with cloud infrastructure to creating 
full stack applications with secure back ends and visually pleasing front ends.    

## Our Plan
MVP: Use Ansible to download a basic node server from git that displays books in pure html which you can download. 
Section off types of books by either genres/labels provided or if not, comparing book titles to info from online/the project gutenburg website.


### Ideas
1) We would like to provide an interactive website using react. This is however dependent on the types of computers/ devices that the users would have access to. 
2) Provide some caching of all time popular books from the gutenberg website so that users would be able to have quick access to commonly read books without betraying privacy. 
3) Depending on the types of devices they have it might be a lot more beneficial to provide the users the ability to read online then download. 
4) Use cookies so that users don’t have to login but can see their recently viewed books.
5) Scalability as in if there are multiple pi’s in an area could we have one act as a load balancer. 

Additional hardware required:
    Raspberry Pi wifi module (depending on which version)

