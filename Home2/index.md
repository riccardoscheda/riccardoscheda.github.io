---
title: Home2
nav:
  order: 6
  tooltip: Old version of the Home
---

# Artificial Intelligence and Neuroimaging for Health

Welcome to the AI for Medicine Research Group! We are a team of researchers dedicated to advancing the field of precision medicine through the use of artificial intelligence. At the heart of our work is a commitment to open science and collaboration. We believe in sharing all of our source code to accelerate research in this field, and we're excited to work with others who share our passion for using AI to improve patient outcomes.

{:.center}
{%
  include link.html
  type="github"
  icon=""
  text="See our Lab on GitHub"
  link="riccardoscheda/riccardoscheda"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/campus.jpeg" %}

{% include section.html %}

# Highlights

{% capture text %}
Our research mainly focuses in Neurological Disorders, such as Dementia, Autism and Schizophrenia. 

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/campus.jpeg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
We developed tools for Slice-level Data-leakage, and other methods.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/slice-level-data-leakage.png"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
See our team
{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/ingeingresso.jpg"
  link="team"
  title="Our Team"
  text=text
%}

{% include twitter.html %}

{% include section.html full=true %}
{% include banner.html image="images/AIphrase2.png" %}
