---
title: Home
layout: home
---

<a class="twitter-timeline" href="https://twitter.com/joshenglert_md?ref_src=twsrc%5Etfw">Tweets by joshenglert_md</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

{% capture text %}

The Englert Lab is part of the [Division of Pulmonary, Critical Care, and Sleep Medicine](https://medicine.osu.edu/departments/internal-medicine/pulmonary) and the [Davis Heart and Lung Research Institute](https://medicine.osu.edu/departments/davis-heart-lung-research-institute) at [The Ohio State University Wexner Medical Center](https://wexnermedical.osu.edu/).  The goal of our research group is to identify the mechanisms that lead to lung injury in the intensive care unit to develop molecularly-targeted therapies for these patients.  To facilitate this precision-based medicine strategy, we employ a multidisciplinary approach that spans the fields of molecular biology, biomedical engineering, and nanomedicine. To achieve our goals we use high fidelity models of the lung microenvironment, preclinical models of critical illness, and biospecimens from clinical studies.  This translational approach.  We are known for our collaborative approach and commitment to scientific rigor and integrity.  Another key mission of the Englert Lab is to train future generations of lung scientists. 

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include featurehome.html
  image="images/projects.webp"
  link="publications"
  title="Our Research"
  text=text
%}

{% capture text %}

Learn more about our current research projects at the Englert Lab!

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include featurehome.html
  image="images/carousel/4.webp"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

The Englert Lab draws on a diverse group of undergraduates, research assistants, graduate students, and physicians. Meet the team members at the Englert Lab!

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include featurehome.html
  image="images/carousel/5.webp"
  link="team"
  title="Our Team"
  text=text
%}

