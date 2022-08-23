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
In the visualisation below stylistic differences of of the Brothers Grimm are visualised using the R package stylo. This has clustered text into two groups of word choices, based on text extracted from letters written to friends and colleagues. It is a comparative representation of preferred and avoided words by brothers Jacob and Wilhelm Grimm. Overlapping markers show stylistic similarity, whilst the separated text clusters imply a consistency in word choices and an individual style. Read about the methods, models and analysis in detail at: 

Gabriela Rotari, Melina Jander, Jan Rybicki, The Grimm Brothers: A stylometric network analysis, Digital Scholarship in the Humanities, Volume 36, Issue 1, April 2021, Pages 172–186, [https://doi.org/10.1093/llc/fqz088](https://doi.org/10.1093/llc/fqz088). 

{% include figure.html img="SixDegreesFrancisBacon.png" alt="Francis Bacon Network visualisation" caption="Francis Bacon Network visualisation" width="100%" %}
Image source: (Rotari et. al. 2021)

{% endcapture %} {% include card.html header="Text cluster visualisation of stylometric analysis" text=text %}

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
