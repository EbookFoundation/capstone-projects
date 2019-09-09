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
    Zion Fung - Front End
    Vincent Lee - Back End  
    Alex Schlumpf - Front End  
    Sean Trinh - Back End (Experince with Ansible)
    Hariharan Vijayachandran - Front End

## Our Plan
    MVP: Use Ansible to download a basic server from git that displays books which you can download

    Provide a interactive frontend using React and scalable backend. 
    Provide user friendly features: 
        1) Login
        2) Recommended Books
        3) Recently Viewed Books
        4) Trending on your network
        5) Read books on the site
        6) Rate books
    
    Additional hardware required:
        Raspberry Pi wifi module (depending on which version)