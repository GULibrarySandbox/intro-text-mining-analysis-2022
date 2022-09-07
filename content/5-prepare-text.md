---
title: Prepare text
topics: Prepare and format; Useful tools; Cleaning text
nav: true
---

# Prepare and format

Preparing and formating your data makes it consistent and machine readable for analysis. This process differs depending on the types and formats of files you are working with. For full functional analysis your corpus documents will need to all be in the same format. This section will show the processes and tools available to help create your analysable corpus. 
{% include figure.html img="Textformats1.jpg" alt="Text as data formats, Speech to text, Handwritten text, Printed text, Digital text" caption="Different text as data formats that need processing" width="100%" %}
## Preparation steps

There can be a number of steps to prepare, clean, then format text data depending on its type.  

Interview data may be in audio or video format and require transcription. Correspondence may be handwritten on paper or in a digital format as a scanned image. 

Let's explore the different formats and preparation steps below.

{% capture text %}
*Speech to text* : this type of data can include audio or video recordings of surveys, focus groups, interviews, or observation videos.

*Handwritten text* : can include personal letters, official correspondence, ships logs, diaries, ledgers, orginal manuscripts and drafts, scientific notes, annotations, field books, recipes, survey responses .

*Printed (or typed) text* : includes typed versions of the handwritten text above, or books, journals, news articles, legislations, government reports, unpublished papers, official records, brochures, menus, and other primary source materials.

*Digital text* : includes digital versions of printed text, or content in databases, digitised collections of published or primary sources, unpublished works, your own digital documents, webpage and social media content, language corpora, interview transcripts and survey results.{% endcapture %}{% include card.html header="Types of text data" text=text %}

{% capture text %}
*Speech to text* : manually transcribe or autogenerate the audio content and convert to .txt file format.

*Handwritten text* : transcribe manually or via an automated processes and convert to .txt file format.

*Printed text* : transcribe or digitise via a scanner then process into text via Optical Character Recognition (OCR).

*Digital text* : extract from databases, files, websites and reformat files to .txt file format if required.{% endcapture %}{% include card.html header="How to prepare text data" text=text %}


### Tools to prepare text data

{% capture text %}
These tools are featured on the next page which focuses on AV preparation.
{% endcapture %}{% include card.html header="Speech to text - transcription tools" text=text %}

{% capture text %}
- [Transkribus](https://readcoop.eu/transkribus/) handwriting recognition tool. Free to use for manual transcription and 500 credits provided to use AI models for automated transcription of different types of handwriting. Research candidates can apply for further credits.

The video below shows how to download and use [Transkribus](https://readcoop.eu/transkribus/).

{% include video-embed.html youtubeid="uNlC2Nboow8" caption="Transkribus handwriting transcription video" %}

- [Google Vision AI](https://cloud.google.com/vision)
- MSWord, google docs or equivalent : for manual transcription without structure or metadata capture.{% endcapture %}{% include card.html header="Handwritten text - transcription tools" text=text %}

{% capture text %}
- High quality scanner with OCR functionality (or OCR processing after scanning).
- [Digital Camera](https://how-ocr-works.com/accuracy/snapshots.html), followed by OCR processing.
{% endcapture %}{% include card.html header="Printed text - digitisation tools" text=text %}

{% capture text %}
- [gImageReader](https://github.com/manisandro/gImageReader#readme) (students) open source OCR processor for pdfs and images of text.

Watch this video on how to install and use [gImageReader](https://github.com/manisandro/gImageReader#readme) to convert an image to text. In this example both Korean and English language in a pdf file are tested for conversion to text. 

{% include video-embed.html youtubeid="GMAZtpWQF0U" caption="gImageReader OCR conversion video" %}

- [Adobe Acrobat Pro DC](https://intranet.secure.griffith.edu.au/computing/software) (staff) OCR recognition.
- [OpenRefine](https://openrefine.org/) to create structure from text.  Explore how to use OpenRefine with unstructured text in this Programming Historian [tutorial](https://programminghistorian.org/en/lessons/fetch-and-parse-data-with-openrefine).
- [DigiVol](https://volunteer.ala.org.au/) for structured text.
- Google Docs can perform OCR on uploaded images and PDFs.
{% endcapture %}{% include card.html header="Digital documents - text recognition and conversion tools" text=text %}

{% capture text %}
No preparation tool, including those above will create *perfect* text. 

Errors will be generated in the transcription or conversion processes. You may need to manually review and clean the text, correcting OCR (Optical character recognition) of scanned images of pages, mis-interpretation of spoken words, and other transcription errors. 

Programs such as Python can automate some cleaning processes. Read about this at [machinelearningmastery.com](https://machinelearningmastery.com/clean-text-machine-learning-python/). Some analysis programs such as Voyant tools will also clean text. More on this in the next lesson. 
{% endcapture %}{% include card.html header="How to clean text after transcription or conversion" text=text %}

{% include alert.html text="**Unstructured vs structured text and machine readibility**

Humans understand that language, and the text that represents it, is highly complex and full of structure. However text is often described as unstructured, when it does not fit easily into a database, or is not easily processed by a computer. In the context of processing text with a computer:

- Unstructured text may include text from narratives (books, articles etc.), interviews, survey responses with free text and more.  
- Structured text can include metadata from GLAM catalogues or finding aides, text in structured databases, possibly spreadsheets, even old ledgers and logbooks." align="left" color="success" %}


{% capture text %}
All text documents, structured and unstructured, need to be formatted for machine readability by software programs or code. Let's look at the different formats.
- `.txt` : is the best format for unstructured text as it is non-proprietary & used in all text analysis tools. Unstructured text in file formats such as `.doc` , `.docx`, `.rtf` (rich text format) can be exported as `.txt` via Microsoft Word.
- `.csv` : is the best format for structured text data in spreadsheets and can be read by tools such as Nvivo. Use Microsoft Excel to convert file formats such as `.xml`, `JSON`, `.html` into `.csv.` or `.txt` delimited text file, in which a `tab` separates each field of text.
- `.pdf` : that has been OCR processed is accepted by some analysis tools. For older texts you might need to transcribe the text or clean the data as the .pdf may be an image of a scanned document.
{% endcapture %}{% include card.html header="Formatting structured and unstructured text" text=text %}
------

{% capture text %}
Prosecution Project researchers worked with a team of eResearch specialists and database and web designers to develop a structured database managed through a secure web portal. With the support of volunteers, they undertook massive digitisation, transcription and indexing work resulting in a longitudinal database of criminal prosecutions never before available in Australia. They also recognized the potential of enriching the data via links to the sources used such as newspaper articles in National Library of Australia TROVE database.  

Read more about the project at: 
Finnane, M., & Piper, A. (2016). The Prosecution Project: Understanding the Changing Criminal Trial Through Digital Tools. Law and History Review, 34(4), 873-891. [doi:10.1017/S0738248016000316](doi:10.1017/S0738248016000316)
{% endcapture %} {% include card.html header="Case study - the Prosecution Project - digitising, transcribing, building" text=text %}

{% include figure.html img="ProsectionProject_image_1.png" alt="Prosecution Project database" caption="Prosecution Project database" width="100%" %}

-----

Next up: transcribing and annotating audio and video.

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/4-build.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/6-prepare-av.html">NEXT --></a>
</p>
