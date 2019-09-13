# Copyright Records Search

## Background

Many books published between 1923 through 1977 may be in the public domain either because their copyright was not registered, or because their copyrights were not renewed after an initial term. Unfortunately, determining the copyright status of these books requires a review of the copyright records of registration and renewal. Unfortunately, these records were all on paper. Digital scans of these records were made, and are available from the Internet Archive, but searching the scans is not easy.

To make this task more manageable, we will begin with one set of records, the Catalog of Copyright Entries (CCEs). The CCEs are comprised of about 450,000 pages and are printed compilations of brief registration and renewal records. These records were published by the Copyright Office at regular intervals, ranging in length from semi-weekly to semi-annually. The CCEs are divided by classes of works, such as books, periodicals, music, drama, maps, photographs, etc. For our pilot, we will focus on a small subset of the CCEs, 10,000 pages of book registration records published between 1923 and 1964.

New York Public Library has hired a contractor to take one set of the scanned records, the Catalog of Copyright Entries (CCEs), [and convert them into well-structured XML data](https://www.nypl.org/blog/2018/03/30/unlocking-record-american-creativity). The CCEs are comprised of about 450,000 pages and are printed compilations of brief registration and renewal records. These records were published by the Copyright Office at regular intervals, ranging in length from semi-weekly to semi-annually. The CCEs are divided by classes of works, such as books, periodicals, music, drama, maps, photographs, etc. Conversion of a set of 10,000 pages of book registration records published between 1923 and 1964 has been completed, and the result [is publicly available](https://github.com/NYPL/catalog_of_copyright_entries_project).

There is a need for a user-friendly search interface for librarians, archivists, and rights researchers to make use of the XML data.

Update: The dataset has been used to find ["secretly in the public domain"](https://www.crummy.com/2019/08/09/0) and has gotten [some publicity](https://www.vice.com/en_us/article/kz4e3e/millions-of-books-are-secretly-in-the-public-domain-you-can-download-them-free)

## Plan

This project will produce a user-friendly, open-source search interface for the structured renewal records.

### Team
This project will require team members to combine technology with some understanding of copyrights and the public domain, and to analyse user requirements.

#### Members
 - Dylan DiGeronimo (ddigeron@stevens.edu)
 - Rachel Kim (rkim5@stevens.edu)
 - Ryan Locke (rlocke@stevens.edu)
 - Naseem Miah (nmiah@stevens.edu)
 - Taleen Mitchell (tmitche2@stevens.edu)

#### About the Team
We are Dylan DiGeronimo, Rachel Kim, Ryan Locke, Naseem Miah, and Taleen Mitchell, and we are extremely excited to have the chance to work with the Free Ebook Foundation and the New York Public Library to help make this critical information available to more users. The five of us posess a broad skillset, including experience with Linux systems, front and back end web development, database configuration, interface design, technical writing and documentation, and cybersecurity.

### Objectives
The team will:

 - become familiar with the structure of the data. Over the years, the renewal records used four different formats, so the system will need to deal with four different data structures.
 - interview potential users to understand use cases and extract work flows and feature sets for the search system.
 - identify appropriate search, application, web-service and user interface software for implementation of the search system.
 - implement and deploy the system.
 - user-test the system

### Issues
Issues the team will need to resolve

 - how to connect record metadata with original scans
 - do users need accounts?
 - will there be an api?

### Wrap-up
The NYPL team is very excited at the possibility that a user facing service could be built; they feel it may be instrumental in demonstrating the value of the converted records and securing funding for the remaining conversion work. Documentation of the project will need to enable future addition of the records that have not yet been converted.

### Schedule

 - mid May, 2019 -  Press Release!
