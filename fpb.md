# Free-Programming-Books Project

## Background


[Free Programming Books](https://github.com/EbookFoundation/free-programming-books) is a list of over 3,000 free programming books and other free programming resources, maintained collaboratively as a repository on Github. With lists in 37 spoken languages, it has helped countless programmers around the world acquire and improve their programming abilities.

Free Programming Books is a product of Open-Source culture, and continues to be a stunning example of what con be created when large numbers of people work together.
It was originally a clone of a StackOverflow page that was moved to GitHub by Victor Felder for collaborative updating and maintenance. After going viral on Hacker News, it grew rapidly and is now one of the most popular repositories on Github, with over 200,000 "stars", over 6100 commits, over 1600 contributors, and over 43,000 "forks". In 2017, the Free Ebook Foundation assumed responsibility for the administration and care of the repository.

### How it Works

Git is an open-source collaboration and version-control system written by Linus Torvalds. Github is a website used by programmers to structure the workflow and collaboration around the software they develop. A developer wishing to contribute an improvement to a software project first "forks" the repository containing the software, then modifies the code to implement the new feature or bugfix. When they're satisfied with their changes and have tested it for functionality, they create a "pull request" asking that changes be pulled into the main branch of the projects code. If the owner of the repository likes the change, the pull request is merged.

Free Programming Books applies Github's workflow to the creation and maintenance of a list of books. The cycle of fork, modify, pull request and merge has happened over 4,000 times, resulting in the list's grand scope and comprehensiveness. 


## Issues

- It’s just a bunch of markdown lists, minimally structured.
- Can’t search it.
- Can’t export and reuse it.
- How to archive all the books?


## Proposed Project

1. Parse the lists into a structured database
    - Github Actions, Continuous Integration Python?
2. Load the database into a website
    - Django? Postgres? AWS?
3. Export a data file.
    - CSV? XML? OPDS?
4. Download and store the books somewhere.
    - Internet Archive?


## Goals

- Build parser running as a GitHub action by end of 2021
- Do something fun with it by April 2022

## Team

Add names and links here.

## More about our team 

Describe your team here.