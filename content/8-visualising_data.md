---
title: Visualise
topics: Requirements; Types of visualisations; 
nav: true
---
# Visualisation methods and tools

Visualising data can help us understand complex information quickly. Transforming data into a visual format can:

- reveal patterns and relationships
- identify trends
- communicate insights with impact

## Visualisation methods

The type of visualisations you can create are governed by the types of data you are working with. 

[Data to Viz](https://www.data-to-viz.com/) will help you find the most appropriate graph for your data.  

The visualisation types explained in Data to Viz are particularly useful to illustrate the analysis results of structured text, including metadata records and categorical data. When text is processed and broken down into its various parts then analysed using quantitative, statistical, temporal, spatial, or other distant reading methods the numerical results can also be visualised using the examples in Data to Viz.

The Data to Viz team also provide a collection of useful tips and caveats for using visualisations [here](https://www.data-to-viz.com/caveats.html).

{% capture alert %}
*A warning on using visualisation methods with text*:

Visualisation methods and tools are useful for “preliminary analysis and hypothesis adjustment” and early data exploration. Always check results “against traditional content analysis techniques which are more sensitive to the complex structure" of language. 

Quantitative analysis of textual data is a reductive process where the “coherent system of meaning units” is broken down. Take care not to read suppositions into visualisations that are not a real reflection of the data, its meaning and relationships. (Gabor, H. et. al., 2019)
{% endcapture %}{% include alert.html text=alert color="warning" %}

## Text visualisation examples

Below is a showcase of text analysis visualisations in recent peer reviewed articles.

{% capture text %}
In the visualisation below, stylistic differences of the Brothers Grimm are visualised using the R package [Stylo](https://cran.r-project.org/web/packages/stylo/index.html). This has clustered text into two groups of word choices, based on text extracted from letters written to friends and colleagues. It is a comparative representation of preferred and avoided words by brothers Jacob and Wilhelm Grimm. Overlapping markers show stylistic similarity, whilst the separated text clusters imply a consistency in word choices and an individual style. Read about the methods, models and analysis in detail at: 

Gabriela Rotari, Melina Jander, Jan Rybicki, The Grimm Brothers: A stylometric network analysis, Digital Scholarship in the Humanities, Volume 36, Issue 1, April 2021, Pages 172–186, [https://doi.org/10.1093/llc/fqz088](https://doi.org/10.1093/llc/fqz088). 

{% include figure.html img="GrimmBrothersStylometricVis.PNG" alt="Grimm Brothers letters - stylometric differences" caption="Grimm Brothers letters - stylometric differences" width="100%" %}
Image source: (Rotari et al., 2021)
{% endcapture %} {% include card.html header="Text cluster visualisation of stylometric analysis" text=text %}

{% capture text %}
Named entity recognition of occupations followed by frequency analysis of different professions featured in movies and televison shows was undertaken using data from the [OpenSubtitles.org](https://www.opensubtitles.org/en/search/subs) database. The line graphs below show the movie and TV frequency trends of some professions from 1950s to 2020s.  Take a deeper dive into the methods and analysis, including sentiment analysis of the professions in media, in the full article: 

Baruah, S., Somandepalli, K., & Narayanan, S. (2022). Representation of professions in entertainment media: Insights into frequency and sentiment trends through computational text analysis. PloS one, 17(5), e0267812. [https://doi.org/10.1371/journal.pone.0267812](https://doi.org/10.1371/journal.pone.0267812)
{% include figure.html img="ProfessionsMediaFrequency.PNG" alt="Frequency trends of professions featured in movies and TV 1950-2020 image" caption="Frequency trends of professions featured in movies and TV 1950-2020" width="100%" %}
Image source: (Baruah, S. et al., 2022)
{% endcapture %} {% include card.html header="Frequency trends visualised in line charts" text=text %}

{% capture text %}
In this study Voyant tools and [NodeXL software](https://www.smrfoundation.org/nodexl/) were used to mine, extract and collocate words which enabled qualitative coding of seven major themes from over 1000 individual public submissions that supported or opposed voluntary assisted dying in a Queensland Parliamentary Inquiry 2018.

Explore the analysis and methods further in the article:  
Kirchhoffer, D. G., & Lui, C. W. (2021). Public reasoning about voluntary assisted dying: An analysis of submissions to the Queensland Parliament, Australia. Bioethics, 35(1), 105-116. https://doi.org/10.1111/bioe.12777 

{% include figure.html img="BioethicsAssistedDyingTextAnalysisVis.PNG" alt="Public reasoning about voluntary assisted dying - network visualisation of major themes" caption="Public reasoning about voluntary assisted dying - network visualisation of major themes" width="100%" %}
Image source: (Kirchhoffer & Lu, 2021)

{% endcapture %} {% include card.html header="Network analysis of major themes found in public submission documents" text=text %}

{% capture text %}
{% endcapture %} {% include card.html header="Activity - ..." text=text %}

## Visualisation tools

Many of the text analysis tools listed on the previous page can create visualisations of the data. Check out the Voyant tools [activity](https://griffithunilibrary.github.io/data-vis-basics/content/5-voyant.html) to explore a series of articles from The Conversation as an example.

In addition to these analysis tools, the following can be used to create visualisations for structured, categorical data or tabular data: 
- MS Excel and other spread sheet programs
- [RawGraphs](https://rawgraphs.io/ ) open source program (free) developed at the Density Design Research Lab of the Politecnico di Milano
- computational code such as R & Python.





{% include button.html text="" color="info" %}

## Create a publication quality image of your visualisation

-----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/6-analyse.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/8-help.html">NEXT --></a>
</p>
