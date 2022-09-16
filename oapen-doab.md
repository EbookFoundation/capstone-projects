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

## Stack proposal

General disclaimer: this is open to change for anything that better integrates with the organization's existing systems

### Business logic/mining engine (1):
* Text preprocessing and trigram generation using Python NLTK
    * Some possibly interesting data available [here](https://oapen.org/resources/15635975-metadata)
* Run [n] times per day(?) with a cronjob on DO/AWS to create trigram map, output to PostgreSQL database for access on website
* Unsure of computational complexities and NLTK capabilities, may have to use cloud provider like AWS (a single DO droplet large enough may be very expensive)
* Use trigrams to run suggestion service API layer, can interact with frontend web stack
* NLTK has good libraries for creating Word N-gram models which can easily be accessed by the web app

### Web product (2):
* Node backend/authentication/middleware (with TypeScript) and React frontend
    * (strongly preferred Next.js to create production+dev env)
* Allows for the frontend interface and the ingest system to be developed independently, allowing for parallel development
* PostgreSQL for data storage

### Advisors

- Ronald Snijder, OAPEN
- Eric Hellman, Free Ebook Foundation

### Proposed team

**[Justin O’Boyle](https://github.com/justinoboyle)**
* Role: Full-stack developer (preferred frontend, “middle-logic” and user experience, API layer, deployment pipeline)
* Experience:
    * Routing+styling with Node/React/Next/TypeScript for a medium-sized financial product (1.5 years+), created frontend MVP while working closely with professional design team
    * Backend realtime trading system diagramming, maintenance and feature implementation for medium-sized financial product at large scale (1.5+ years+)
    * Experience with maintaining AWS products like Lambda, S3, CodeBuild, CodePipeline and DigitalOcean buckets for backend deployments
    * Experience with Vercel, Heroku and CloudFlare for frontend deployments


**[Maxim Zaremba](https://github.com/max-zaremba)**
* Role: Full-stack developer (experience with machine learning, frontend UI, and trading systems)
* Experience: 
    * Created a front-end UI in Typescript for the bloomberg professional application
    * Developed a back-end Python service to load and deliver live position data
    * Utilized machine learning (Pandas, SKLearn) to allow for automated matching between positions during reconciliation of derivative collateral
    * Worked on microservice code generation improvements in C++, including adding C++ 11 specific features, such as templated functions
    * Designed a judo class management application using Google’s Flutter and Firebase

**[Celina Peralta](https://github.com/celinanperalta)**
* Role: Backend developer (business logic (text mining), database design, API design)
* Experience:
    * Worked on computation engine for a business science application in React and Typescript.
    * Experience with NLTK through a text mining course at Stevens. Familiarity with foundational concepts concerning text mining and NLP models.
    * Worked as full stack dev on two MERN applications created with team members at Stevens for Web Programming courses.
    * Various backend API implementations


**[Joseph Sofia](https://github.com/j-sofia)**
* Role: Developer
* Experience:
    * Full-stack web/mobile dev for coursework
    * Business applications in .NET and Blazor/Angular; UI, business logic, databases
    * Business backend integrations
    * Azure deployment pipelines, function apps, and db storage
    * Databricks distributed data analytics processing

**[Peter Rauscher](https://github.com/peterrauscher)**
* Role: Developer
* Experience:
    * Full-stack web development with the MERN stack
    * EDI automation using C#/.NET to send and receive purchase orders and shipment updates
    * ASP.NET web development for intranet business applications
    * Experience with AWS, Azure, and DigitalOcean deployment and administration
    * Built a web crawler with Python and BeautifulSoup for cross-checking product prices on Amazon, eBay, and Facebook Marketplace


### More about the team 

As a whole, our team is very comfortable with modern web development and agile practices. We will work asynchronously (but of course will be ready for all of our check-in meetings) and self-assign tickets as we go through Github projects. Our workflow will involve setting weekly Milestones (GitHub feature) of collections of Issues (tickets) that are assigned to each group member appropriately based on bandwidth and experience. As an organized team, you will be able to view our progress through Github’s issue tracker and milestones (which we can more clearly define once we meet with the project manager/advisors). 

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



