---
layout: post
title: 'Cities and Wellbeing'
tags: []
comments: true
mathjax: true
author: Michael Goff
---
In what kind of cities are people the healthiest and happiest? The research on this question is murky, and a big part of the challenge is identifying a consistent notion of wellbeing.

## Cities and Depression

Do people tend to be more depressed in large, dense cities, less depressed, or does it matter either way? [Miles, Coutts, and Mohamadi (2011)](https://doi.org/10.1007/s11524-011-9621-2) tackle the question by examining several neighborhoods in Miami. They find that living in a neighborhood with higher residential density is associated with fewer depressive symptoms. They find that a greater amount of green space is associated with fewer depressive symptoms, but that this effect wasn’t statistically significant in the full model. They also find that a higher density of auto commuters is associated with more depressive symptoms.

[Miles, Coutts, and Mohamadi (2011)](https://doi.org/10.1007/s11524-011-9621-2) measure depressive symptoms with the Center for Epidemiological Studies-Depression scale, a self-reported survey that is commonly used to measure depression in the general public, as described by [Radloff (1977)](https://psycnet.apa.org/doi/10.1177/014662167700100306).

The findings of [Miles, Coutts, and Mohamadi (2011)](https://doi.org/10.1007/s11524-011-9621-2), as described above, are specific to a multivariate regression model. That is a linear regression taken on all of the variables simultaneously. They also do ordinary least squares regression on each of the variables individually, and for that, they do not find a significant relationship between depressive symptoms and either housing density or auto commute density.

A major challenge is that residential density and auto commute density are themselves highly correlated. The correlation coefficient is 0.84; a value of 1.0 would mean that there is a perfect linear relationship between them, a value of 0.0 would mean no correlation whatsoever, and a value of -1.0 would mean a perfect linear relationship, but in the opposite direction. As explained by [Kim (2019)](https://doi.org/10.4097/kja.19087), multivariate regression with multicollinearity (that is, independent variables that are highly correlated) leads to unreliable results. See also a detailed overview by [Jim Frost](https://statisticsbyjim.com/regression/multicollinearity-in-regression-analysis/) of the multicolinearity problem and ways to address it.

Another weakness of [Miles, Coutts, and Mohamadi (2011)](https://doi.org/10.1007/s11524-011-9621-2) is that it does not address selection effects or other causality issues. Selection effects mean that perhaps, for whatever reason, people who are prone to depression tend to gravitate to neighborhoods with lower density or more auto commuters, rather than low density or more auto commuters being the cause of depression. [Hoogerbrugge and Burger (2022)](https://doi.org/10.1177/00420980211023052) is one of the minority of studies that attempts to address the selection bias problem. They find that subjective wellbeing in cities in the United Kingdom is worse than in rural areas, but that this effect can be explained, at least in part, by less satisfied people being more likely to make a rural-to-urban move.

The hidden variable problem may further confound our interpretation of the results of [Miles, Coutts, and Mohamadi (2011)](https://doi.org/10.1007/s11524-011-9621-2). This is the situation in which other variables, not studied in the model, are the true explanation for the dependent variable. [Elidan et al. (2000)](https://proceedings.neurips.cc/paper/2000/hash/95e6834d0a3d99e9ea8811855ae9229d-Abstract.html) address this phenomenon in the context of probabilistic models and suggest some complex solutions. In the particular case of [Miles, Coutts, and Mohamadi (2011)](https://doi.org/10.1007/s11524-011-9621-2), they find that housing density is weakly correlated with economic deprivation and negatively correlated with housing stability, and so it may be that these two variables, rather than density per se, is the true cause of the apparent association between density and depression. The data and analysis simply don’t allow us to tell.

[Galea et al. (2005)](https://doi.org/10.1136/jech.2005.033084) discuss the link between depression and housing and neighborhood quality. They find,

> In adjusted models, persons living in neighbourhoods characterised by poorer features of the built environment were 29%-58% more likely to report past six month depression and 36%-64% more likely to report lifetime depression than respondents living in neighbourhoods characterised by better features of the built environment.

The study was conducted in New York City, with data collected via telephone surveying in 2002. The original purpose was to assess the impact of the September 11 attacks on mental health, with proximity to the World Trade Center as a key neighborhood variable, but the purpose shifted between the sampling dates and publication.

[Evans (2003)](https://doi.org/10.1093/jurban/jtg063) also tackles the built environment and mental health. He doesn’t address density directly, but he does address some features of the built environment that are associated with density. For example, he finds that "[h]ighrise housing is inimical to the psychological well-being of women with young children and "loud exterior noise sources (e.g., airports) elevate psychological distress but do not produce serious mental illness". Noise pollution may be an important hidden variable in the density/mental health studies question.

[Park, Koo, and Kang (2026)](https://doi.org/10.1371/journal.pone.0339040) are interested in the impact of density on mental health, particularly in light of the COVID-19 pandemic. Considering 25 neighborhoods in Seoul, they find,

> First, the results revealed that population mobility density, residential density, and public transportation congestion were consistently positively associated with depressive symptoms across both study periods (2020 and 2021). Second, social participation significantly moderated the relationship between urban density characteristics and depressive symptoms, regardless of the pandemic phase.

The interpretation of [Park, Koo, and Kang (2026)](https://doi.org/10.1371/journal.pone.0339040) is that the stress of receiving and transmitting the virus caused greater depressive symptoms in denser environments. However, the study also fails to address the hidden variable problem. It would also have been benefitted from including a non-COVID year as a control, so that we could see how many of these results were in fact driven by the pandemic.

## Density and Relationship Quality

Another aspect of wellbeing is social wellbeing, or the quality of one’s interpersonal relationships. [Mouratidis (2018)](https://doi.org/10.1016/j.cities.2017.10.020) studies several neighborhoods in Oslo, Norway, some of which are suburban and some of which are compact. He finds statistically significant associations between compactness and several metrics related to social wellbeing:

- Opportunities to meet new people,
- Frequency of meeting with relatives and friends,
- Number of close relationships,
- Support from close relationships (significant at p=0.05 but not 0.01),
- Personal relationships satisfaction.

To address the self-selection problem, [Mouratidis (2018)](https://doi.org/10.1016/j.cities.2017.10.020) augments the statistics with structured interviews with participants. The interviewees stated that they had more time and opportunities for socializing in compact areas and some stated that they chose to move specifically for that reason. Although this is intended to mitigate the self-selection problem, it is not entirely clear how it does so.

[Dempsey, Brown, and Bramley (2012)](https://doi.org/10.1016/j.progress.2012.01.001) tackle the question using questionnaires and focus groups. They find that higher densities in United Kingdom studies do indeed foster greater access to services and facilities. However, they find that less social interaction tends to occur in denser neighborhoods.

## Density and Wellbeing

Wellbeing is another concept which does not have an exact, consistent definition in the literature, and the precise definition used may influence the results. [Hebert et al. (2023)](https://happycities.com/blog/does-density-hurt-happiness), working with the consultancy Happy Cities that is based on Charles Montgomery's *Happy City: Transforming Our Lives Through Urban Design* ([Montgomery 2013](https://www.amazon.com/Happy-City-Transforming-Through-Design-ebook/dp/B009LRWHPY)), examines the link between density and wellbeing in metro Vancouver, Canada.

[Hebert et al. (2023)](https://happycities.com/blog/does-density-hurt-happiness) uses surveys to assess seven types of wellbeing, which are then aggregated into three metrics: general wellbeing, social wellbeing, and neighborhood wellbeing (actually, neighbourhood wellbeing; the firm is based in Canada). They surveyed 1886 people in the Vancouver, British Columbia area, for which they were able to determine postal codes for 1565.

A major challenge is that respondents are not equally representative of the population. Some groups, such as women and older people, are overrepresented, meaning that a greater proportion of them answered the survey than live in the area. For public opinion polls, this is a well-known problem. A common—though not always sufficient solution according to [Mercer, Lau, and Kennedy (2018)](https://www.pewresearch.org/methods/2018/01/26/how-different-weighting-methods-work/) for the Pew Research Center—is weighting. This techniques put a heavier value on respondents for underrepresented demographics so that the representation of each demographic in the survey matches their prevalence in society at large. No weighting was done in [Hebert et al. (2023)](https://happycities.com/blog/does-density-hurt-happiness), and it is not clear how much of a difference this would have made.

## References

Miles, R., Coutts, C., Mohamadi, A. ["Neighborhood Urban Form, Social Environment, and Depression"](https://doi.org/10.1007/s11524-011-9621-2). Journal of Urban Health **89**(1), pp. 1-18. October 2011.

Radloff, L. S. [The CES-D Scale: A self-report depression scale for research in the general population](https://psycnet.apa.org/doi/10.1177/014662167700100306). Applied Psychological Measurement **1**(3), pp. 385–401. 1977.

Kim, J.H. ["Multicollinearity and misleading statistical results"](https://doi.org/10.4097/kja.19087). Korean Journal of Anesthesiology **72**(6), pp. 558-569. December 2019.

Frost, J. ["Multicollinearity in Regression Analysis: Problems, Detection, and Solutions"](https://statisticsbyjim.com/regression/multicollinearity-in-regression-analysis/). Statistics by Jim. Accessed February 12, 2026.

Hoogerbrugge, M., Burger, M. ["Selective migration and urban–rural differences in subjective well-being: Evidence from the United Kingdom"](https://doi.org/10.1177/00420980211023052). Urban Studies **59**(10), pp. 2092-2109. August 2022.

Elidan, G., Lotner, N., Friedman, N., Koller, D. ["Discovering Hidden Variables: A Structure-Based Approach"](https://proceedings.neurips.cc/paper/2000/hash/95e6834d0a3d99e9ea8811855ae9229d-Abstract.html). Advances in Neural Information Processing Systems **13**. 2000.

Galea, S., Ahern, J., Rudenstine, S., Wallace, Z., Vlahov, D. ["Urban built environment and depression: a multilevel analysis"](https://doi.org/10.1136/jech.2005.033084). Journal of Epidemiology & Community Health **59**(10). 2005.

Evans, G. W. ["The built environment and mental health"](https://doi.org/10.1093/jurban/jtg063). Journal of Urban Health **80**, pp. 536-555. December 2003.

Park, J., Koo, J-H., Kang, S. ["Urban density and depression during COVID-19 in Seoul: Moderating effects of social participation"](https://doi.org/10.1371/journal.pone.0339040). PLoS One **21**(1): e0339040. January 2026.

Mouratidis, K. ["Built environment and social well-being: How does urban form affect social life and personal relationships?"](https://doi.org/10.1016/j.cities.2017.10.020). Cities **74**, pp. 7-20. April 2018.

Dempsey, N., Brown, C., Bramley, G. ["The key to sustainable urban development in UK cities? The influence of density on social sustainability"](https://doi.org/10.1016/j.progress.2012.01.001). Progress in Planning **77**(3), pp. 89-141. April 2012.

Hebert, M., Avery, E., Cleveland, T., Elokda, H., Borkenhagen, D., Licker, A., Gay, C. ["My home, my neighbourhood"](https://happycities.com/blog/does-density-hurt-happiness). Happy Cities. November 2023.

Montgomery, C. ["Happy City: Transforming Our Lives Through Urban Design"](https://www.amazon.com/Happy-City-Transforming-Through-Design-ebook/dp/B009LRWHPY). Farrar, Straus and Giroux, ISBN 978-1429969536. November 2013.

Mercer, A., Lau, A., Kennedy, C. ["How different weighting methods work"](https://www.pewresearch.org/methods/2018/01/26/how-different-weighting-methods-work/). Pew Research Center. January 2018.