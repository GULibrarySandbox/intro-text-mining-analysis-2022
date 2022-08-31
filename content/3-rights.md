---
title: Rights
nav: true
topics: Getting ethical clearance; Licenses and access agreements; Copyright
---

# Ethics, permissions, rights and licences

{% include figure.html img="eratosthenes.jpg" alt="Eratosthenes Teaching in Alexandria" caption="'Eratosthenes Teaching in Alexandria' by Bernardo Strozzi by mark6mauno is licensed under CC BY 2.0" width="100%" %}

As a researcher you have ethical obligations toward anyone who might be affected by your research. You also have the obligation to comply with Australian copyright law. These are separate but related topics. We will deal with ethics first, then copyright and licensing.

## Ethics

{% capture text %}
Any research involving **human subjects** carries ethical obligations. 
{% endcapture %}
{% include alert.html text=text color="warning" %}

Even if you are working with publicly available datasets, it might be necessary to obtain consent from the individuals involved and ethical clearance from the university.

### But it's just text! How can it involve human subjects?

Depending on where you obtain your text data, it might contain personal information. For example, [historical archival sources](https://glam-workbench.net/) might contain information that can identify and affect people living today. Public forums like Twitter or Facebook aren't fair game just because a person has posted there. To meet your ethical obligations you may still need to obtain their informed consented to include their material your research.

According to Griffith's [Ethics Booklet on Information Technology and Online Research](https://www.griffith.edu.au/__data/assets/pdf_file/0026/354752/booklet37.pdf), whether online content analysis is viewed as 'human research' depends on:

1. the degree to which the material is 'on the public record' and;
2. whether it is contentious or likely to be of concern to the subject.

In general, the less the information could be considered 'on the public record' and the more likely the material might be contentious or of concern to the person, the more likely its inclusion would make the work 'human research'. For social media data, Griffith publishes a [flowchart](https://www.griffith.edu.au/__data/assets/pdf_file/0023/1153571/Social-Media-Flowchart-Visio-v7-200902.pdf) to help you determine your ethical obligations.

{% capture consent %}
'Informed consent' requires that the subject know exactly how the information will be published and the potential risks to them or their reputation, as a result of publishing the information. You can find sample consent forms at our [Ethical Reviews](https://www.griffith.edu.au/research/research-services/research-ethics-integrity/human/ethical-reviews) page. 

{% capture ongoing %}
**Consent may also be an ongoing process**

If you've already gained consent from your subjects and then want to do something new or different with your data, you might need to approach them for further consent.
{% endcapture %}
{% include alert.html text=ongoing color="primary" %}

{% endcapture %}
{% include card.html header="Gaining informed consent" text=consent %}

### What are my obligations?

Chapter 3.1, Element 4 of the National Statement on the [Ethical Conduct in Human Research](https://www.nhmrc.gov.au/about-us/publications/national-statement-ethical-conduct-human-research-2007-updated-2018) describes the ethical standards relating to the collection, use and management of data in human research.

Griffith publishes a [Guide for Managing Your Research Data](https://www.griffith.edu.au/__data/assets/pdf_file/0025/1233907/20210107-Guide-to-managing-research-data.pdf) that outlines the considerations involved in preparing a Data Management Plan. Having this information ready will help you to explain your research to your participants.

{% capture text %}
If you're unsure about your ethical obligations, contact [Griffith research ethics](https://www.griffith.edu.au/research/research-services/research-ethics-integrity).
{% endcapture %}
{% include alert.html text=text color="info" %} 

{% capture deidentify %}
Unless the participants have given their informed consent to being identified, you will need to remove personally identifying data from your data set before publishing it. This applies to all personal information, not just data which is sensitive or confidential.

Where a social media service has a search function, using direct quotes can identify individuals.

{% capture reidentification %}
**Beware of re-identification**

If de-identification is done carelessly, or there are many data points in a data set that are unique to an individual, the data can be re-identified. In 2017, University of Melbourne researchers were able to [re-identify published Medicare data](https://www.unimelb.edu.au/newsroom/news/2017/december/research-reveals-de-identified-patient-data-can-be-re-identified), leading to its swift retraction.

{% endcapture %}
{% include alert.html text=reidentification color="danger" %}

{% endcapture %}

<!--- Begin header with icon code --->
{% capture headertext %}
{% include icon.html icon='clipboard2-x-fill' %} De-identifying data
{% endcapture %}
<!--- End header with icon code --->

{% include card.html header=headertext text=deidentify %}

{% capture text %}
If you're unsure about your ethical obligations, contact [Griffith research ethics](https://www.griffith.edu.au/research/research-services/research-ethics-integrity).
{% endcapture %}
{% include alert.html text=text color="info" %}

----

## Copyright

Both copyright law and any relevant licensing terms will affect what you can do with scraped data.

{% capture copyrightwarning %}
Accessing and downloading data is one thing — publishing it is another. Obtaining permission to do one does not mean you have permission to do the other.  Make sure your permission covers all your intended activities.  Contact the Information Policy Officer for assistance.
{% endcapture %}
{% include alert.html text=copyrightwarning color="warning" %}

Copyright law prevents you from publishing data sets owned by someone else without permission or an appropriate licence. This also generally applies if you intend to alter or mix data owned by someone else, since your altered dataset will generally contain a “substantial amount” of the original data.  However, this does not always apply with text or data mining as the data outputs may not be “substantially” similar to the data they mine.  

{% capture checkwithcopyrightofficer %}
If you are intending to text or data mine, always check with the [Information Policy Officer](http://www.griffith.edu.au/copyright-matters/) first.
{% endcapture %}
{% include alert.html text=checkwithcopyrightofficer color="info" %}

### Using social media data

Social media datasets generally contain copyrighted material (such as comments, images, videos) whose copyright belongs to individuals and not to the Social Media platform (although tweets are generally not considered long enough to attract copyright protection).   Before using such data for your research, you should check the site’s Terms and Conditions and policies.  These will mostly determine what you are allowed to do with the site’s data (including whether scraping or bulk-access is allowed).

Many sites allow research or non-commercial scraping or API use.  Contact the [Information Policy Officer](http://www.griffith.edu.au/copyright-matters/)  for assistance.

### Gaining access and permission

{% capture publicdomain %}
Some data is in the public domain (meaning nobody owns the copyright), or is licensed under free or public licenses like [Creative Commons](https://creativecommons.org.au) or [Copyleft](https://opensource.com/resources/what-is-copyleft). Creative Commons is not the same as being copyright-free. It is still a kind of license that you need to comply with. The main difference is that you don’t have to ask permission to use the material. Permission is granted by the owner in advance, provided that you conform to the licence terms. It’s possible for some Creative Commons licenses include a ‘No Derivatives’ term, which would prevent you from publishing a new dataset based on the original.

See Griffith's [Library Guide on Text mining and analysis](https://libraryguides.griffith.edu.au/text-mining/open) for a list of open access sources.

{% capture stillethics %}
**Copyright-free does not mean ethics-free** 

Data that is freely licensed still carries ethical considerations! If your corpus contains information about people then you may still hold ethical obligations to them.
{% endcapture %}
{% include alert.html text=stillethics color="warning" %}

{% endcapture %}

<!--- Begin header with icon code --->
{% capture headertext %}
{% include icon.html icon='badge-cc' %} Public domain and Creative Commons
{% endcapture %}
<!--- End header with icon code --->
{% include card.html header=headertext text=publicdomain %}

{% capture permissionsblock %}

To get permission, firstly find the copyright owner and their contact email address.   Then send an email adapting one of the [permission template emails](https://www.griffith.edu.au/copyright-matters/hdr-candidates/getting-permission).  Make sure your permission covers all your intended activities.  Store the received permission so that it can be readily retrieved if ever required. As always, contact the [Information Policy Officer](http://www.griffith.edu.au/copyright-matters/)  for assistance.

{% endcapture %}
{% include card.html header="Getting permission" text=permissionsblock %}

{% capture licensedsources %}

Griffith's licensing arrangements with several publishers allow for text and data mining by Griffith University researchers. See the [Text Mining Library Guide](https://libraryguides.griffith.edu.au/text-mining/licenced) for a list of licensed sources.

<!--- Begin header with icon code --->
{% capture headertext %}
{% include icon.html icon='cloud-download' %} Griffith licensed sources
{% endcapture %}
<!--- End header with icon code --->

{% endcapture %}
{% include card.html header=headertext text=licensedsources %}

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/2-how.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/4-build.html">NEXT --></a>
</p>
