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

## Team

Add names and links here.

## More about our team 

Describe your team here.