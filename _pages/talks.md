---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

<figure style="float: left; margin: 0 20px -10px 0;">
    <img src='../images/me.jpg' style='width:200px;'>
</figure>

## Sen Pei
Dr. Sen Pei is an [Assistant Professor](https://www.publichealth.columbia.edu/profile/sen-pei) in the Department of Environmental Health Sciences at Mailman School of Public Health, Columbia University. With a background in applied mathematics, network science, and complex systems, he studies environmental, social, and ecological determinants of infectious disease, aiming
to better understand, predict, and prepare for recurrent and emerging outbreaks. Using a variety of data sources, he develops mathematical models and computational tools to advance surveillance, forecasting, and control of seasonal and emerging infectious agents. His recent studies focus on respiratory viruses and antimicrobial-resistant pathogens in healthcare systems.

<figure style="float: left; margin: 0 20px -10px 0;">
    <img src='../images/QingYao.jpg' style='width:200px;'>
</figure>

## [Qing Yao](https://qing1101.com/)
### Postdoctoral Research Scientist
Dr. Qing Yao is a postdoctoral research scientist with a focus on the theories and application of complexity and network science. She is currently working on modeling infectious diseases spread and understanding the impact of human behaviour on this phenomenon. Prior to her current position, Qing conducted research at Beijing Normal University and Imperial College London. She holds a PhD in physics and a Master's degree in financial statistics.

<figure style="float: left; margin: 0 20px -10px 0;">
    <img src='../images/ToryLynch.jpg' style='width:200px;'>
</figure>

## [Victoria Lynch](https://scholar.google.com/citations?user=4b-RO54AAAAJ&hl=en)
### Postdoctoral Research Fellow
Victoria Lynch is a postdoctoral scientist in the Environmental Health Sciences Department at Columbia Mailman School of Public Health, where she also completed her PhD in August 2022. Her doctoral work examined the association between flooding and waterborne infectious diseases with a particular focus on Legionnaires' disease. As a postdoctoral research fellow, she continues to study the effect of extreme events, namely cyclonic storms and large flood events, on a broader range of health outcomes and among vulnerable populations including outdoor workers and people in carceral facilities.


<figure style="float: left; margin: 0 20px -10px 0;">
    <img src='../images/HanYongWunrow.jpg' style='width:200px;'>
</figure>

## [Han Yong Wunrow](https://hwunrow.github.io/)
### Doctoral Student
Han Yong Wunrow began his PhD in Applied Mathematics in the fall of 2021. He received an MS in Applied Mathematics from the University of Washington and was a Post-Bachelor Fellow at the Institute for Health Metrics and Evaluation, where he worked on the Global Burden of Disease study and the Future Health Scenarios forecasting team. He is interested in the science of transforming raw health data into actionable information through mathematical modeling and computational science. While at Columbia, he hopes to help solve some of the analytical challenges in combining statistical and mechanistic models of infectious disease dynamics.

<figure style="float: left; margin: 0 20px -10px 0;">
    <img src='../images/ChristineKuryla.jpeg' style='width:200px;'>
</figure>

## [Christine Kuryla](https://www.researchgate.net/profile/Christine-Kuryla-2)
### Doctoral Student
Christine Kuryla is working on her PhD in the department of Environmental Health Sciences. She holds an MPH from Columbia University, a Pre-medical Post-bac from Johns Hopkins, and a B.S. In Physics with a concentration in Mathematics from FIU. She is interested in using various types of data, including physiological time series, as well as omics, to characterize health states and quantify intrinsic health. 

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
