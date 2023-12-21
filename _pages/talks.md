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
    <img src='../images/HanYongWunrow.jpg' style='width:200px;'>
</figure>

## [Han Yong Wunrow](https://hwunrow.github.io/)
### Doctoral Student
Han Yong Wunrow began his PhD in Applied Mathematics in the fall of 2021. He received an MS in Applied Mathematics from the University of Washington and was a Post-Bachelor Fellow at the Institute for Health Metrics and Evaluation, where he worked on the Global Burden of Disease study and the Future Health Scenarios forecasting team. He is interested in the science of transforming raw health data into actionable information through mathematical modeling and computational science. While at Columbia, he hopes to help solve some of the analytical challenges in combining statistical and mechanistic models of infectious disease dynamics.

<figure style="float: left; margin: 0 20px -10px 0;">
    <img src='../images/MichalHajlasz.png' style='width:200px;'>
</figure>

## [Michal Hajlasz](https://www.linkedin.com/in/micha%C5%82-haj%C5%82asz-9ba5a8224)
### Research Assistant
Michal is a senior at Columbia hailing from Pittsburgh, PA. He is studying computer science with a concentration in math. He is interested in learning more about machine learning, mathematical modelling, and theoretical computer science. In his free time, you will find Michal walking, skating, and listening to music. Michal is working on predictability of human mobility.


{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
