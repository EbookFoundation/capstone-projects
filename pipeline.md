# Ebook Update Pipeline Project

## Background

Libraries would like to get free ebooks into their catalogs, but too often, their information is out of date. Many ebook authoring systems allow the books to be continually updated; this is especially true of software documentation books which are updated along with the software they document.

There needs to be a way for ebook authors to announce new books and version updates to distributors, aggregators and libraries and to provide these distribution channels with the metadata and files they need to promote and distrute these books.

## Plan
This project will create an update pipeline for these ebooks by implementing update hooks in a variety of open source ebook authoring systems. The Free Ebook Foundation has demonstrated the viability of such a system in its GITenberg project, which uses Github hooks to announce the possible availability of an updated version of a book built from a git repository, and YAML-based metadata files to describe the ebooks being updated.

### Team
This project will attempt to scale this approach by implementing update hooks in a number of open-source ebook authoring tools. As the tools are based on different software environments, this project will need a team with a variety of programming skills.

### Objectives
Ebook authoring systems the team will target:
 - Wikibooks (PHP)
 - Gitbooks (Node/Javascript)
 - Pressbooks/Rebus (PHP)
 - Readthedocs (Python)
 - Standard Ebooks (Python)
 - Bookdown (R)

The update server will then use Unglue.it to provide syndication feeds for downstream consumption.

### Issues
Issues the team will need to resolve

 - metadata format and dictionary
 - versioning and duplicates

### Wrapup
Finally the team will produce how-to documentation to enable other ebook-building systems to add update hooks to their own systems.