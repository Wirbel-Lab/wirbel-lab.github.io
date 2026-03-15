---
title: Software
nav:
  order: 4
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Software

{% capture text %}

The SIAMCAT package is an R package for comparative metagenomics analysis. It is a one-stop toolbox for data filtering, association testing, construction of machine learning workflows, and data visualization.

Check out the [associated publication](https://doi.org/10.1186/s13059-021-02306-1) describing the tool.

The SIAMCAT package was originally developed in the [Zeller lab](https://zellerlab.github.io).

{% endcapture %}

{%
  include feature.html
  image="images/siamcat.png"
  link="https://github.com/zellerlab/siamcat"
  title="SIAMCAT"
  text=text
%}


{% capture text %}

The microbiome workflows are implemented in Nextflow and offer a wide range of standard microbiome analyses approaches. They include workflows for raw data preprocessing, taxonomic profiling, assembly, binning, and prediction of phages. Most workflows are implemented to work with both short- and long-read input data.

The microbiome workflows are maintained by the [Bhatt lab](https://bhattlab.com/) and the Wirbel lab.

{% endcapture %}

{%
  include feature.html
  image="images/metro_map.png"
  link="https://github.com/wirbel-lab/microbiome_workflows"
  title="Microbiome Workflows"
  text=text
  flip=true
%}
