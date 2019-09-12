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

## Proposal

We are Dylan DiGeronimo (ddigeron@stevens.edu), Rachel Kim (rkim5@stevens.edu), Ryan Locke (rlocke@stevens.edu), Naseem Miah (nmiah@stevens.edu), and Taleen Mitchell (tmitche2@stevens.edu), and we are extremely excited to have the chance to work with the Free Ebook Foundation to bring Project Gutenberg to more and more people around the world. The five of us posess a broad skillset, including experience with Linux systems, front and back end web development, database configuration, interface design, technical writing and documentation, and cybersecurity.

Our end goal in this project is to produce a workable demonstration of the Project Gutenberg in a Box module, running on a RaspberryPi minicomputer. This system will be able to be easily deployed as an Internet in a Box module, and upon deployment will use Ansible to automatically install and setup various components, which will come together as a whole to form the PG in a Box system. Among these components will be a web server, hosting an easy to use web application that will allow users to interact with the library system. Another will be a database system containing the full PG library, which will allow users to search the system as well as find books based on categories, including genre. Additionally, as many of our module's users will not have regular access to broadband internet, we will create a full suite of documentation to simply illustrate how to make full use of the system. Finally, as our team contains students passionate about cybersecurity, we also plan to make the security of our system a top priority, and will ensure the privacy and integrity of any user information, as well as making sure to mitigate any vulnerabilities introduced by our module.
