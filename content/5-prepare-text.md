---
title: Prepare text
topics: Prepare and format; Useful tools; Cleaning text
nav: true
---

# Prepare and format

Preparing and formating your data makes it consistent and machine readable for analysis. This process differs depending on the types and formats of files you are working with.  
{% include figure.html img="Textformats1.jpg" alt="Text as data formats, Speech to text, Handwritten text, Printed text, Digital text" caption="Different text as data formats that need processing" width="100%" %}
## Preparation steps

There can be a number of steps to prepare, clean, then format text data depending on its type.  

Interview data may be in audio or video format and require transcription. Correspondence may be handwritten on paper or in a digital format as a scanned image. 

Let's explore the different formats and preparation steps below.

### Types of text data

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| survey audio recordings | personal letters | books, journals, news articles, legislation, government reports | online databases & digital collections of published or primary sources...
| interview audio or video recordings | official correspondence | unpublished papers | unpublished works, your own digital documents
| observation video recordings | ships logs, diaries, ledgers | typed documents, letters, official records, recipes.... | webpage and social media content |
| | original manuscripts & drafts | brochures, menus, other primary source materials | language corpora |
| | scientific notes, annotations, field books | survey results | interview transcripts, survey results |
{:.table .table-bordered}

### How to prepare text data

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| transcribe the audio content | transcribe manually or via an automated processes | transcribe or digitise via a scanner then process into text via Optical Character Recognition (OCR) | reformat files to .txt |
{:.table .table-bordered}

### Tools to prepare text data


{% capture text %}
- Nvivo software [student access](https://www.griffith.edu.au/student-computing/available-software)  [staff access](https://intranet.secure.griffith.edu.au/computing/software) 
Watch this video for an overview on the Nvivo transcription feature.

{% include video-embed.html youtubeid="AES26-CdEn0" caption="Nvivo transcription demonstration video" %}

- [Microsoft Office 365](https://support.microsoft.com/en-us/office/transcribe-your-recordings-7fc2efec-245e-45f0-b053-2a97531ecf57)
- [Griffith's Speech to text service](https://www.griffith.edu.au/eresearch-services/speech-to-text) note this service has assoicate charges.
- [Alveo](https://www.alveo.edu.au/) : Developed in Australia for researchers.  The software breaks up audio into segments by identifying breathing pauses and provides a structured format for manual transcription.  Griffith Education researchers have found it can reduce manual transcription time by up to 50%.

Watch the video below for instructions on how to use Alveo.

{% include video-embed.html youtubeid="ixQR-c4R0Ss" caption="Alveo transcription demonstration video" %}

{% endcapture %}{% include card.html header="Speech to text - transcription tools" text=text %}

{% capture text %}
- [Transkribus](https://readcoop.eu/transkribus/) 
The video below shows how to download and use [Transkribus](https://readcoop.eu/transkribus/) handwriting recognition tool.

{% include video-embed.html youtubeid="uNlC2Nboow8" caption="Transkribus handwriting transcription video" %}

- [Google Vision AI](https://cloud.google.com/vision)
- MSWord, google docs or equivalent : for manual transcription without structure or metadata capture.{% endcapture %}{% include card.html header="Handwritten text - transcription tools" text=text %}

{% capture text %}
- High quality scanner with OCR functionality (or OCR processing after scanning) 
- [Digital Camera](https://how-ocr-works.com/accuracy/snapshots.html)(followed by OCR processing) 
{% endcapture %}{% include card.html header="Printed text - digitisation tools" text=text %}

{% capture text %}
- [gImageReader](https://github.com/manisandro/gImageReader#readme) (students) open source OCR processor for pdfs and images of text.
Watch this video on how to install and use [gImageReader](https://github.com/manisandro/gImageReader#readme) to convert an image to text. In this example both Korean and English language in a pdf file are tested for conversion to text. 

{% include video-embed.html youtubeid="GMAZtpWQF0U" caption="gImageReader OCR conversion video" %}

- [Adobe Acrobat Pro DC](https://intranet.secure.griffith.edu.au/computing/software) (staff) OCR recognition
- [OpenRefine](https://openrefine.org/) to create structure to text
- [DigiVol](https://volunteer.ala.org.au/) for structured text 
- Google Docs can perform OCR on uploaded images and PDFs 
{% endcapture %}{% include card.html header="Digital documents - text recognition and conversion tools" text=text %}


### How to clean text after transcription and conversion

No preparation tool, including those above will create *perfect* text. 

Errors will be generated in the transcription or conversion processes. You may need to manually review and clean the text, correcting OCR (Optical character recognition) of scanned images of pages, mis-interpretation of spoken words, and other transcription errors. 

Programs such as Python can automate some cleaning processes. Read about this at [machinelearningmastery.com](https://machinelearningmastery.com/clean-text-machine-learning-python/). Some analysis programs such as Voyant tools will also clean text. More on this in the next lesson. 

### Unstructured vs structured text and machine readibility

Humans understand that language, and the text that represents it, is highly complex and full of structure. However text is often described as unstructured, when it does not fit easily into a database, or is not easily processed by a computer. In the context of processing text with a computer:

- Unstructured text may include text from narratives (books, articles etc.), interviews, survey responses with free text and more.  
- Structured text can include metadata from GLAM catalogues or finding aides, text in structured databases, possibly spreadsheets, even old ledgers and logbooks. 

### Formating structured and unstructured text

All text documents need to be formatted for machine readability by software programs or code, let's look at the different formats for structured and unstructured text.
- `.txt` : is the best format for unstructured text as it is non-proprietary & used in all text analysis tools. Unstructured text in file formats such as `.doc` , `.docx`, `.rtf` (rich text format) can be exported as `.txt` via Microsoft Word.
- `.csv` : is the best format for structured text data in spreadsheets and can be read by tools such as Nvivo. Use Microsoft Excel to convert file formats such as `.xml`, `JSON`, `.html` into `.csv.` or `.txt` delimited text file, in which a `tab` separates each field of text.
- `.pdf` : that has been OCR processed is accepted by some analysis tools. For older texts you might need to transcribe the text or clean the data as the .pdf may be an image of a scanned document.

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
