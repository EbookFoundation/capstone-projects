# Gutenberg in a Box Project

## Background

Project Gutenberg is a 48 year old organization whose mission is to make public domain works available for free on the internet. To date, over 63,000 works, mostly books, have been posted. The orgaization, run mostly volunteers, _invented_ the ebook!

The Free Ebook Foundation (FEF) has been helping Project Gutenberg (PG) renovate their software and platform for the past 2 years. This work partially resulted from the efforts of a Stevens Institute temam from 2017-2018.

“Bookshelves” are lists of PG books that help users navigate PG. See them [here](https://www.gutenberg.org/wiki/Category:Bookshelf).

## Problem

- System for creating and updating bookshelves is failing
  - PHP/wiki interface
  - Loaded into production Postgres db by scraping wiki!
  - Few people maintaining it.
  - No way to create personal bookshelves or reading lists
  - Recurring security issues with PHP

## Proposed Solution

- Registrationless Bookshelf Builder

  - HTML5 local storage + javascript
  - Button on Item page
  - Import/export lists for sharing

- Bookshelf Management App
  - Python/Flask or Python/CherryPy with Postgres backend
  - Managers can make new bookshelves and categories
  - Moderators can add/remove items from Builder Bookshelves

## Goal

Have prototype system running by April, 2021 for public review, move to production bin May.

## Timeline

| Dates               |                                                               Milestones                                                               |
| ------------------- | :------------------------------------------------------------------------------------------------------------------------------------: |
| 09/14/20 - 9/21/20  | Review existing code/documentation, and implementation goals for deeper understanding of technical aspects of problem |
| 09/21/20 - 12/02/20  | Document requirements of PG deployment environment and evaluate technology options. |
| 10/02/20            |   Deliver user stories for dev team to iteratively implement; allowing the dev team to reevaluate any cases.   |
| 10/09/20            |   Deliver implementation plan detailing technical feasability and decisions. Document what tools and technologies will be used.   |
| 10/12/20 - 03/19/21 |    Main Development Period: Iteratively develop user stories several sprints. Demo new features at the end of sprints for feedback.    |
| 03/19/21            |                                                       Final demo of new features                                                       |
| 03/19/21 - 04/30/21 |                              QA period to resolve issues and bugs. Final preparation for product release                               |

_Dates/Milestones are tentative and subject to change._

## Team

Adam Undus (aundus@stevens.edu)
Liam Nagel (lnagel@stevens.edu)
John Dyer (jdyer@stevens.edu)
Damon Del Priore (ddelprio@stevens.edu)
Anthony Ciccone (aciccone@stevens.edu)

## More about our team

Adam Undus - Most of my experience is in web development as I have worked on two teams with web facing applications. I have experience in Node.js with several database implementations, both cloud based and on prem. Overall experienced in both frontend and backend web facing development, and excited to take on this new challenge and learning experience.

Liam Nagel - I have a fair amount of experience in web development from Web programming 1 and 2 both resulting in full web apps for the final project. I’ve worked with a good number of web technologies and I am looking forward to working with the new technologies we will be using for this project.

John Dyer - I have taken a database class and am currently in a web programming course. I have also done work on the database structure of an app project using Node.js. I have not yet worked with cherrypy but am excited to learn a new method of database management.

Damon Del Priore - My light experience in web development stems from my computer science curriculum. After taking web development and database courses, I have felt passionate about the designs of web pages. In past projects, I have been less active in programming outside of Java or C++, but I am prepared and excited to be working with a new database.

Anthony Ciccone - My experience is mainly in web development, as I took both Web Programming 1 and 2. Stevens has us take many different classes for our major, that introduces us to a wide variety of topics and languages. I may not, currently, be confident in the skills needed for this project. After putting in time to familiarize myself and learn more, I believe that I'll be a great fit for this team/project.
