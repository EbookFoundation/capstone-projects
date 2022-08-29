# OAPEN/DOAB projects

 
# OAPEN Suggestion Service

## (Project #1)

## Background

[OAPEN](https://oapen.org/) promotes and supports the transition to open access for academic books by providing open infrastructure services to stakeholders in scholarly communication. Over 24,000 books and book chapters are available from the OAPEN platform.

OAPEN has experimented with a suggestion service based on semantic inferencing based on trigrams.[1] It is interested to see if this concept can be turned into a web service and integrated into its online offering.

## Goals

This project will build

- an analysis/mining engine that will ingest the 24,000 texts at OAPEN and produce a trigram map
- a web-service application that will use the trigram map allow websites to present suggestions from the OAPEN catalog based on a book identifier.

The team will use off-the-shelf components such as Django, Node, and Postgres for deployment on Digital Ocean.

### Advisors

- Ronald Snijder, OAPEN
- Eric Hellman, Free Ebook Foundation

### Proposed Team

-
-
-
-
-

### More about the team 


### Reference

[1] Snijder, R. (2021). Words Algorithm Collection - finding closely related open access books using text mining techniques. LIBER Quarterly: The Journal of the Association of European Research Libraries, 31(1), 1–22. [https://doi.org/10.53377/lq.10938](https://doi.org/10.53377/lq.10938)


# Expert System for Open Access Book Website Analysis

## (Project #2)

## Background

The Directory of Open Access Books, [DOAB](https://doabooks.org/) is a database of 60,000 academic peer-reviewed books and book chapters. The information in the database, including links, is contributed by open-access publishers around the world. This year, the Free Ebook Foundation has begun a joint project with OAPEN, the operator of DOAB, to verify and improve the links in this database.

While many of the books in  DOAB are stored in the OAPEN database, more of them are not. 30,000 of the links in the DOAB database point at HTML access pages rather than directly to document files such as PDFs or EPUBs. It can be difficult for a software agent to recognize if these links are "good", i.e. usable by researchers to access a book, or "bad", links that need to be fixed or otherwise corrected by the publisher. In addition, identification of PDF and EPUB links on these pages can enable additional services such as indexing and archival.

## Goals

This project will build an expert system to analyze webpages linked from the DOAB System. The components of such a system would include:

- a classifier that recognizes the common types of website access pages
- a classifier that recognizes the common types of error pages
- a collection of parsers that extract ebook document links from access pages

The project will build on the Free Ebook Foundation's ebook loader modules written in Python, using  Beautiful Soup, a Python library for pulling data out of HTML and XML files.

Advisors

- Eric Hellman, Free Ebook Foundation
- Ronald Snijder, OAPEN

### Proposed Team

-
-
-
-
-

### More about the team 



