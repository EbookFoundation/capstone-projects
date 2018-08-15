# Copyright Renewals Search

## Background

Many books published between 1923 through 1977 may be in the public domain either because their copyright was not registered, or because their copyrights were not renewed after an initial term. Unfortunately, determining the copyright status of these books requires a review of the copyright records of registration and renewal. Unfortunately, these records were all on paper. Digital scans of these records were made, and are available from the Internet Archive, but searching the scans is not easy.

To make this task more manageable, we will begin with one set of records, the Catalog of Copyright Entries (CCEs). The CCEs are comprised of about 450,000 pages and are printed compilations of brief registration and renewal records. These records were published by the Copyright Office at regular intervals, ranging in length from semi-weekly to semi-annually. The CCEs are divided by classes of works, such as books, periodicals, music, drama, maps, photographs, etc. For our pilot, we will focus on a small subset of the CCEs, 10,000 pages of book registration records published between 1923 and 1964.

New York Public Library has hired a contractor to take one set of the scanned records, the Catalog of Copyright Entries (CCEs), [and convert them into well-structured XML data](https://www.nypl.org/blog/2018/03/30/unlocking-record-american-creativity). The CCEs are comprised of about 450,000 pages and are printed compilations of brief registration and renewal records. These records were published by the Copyright Office at regular intervals, ranging in length from semi-weekly to semi-annually. The CCEs are divided by classes of works, such as books, periodicals, music, drama, maps, photographs, etc. Conversion of a set of 10,000 pages of book registration records published between 1923 and 1964 has been completed, and the result [is publicly available](https://github.com/NYPL/catalog_of_copyright_entries_project).

There is a need for a user-friendly search interface for librarians, archivists, and rights researchers to make use of the XML data.

## Plan

This project will produce a user-friendly, open-source search interface for the structured renewal records.

The team will:

 - become familiar with the structure of the data. Over the years, the renewal records used four different formats, so the system will need to deal with four different data structures.
 - interview potential users to understand use cases and extract work flows and features sets for the search system.
 - identify appropriate search, application, web-service and user interface software for implementation of the search system.
 - implement and deploy the system.
 - user-test the system
 
The NYPL team is excited at the possibility that a user facing service could be built; they feel it may be instrumental in demonstrating the value of the converted records and securing funding for the remaining conversion work. 