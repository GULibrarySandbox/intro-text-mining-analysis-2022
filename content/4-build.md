---
title: Build
topics: Building a dataset; Finding data; 
nav: true
---

# Building a dataset

A dataset can be built either through finding and extracting existing data, collating resources or generating your own data. Building a dataset can be as simple as collecting PDFs from your literature search, or as complex as finding then transribing handwritten texts and converting them into a computational format.  

The first step is to find the dataset or corpus of interest.

## Finding data

{% include figure.html img="GLAMCollections.PNG" alt="Find data in GLAM collections" caption="Find data in GLAM collections" width="100%" %}

Digitisation, Optical Character Recognition (OCR) processing, indexing, encoding, and online hosting of primary source materials by archives, libraries, museums and galleries (GLAM sector)  has enabled greater access, and new ways to find, explore, process and analyse text as data.  An easy way to get started in finding discipline specific data sets is in the Griffith guides
- <a href ='https://libraryguides.griffith.edu.au/finddata' target="_blank">Finding data guide </a>  
- [Text mining and analysis guide](https://libraryguides.griffith.edu.au/text-mining) : of Griffith Library subscription and open source databases

Explore the amazing data that can be extracted from our GLAM catalogues with [Ass. Prof. Tim Sherratt](https://timsherratt.org/) historian and hacker, via the video below.
<iframe width="853" height="480" src="https://www.youtube.com/embed/spvb-zBe24o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

If you cannot get the data you need from the guides above make an enquiry with the platform of interest. Companies may make their data available to researchers by agreement such as [Twitter's Academic Research access service](https://developer.twitter.com/en/products/twitter-api/academic-research). Archives and other repositories will have links to the datasets that can be downloaded, as will some Government websites.  

## Extracting data

### Searching and downloading

Search GLAM catalogues and download individual resources or sets of results as required. This is useful if searching for small quantities of text and catalogue websites provide useful search and download help for users. 

When downloading resources, select text `.txt` file format which has all formatting removed and is readible by computers. 

If this isn't possible choose `.pdf` format which is accepted by some analysis programs or can be read by Optical Character Recognition (OCR), then useable in analysis programs. 

Watch the video below to learn how to search then download newspaper articles from TROVE.
<iframe width="853" height="480" src="https://www.youtube.com/embed/RZyq_QMO7YY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[TROVE text download options](https://trove.nla.gov.au/help/using-trove/downloading) provides `.txt` and `.pdf` format download instructions for different types of resources.

### Using an API to extract data

An Application Programming Interface (API) is a software tool that allows two applications to communicate with each other. In the case of collecting web data, an API is a database that stores the webpages data and something that can read, display or store that data (i.e. a web browser, a programming language such as Python, software on your computer, or a cloud based application).

<iframe width="853" height="480" src="https://www.youtube.com/embed/s7wmiS2mSXY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Using a supplied API is the easiest way to collect metadata sets (data about the text, e.g. a literature database records) or a large dataset of text from a database or website. Examples of API's useful to text analysis researchers include:
- [TROVE API](https://trove.nla.gov.au/about/create-something/using-api)
- [Assoc Prof Tim Sherrat's Australian GLAM data & API list](https://glam-workbench.net/glam-data-list/)
- [State Library of Queensland's open datasets API](https://www.slq.qld.gov.au/get-involved/open-data/open-datasets-released-state-library)
- [QLD Open Data Portal API](https://www.data.qld.gov.au/article/standards-and-guidance/publishing-guides-standards/api-user-guide)
- [Twitter's Academic Research Access API](https://developer.twitter.com/en/products/twitter-api/academic-research)
- [JSTOR API for texting mining](https://about-jstor-org.libraryproxy.griffith.edu.au/whats-in-jstor/text-mining-support/)


{% capture text %}
The Prosecution Project is a collaborative research project on the history of the criminal trial in Australia from 1788 to 1960. Sources of text data included Supreme Court crimial trial registers, Police Gazettes notices, Prison and Convict Registers, along with press releases and other newspaper articles  [https://prosecutionproject.griffith.edu.au/](https://prosecutionproject.griffith.edu.au/).

The images below include example source materials like those used by the Prosecution Project:
- Libraries Tasmania Digital Image ID AB693-1-1 1853-1854: Registers of Criminal Cases Prosecuted by the Crown (AB693), 1853-1984. retrieved May 10, 2021, from [https://stors.tas.gov.au/AB693-1-1$init=AB693-1-1_039](https://stors.tas.gov.au/AB693-1-1$init=AB693-1-1_039) 
- (1907, January 16). The Advertiser (Adelaide, SA : 1889 - 1931), p. 1. Retrieved May 10, 2021, from [http://nla.gov.au/nla.news-page930175](http://nla.gov.au/nla.news-page930175)
- Queensland State Archives Digital Image ID 23435: Queensland Police Gazette – Vol LXI, No 66, pp 653-654, 6 December 1924 
[https://blogs.archives.qld.gov.au/2014/08/17/catching-criminals-in-queensland-state-archives-collection/](https://blogs.archives.qld.gov.au/2014/08/17/catching-criminals-in-queensland-state-archives-collection/)

{% include figure.html img="2021_ProsProjSources.png" alt="Sources of text for the Prosecution Project" caption="Sources of text for the Prosecution Project" width="100%" %}{% endcapture %} {% include card.html header="Case study - the Prosecution Project - finding sources" text=text %}

----

{% include alert.html text="*Note:* Be sure to cite any resources you use in your research." color="warning" %}


----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/3-rights.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/5-prepare-text.html">NEXT --></a>
</p>
