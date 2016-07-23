---
layout: post
title: Facebook and Autism Public Pages      
---

The Twitter and Facebook APIs, used to access data from the Facebook and Twitter systems, are based on different philosophies.  Twitter allows for a direct querying of posts and content.  Facebook, provides options to limit public access to content, such as designating pages as private.  Additionally, it is not possible to utilize a keyword search using the existing Facebook API to access content.  It is possible, however, to use the API to search for public Facebook pages based on specified words. 

 We used the Facebook public page search to locate pages containing the keywords ‘autism’, ‘autistic’, and ‘asperger’. Overall, 2200 pages were identified.  Of these, 1200 pages were identified as English-language pages. English language pages were determined in two ways. Pages containing an English-speaking country in the 'country' field were classified as English-language pages.  For pages without a country identifier, we used text analysis to identify english-language sites. 

The top 5 non english language countries containing autism Facebook pages are:

Country| Number of Pages
--- | ---:
Spain | 42
Germany | 26
Italy | 20
Brazil | 16
France | 15

It is important to note that the preceding country list is based on pages that self-identify with a non-english speaking country.  The most common entry (1364 sites) for the country field is "NA".  Text analysis of language-specific words could result in classification of pages that are missing a country identified to a country or set of countries. We performed this exercise to determine english-language pages, but did not repeat the exercise for non english language pages.


It is also possible to plot the location of the autism Facebook pages on a map, using longitude and latitude information.  640 of the 2200 pages contained longitude and latitude information.  The following map plots the global location for these pages:

![Autism Pages](/images/AutismWorldMap.png)


The top 5 English-language countries contained in the autism Facebook page dataset are listed below.  Most pages do not have a country identified (a page is identified as english-language if the 'country' field is a english speaking country, or if the text in the 'about' or 'description' fields identify the page as english-language).

Country | Number of Pages
--- | ---: 
  NA  | 708
  United States  | 349
 United Kingdon  | 98
Canada | 71
Australia | 28 




For the 349 pages identified as being located in the United States, the following table lists the top 5 states.

State  | Number of Pages
--- | ---:
CA | 34
NY | 32
TX | 26
FL  | 22
PA | 21

All Facebook pages do not contain the same amount of information.  Some pages contain frequent updates, while others are updated rarely.  Additionally, some pages are highly connected to the Facebook network, while others are not.  The “talking about” field can be used as one metric to identify pages' connection to the Facebook network.  The top 5 English-language pages, based on the ‘talking about’ count are:

Page | Talking About Count
--- | ---:
Autism Awareness | 161724
World Autism Awareness Day | 110573
Autism Speaks |  105922
Autistic Yui |  75359
National Autism Association |  65025


Using the page information, it is also possible to examine the (self-identified) Facebook categories associated with the English-language pages.  The top 5 categories are:


Category | Count
---|---:
Community | 490
Non-Profit Organization | 285
Local Business | 113
Community Organization | 37
Education | 30

In future blog posts, we will examine how the list of autism related pages changes over time.  We will also examine post frequency of individul pages, and separate active from inactive pages. 




