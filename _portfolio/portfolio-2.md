---
title: "Real-time Response to the COVID-19 Pandemic"
excerpt: "Understanding transmission dynamics of SARS-CoV-2<br/><img src='/images/COVID.png' style='width:500px;'>"
collection: portfolio
---

<figure style="float: left;">
    <img src='/images/COVID.png' style='width:100%;'>
</figure>

The COVID-19 pandemic provided an urgent demonstration of the need for real-time, data-driven epidemic modeling. In response to the emergence of SARS-CoV-2, our group developed and applied mathematical models to address critical questions about transmission, under-ascertainment, spatial spread, intervention effects, disease burden, and community transmission.

Early in the pandemic, we used mobility data, surveillance observations, and networked metapopulation models to estimate the extent and impact of undocumented SARS-CoV-2 infections. We also developed one of the first county-level projection systems for the United States, supporting real-time situational awareness during the initial phase of the pandemic. These studies highlighted the role of cryptic transmission, rapid geographic spread, and the importance of timely interventions.

Our later COVID-19 work examined disease burden in the United States, the effects of non-pharmaceutical interventions, contact tracing and community transmission in New York City, and the interaction between human mobility, vaccination, and spatial transmission. Together, this body of work provides a foundation for our broader research program in pandemic preparedness and data-driven modeling of emerging infectious diseases.

## Projecting COVID-19 spread in the United States

We developed one of the first [COVID-19 projections](https://www.medrxiv.org/content/10.1101/2020.05.15.20103655v2) for 3142 US counties in March 2020. From March 2020 to March 2023, we produced real-time COVID-19 forecasts for US counties updated weekly. These forecasts were made available to the public and were submitted to the CDC COVID-19 forecast hub. Our early simulation of COVID-19 spread in the US was covered by the New York Times ["Coronavirus Could Overwhelm U.S. Without Urgent Action, Estimates Say"](https://www.nytimes.com/interactive/2020/03/20/us/coronavirus-model-us-outbreak.html), which was featured on the front page of the New York Times on March 21, 2020.

<figure style="float: left;">
    <img src='/images/earlysimulation.png' style='width:100%;'>
</figure>

## Undocumented infection fuels rapid spread of SARS-CoV-2 in China

Estimation of the prevalence and contagiousness of undocumented novel coronavirus (SARS-CoV-2) infections is critical for understanding the overall prevalence and pandemic potential of this disease. Using observations of reported infection within China, in conjunction with mobility data, a networked dynamic metapopulation model and Bayesian inference, we inferred critical epidemiological characteristics associated with SARS-CoV-2, including the fraction of undocumented infections and their contagiousness. We estimated 86% of all infections were undocumented (95% CI: [82%-90%]) prior to January 23, 2020 travel restrictions. Per person, these undocumented infections were 55% as contagious as documented infections ([46%-62%]) and were the source of infection for two-thirds of documented cases. These findings explain the rapid geographic spread of SARS-CoV-2 and indicate containment of this virus will be particularly challenging. See the research article published in [Science](https://science.sciencemag.org/content/early/2020/03/13/science.abb3221).

## Counterfactual simulations of COVID-19 spread in the United States

Assessing the effects of early non-pharmaceutical interventions on COVID-19 spread is crucial for understanding and planning future control measures to combat the pandemic. We used observations of reported infections and deaths, human mobility data, and a metapopulation transmission model to quantify changes in disease transmission rates in US counties from March 15 to May 3, 2020. We found that marked, asynchronous reductions of the basic reproductive number occurred throughout the US in association with social distancing and other control measures. Counterfactual simulations indicate that, had these same measures been implemented 1-2 weeks earlier, substantial cases and deaths could have been averted, and that delayed responses to future increased incidence will facilitate a stronger rebound of infections and death. This study, published in [Sci. Adv.](https://advances.sciencemag.org/content/early/2020/11/05/sciadv.abd6370), was reported by the New York Times ["Lockdown Delays Cost at Least 36,000 Lives, Data Show"](https://www.nytimes.com/2020/05/20/us/coronavirus-distancing-deaths.html).

<figure style="float: left;">
    <img src='/images/counterfactual.png' style='width:100%;'>
</figure>

## Burden and characteristics of COVID-19 in the United States

We used a data-driven model-inference approach to simulate the pandemic at county-scale in the United States during 2020 and estimated critical, time-varying epidemiological properties underpinning the dynamics of the virus. The pandemic in the US during 2020 was characterized by national ascertainment rates that increased from 11.3% (95% credible interval (CI):8.3 – 15.9%) during March to 24.5% (18.6 – 32.3%) during December. Population susceptibility at year’s end was 69.0% (63.6 – 75.4%), indicating that roughly one third of the US population had been infected. Community infectious rates, the percentage of people harbouring a contagious infection, rose above 0.8% (0.6 – 1.0%) before the end of the year, and were as high as 2.4% in some major metropolitan areas. In contrast, the infection fatality rate fell to 0.3% by year’s end. This study was published in [Nature](https://www.nature.com/articles/s41586-021-03914-4) and highlighted in the [NIH Director's Blog](https://directorsblog.nih.gov/2021/09/07/covid-19-infected-many-more-americans-in-2020-than-official-tallies-show/).


## Transmission dynamics of SARS-CoV-2

We led and participated in several studies that eluciated the transmission dynamics of SARS-CoV-2. Collaborating with colleagues at Union of Concerned Scientists, We modeled the compound risks of hurricane evacuation amid the COVID-19 pandemic ([Pei et al. GeoHealth 2020](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2020GH000319)). In a collaboration with colleagues at Yale, we quantified the role of meteorological factors in the transmission of SARS-CoV-2 ([Ma et al. Nat. Commun. 2021](https://www.nature.com/articles/s41467-021-23866-7)). We also quantified the impact of COVID-19 non-pharmaceutical interventions on influenza tansmission in the United States ([Qi et al. J. Infect. Dis. 2021](https://academic.oup.com/jid/advance-article/doi/10.1093/infdis/jiab485/6374002)).

## Contact tracing and COVID-19 transmission in New York City

Using contact tracing records and high-resolution surveillance data, we analyzed community transmission of SARS-CoV-2 in NYC. We found considerable heterogeneity in reported close contacts and secondary infections and evidence of extensive transmission across ZIP code areas. Our analysis revealed the spatial pattern of SARS-CoV-2 spread and communities that were tightly interconnected by exposure and transmission. We found that locations with higher vaccination coverage and lower numbers of visitors to points-of-interest had reduced within- and cross-ZIP code transmission events, highlighting potential measures for curtailing SARS-CoV-2 spread in urban settings. We also found the Delta variant produced greater long-range spatial transmission across NYC ZIP code areas, likely caused by its increased transmissibility and elevated human mobility  These studies were published in [Pei et al. Nat. Commun. 2022](https://www.nature.com/articles/s41467-022-34130-x), [Dai et al. BMC Infect. Dis. 2023](https://link.springer.com/article/10.1186/s12879-023-08735-6), and [He et al. BMC Public Health 2024](https://link.springer.com/article/10.1186/s12889-024-17920-4).
