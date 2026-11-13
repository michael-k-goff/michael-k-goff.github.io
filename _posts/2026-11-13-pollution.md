---
layout: post
title: 'Cities and Pollution'
tags: []
comments: true
mathjax: true
author: Michael Goff
---
There is no blanket statement that can be made about how pollution varies with city size, since "pollution" is broad phenomenon, and different kinds of pollution operate according to different dynamics. We will consider several kinds of pollution and see how their behavior with respect to city size varies considerably.

Following such works at [Bettencourt (2013)](https://doi.org/10.1126/science.1235823), many researchers seek to find allometric scaling relationships between a city's population N and levels of a pollutant Y:

$$Y(N) = Y_0N^\beta.$$

Here, Y₀ and β are constants. The value β, in particular, is of the greatest interest, and it indicates how a quantity scales with city size. Under the null hypothesis β=1, the quantity remains constant on a per-capita basis for cities of different sizes. β>1 indicates superlinear scaling, and researchers generally find that socioeconomic quantities such as incomes and GDP demonstrate superlinear scaling. β<1 indicates sublinear scaling, and [Bettencourt (2013)](https://doi.org/10.1126/science.1235823) finds that sublinear scaling applies to infrastucture quantities such as lane-miles of road and lengths of power lines and water pipes.

## Nitrogen Dioxide

Nitrogen dioxide (chemically NO₂) is a widespread and deadly pollutant, and it can be classified among the more general family of nitrogen oxide pollutants (NOₓ). With NO₂, there are three quantities that we might be interested in. First, there are total emissions. If emissions can be expressed as a exponent of city size N^β, then we can ask how emissions vary with city size. The null hypothesis is β=1, which is that individuals emit the same regardless of what kind of city they live in.

Second, there is ambient concentration. If concentration is expressed as N^β, then the null hypothesis is β=0, which is that the level of pollution concentration is the same regardless of city size. It should be emphasized that the null hypotheses β=1 for emissions and β=0 for concentration are *not* equivalent for several reasons. The first reason is that, as discussed in [Bettencourt (2013)](https://doi.org/10.1126/science.1235823), population density tends to increase with population (theoretically, at the 1/6 power). It is therefore possible for emissions per capita to be flat with city size—-equivalently, total emissions increase linearly with an exponent β=1—-while concentration increases. A second reason is that the mechanism for pollution removal is not specified. With a geographically larger city, it is possible that pollution lingers for a longer time, and so concentration increases for reasons that are separate from emissions. Yet another reason, as discussed by [Wurm et al. (2025)](https://doi.org/10.1371/journal.pone.0333902), is that nonanthropogenic sources of pollution might become significant especially in the rural hinterlands that may be considered part of an urban area for the purposes of analysis.

A third quantity of interest is population exposure. This is roughly equal to population times concentration, but they are not exactly equal, as within a city, population density might correlate (positively or negatively) with concentration.

The following studies show a robust pattern of increasing NO₂ concentration for lager cities. Furthermore, there is strong evidence to suggest that the main cause of this is not increased per-capita emissions or higher population density, but rather for the tendency for pollution to linger in a city longer when it is geographically larger.

### Scaling Results

[Lamsal et al. (2013)](https://doi.org/10.1021/es400744g) use satellite data from the Ozone Monitoring Instrument project to analyze ground-level nitrogen dioxide (NO₂). The satellite data do not give ground-level NO₂ directly, but the authors apply a model to estimate that quantity from the total level of NO₂. They find that ground-level NO₂ concentration scales with city population with an allometric coefficient, meaning that NO₂ concentration can be expressed as a power of city population. The allometric coefficients are 0.42 for the United States, 0.46 for Europe, 0.69 for China, and 0.59 for India. Cities with large power plants are excluded, since this would disrupt the results. The correlation coefficient varies from 0.59 for India to 0.71 for the US, indicating a strong model. The paper does not explicitly discuss a removal mechanism, and so it is unclear how to translate their concentration figures into emissions figures.

[Wurm et al. (2025)](https://doi.org/10.1371/journal.pone.0333902) analyze just over 10,000 cities worldwide to identify scaling relationships between city size and NO₂ pollution. They consider the total level of NO₂ within a city. To insure consistency across different parts of the world, which is a major challenge for international urban scaling analyses, they define cities based on clustering settlements by population density. NO₂ concentration is determined by three satellite data sources, and those are augmented by emissions data from the Emissions Data for Global Atmospheric Research.

On a global level, [Wurm et al. (2025)](https://doi.org/10.1371/journal.pone.0333902) find an essentially linear relationship between city size and NO₂ levels; the scaling exponent is 0.999, indicating no global relationship between city size and per-capita NO₂ concentration. However, the global aggregation masks substantial variation by world region. By world region, those exponents range from 0.788 in Middle Africa to 1.130 in Australia/New Zealand. The authors find some evidence of an environmental Kuznets curve, whereby the volume of NO₂ concentration per capita increases as a country becomes wealthier, until it reaches a peak and decreases. Note that the EKC is actually for the scaling exponent, not for NO₂ concentration per se. Also, the data show at best a modest decrease for high levels of wealth and not at a statistically significant level.

The choice of city boundaries matters greatly, and thus it is crucial for the method of setting boundaries to be consistent for international comparisons to be meaningful. For the United States and with the clustering approach described above, [Wurm et al. (2025)](https://doi.org/10.1371/journal.pone.0333902) find that the scaling exponent is between 1.06 and 1.09, depending on which NO₂ dataset they use. However, the exponent is much lower—between 0.58 and 0.78—when metropolitan statistical areas rather than morphological boundaries are used. MSAs are larger and incorporate much rural area with natural sources of NO₂, which helps explain the flatter scaling.

[MacKenzie et al. (2019)](https://doi.org/10.1088/1748-9326/ab50e3) focus on emissions of NO₂, rather than concentration, and they find a strongly sublinear scaling exponent of emissions in terms of city size. Their analysis is based on 3030 settlements in Great Britain, comprising about 80% of the region’s population. The exponent is around 0.6 for emissions of sources of both nitrogen dioxide and particulates (PM2.5 and PM10).

[Wei, Lemoy, and Caruso (2024)](https://doi.org/10.1016/j.cacint.2024.100161) conduct a meta-review and find that a 10-fold growth in city population increases NO₂ emissions by 40%, which is equivalent to a scaling exponent of around 0.15, a more modest value than some other papers discussed here. They call for a more consistent definition of cities for making international comparisons, an issue later addressed by [Wurm et al. (2025)](https://doi.org/10.1371/journal.pone.0333902).

### Variance Within Cities

Both emissions and concentration of nitrogen dioxide varies within cities, as well as between cities.

[MacKenzie et al. (2019)](https://doi.org/10.1088/1748-9326/ab50e3) predict that the prevalence of NO₂ hotspots should scale with the 1.1 power of city population. This is not due to an increase of emissions but rather due to an increase in the number of areas with poor ventilation. The authors lack the data to determine if this is the case, and to my knowledge, no paper has addressed the hotspot question.

However, [Huang et al. (2026)](https://doi.org/10.1038/s41467-026-73015-1) do find intra-urban concentration effects for three quantities, of which thermal exposure is the most relevant for today’s topic. They measure concentration with the Gini coefficient, which is a measure of inequality most well-known in the context of wealth and income. A Gini coefficient of 0 would signify perfect equality: everyone in the city experiences the same level of pollution. A coefficient of 1 signifies perfect inequality: a single person experiences the entirety of pollution. [Huang et al. (2026)](https://doi.org/10.1038/s41467-026-73015-1) find that the Gini coefficient increases by 8-9% for every doubling of city size by analyzing around 11,000 urban centers worldwide. However, the authors do not address NO₂ specifically.

### Removal of NO₂

The connection between concentration and emissions of NO₂ and its precursors is not straightforward. As discussed above, one thing it depends on is population density. If two cities have the same population and per-capita emissions, but one has a higher population density than the others, we would expect, with all else being equal, the city with a higher population density to have higher NO₂ concentration because the same amount of NO₂ is concentrated into a smaller area. [Bettencourt (2013)](https://doi.org/10.1126/science.1235823) finds that population density scales with about the 0.15 power of overall population, while [Lamsal et al. (2013)](https://doi.org/10.1021/es400744g) find that NO₂ concentration scales with an exponent of 0.42 to 0.69, depending on region. Under a simple removal model, whereby NO₂ is removed at the same point it is emitted through chemical processes, it would follow that emissions scale with an exponent between 0.27 and 0.54.

However, another removal model is the box model, as developed by [Hanna (1973)](https://doi.org/10.1016/0004-6981(73)90143-1), whereby NO₂ or other pollutants are removed primarily by wind blowing the pollution out of the city. In that case, a larger city area would increase the amount of time that pollution lingers within city limits and thus the concentration. Consider two cities X and Y, whereby X has twice the population and twice the area—hence the same population density—as Y, and both have the same per-capita emissions and are otherwise identical. In that case, since pollutants remain in X for 40% longer (the square root of 2), we expect concentration to be 40% higher. This phenomenon, rather than higher per-capita emissions, might explain higher NO₂ concentrations in larger cities. In particular, under a simplified model of constant population density, city shape, and per-capita emissions, the box model suggests that NO₂ concentration should grows with the square root of population, since area grows proportionally with population and radius and thus pollution lifetime grows with the square root of population.

Although [MacKenzie et al. (2019)](https://doi.org/10.1088/1748-9326/ab50e3) do not identify a removal model explicitly, they state that “Our predicted concentration scaling with population is strongly sub-linear, with a slope about half that of the emissions scaling”, suggesting a box model.

The dissertation of Paredes-Miranda (2011) focuses on aerosols, rather than NO₂, and it finds that aerosol concentration grows with the square root of population. The mechanism by which this growth occurs is similar to that of the box model for NO₂.

### Cross-Sectional and Temporal Trends

While this review has been primarily concerned with cross-sectional effects--how emissions and concentration vary with city size at a fixed point in time--we should not fully neglect to discuss the temporal trend of decreasing NO₂ pollution.

[Wurm et al. (2025)](https://doi.org/10.1371/journal.pone.0333902) document massive decreases in NO₂ emissions from 2005 to 2020 of 50.5% in Europe, 61.2% in North America, and 42% in Oceana. Significant but more modest decreases of 26.4% in Asia and 27.9% in Latin America were found, and Africa has shown only a 6.6% decrease. In wealthier countries, the effects of improved technology and pollution control vastly outweigh any negative effect on NO₂ concentration that results from growing cities.

## Carbon Dioxide and City Size

The research on CO₂ emissions and city size does not yield many firm conclusions. Part of the challenge is that, in additional to the usual difficulties in defining the scope of a city, we have ambiguity in how CO₂ emissions are measured. Are we including Scope 2 and Scope 3 emissions, and are emissions from a power plant or a factory attributed to where the product is produced or where it is consumed? We also have the challenges of which emissions (i.e. from roads, electricity production, homes, etc.) are counted and which are not.

[Oliveria, Andrade, and Makse (2014)](https://doi.org/10.1038/srep04235) analyze 2281 cities in the United States, and they find that overall CO₂ emissions grow with the 1.46 power of city size, or in other words, β=1.46. The authors use the City Clustering Algorithm of [Rozenfeld et al. (2008)](https://doi.org/10.1073/pnas.0807435105), similar to the technique of [Wurm et al. (2025)](https://doi.org/10.1371/journal.pone.0333902). The CCA has the advantage of allowing comparable analyses across different countries, but it does not necessarily capture commuting patterns.

[Oliveria, Andrade, and Makse (2014)](https://doi.org/10.1038/srep04235) differentiate between different classes of CO₂ emissions, including cement, aviation, onroad vehicles, nonroad vehicles (e.g. trains, boats, snowmobiles), residential, industrial, commercial, and electricity. They find that total emissions scale superlinearly with population for each of these categories except for cement, which scales sublinearly, and aviation, for which the scaling exponent is statistically indistinguishable from 1.

One reason for caution in reading [Oliveria, Andrade, and Makse (2014)](https://doi.org/10.1038/srep04235) is distinguishing between production-based and consumption-based emissions. The authors attribute emissions to where they occur: production-based emissions. This issue is particularly important with electricity, since emissions are attributed to the power plant. Only 678 of the 2281 clusters have nonzero electricity emissions, and of all the emissions subsectors, electricity emissions scale with the highest exponent of β=1.62 and with a weak R² value of 0.38. A similar objection could be made against industrial emissions. While their results might overstate the strength of the relationship, the conclusion that emissions scale superlinearly with city size is likely robust to this consideration.

[Gudipudi et al. (2019)](https://doi.org/10.1177/2399808319825867) discuss the production versus consumption accounting problem in greater detail. In greenhouse gas accounting, there is a distinction between Scope 1, Scope 2, and Scope 3 emissions. Scope 1 emissions refer to emissions directly within an urban boundary. Scope 2 emissions include Scope 1 emissions and the emissions that results from electricity and heat consumption within a city, even if the electricity and heat are generated outside the boundary. Scope 3 emissions include those of the previous scopes and also the net embodied energy (embodied emissions in imported materials, minus embodied emissions in exported materials) in good and materials that are imported. Scope 3 emissions would be the most desirable for analysis, but data limitations typically require us to use Scope 1 or Scope 2.

Another potential objection to [Oliveria, Andrade, and Makse (2014)](https://doi.org/10.1038/srep04235) is that the superlinear scaling of emissions is capturing higher levels of wealth. As we saw early in the project, larger cities tend to see higher per-capita GDP levels, and higher GDP tends to be associated with higher CO₂ emissions. To address this concern, the authors group the cells used for clustering into income groups. They find that for all but the lowest income group, emissions scale superlinearly with city population for that particular income group. The scaling rate is highest for a middle income group, with declining scaling rates for higher income groups. The authors argue that these results comprise an environmental Kuznets curve, where pollution tends to increase with wealth up to a certain level and decline after that level. Such a conclusion is difficult to draw from the weak and limited evidence in the paper—and note also that the scaling exponent is different from overall levels of pollution—but it does address the concern that the scaling is actually capturing a wealth effect.

Let us now consider [Fragkias et al. (2013)](https://doi.org/10.1371/journal.pone.0064727). Unlike [Oliveria, Andrade, and Makse (2014)](https://doi.org/10.1038/srep04235), [Fragkias et al. (2013)](https://doi.org/10.1371/journal.pone.0064727) finds slightly sublinear scaling of CO₂ emissions with size. The estimated scaling exponent is around 0.93 and indicates a weak sublinear scaling, so that per-capita emissions go down in larger cities, and the 95% confidence interval excludes 1.0, indicating statistical significance. However, [Fragkias et al. (2013)](https://doi.org/10.1371/journal.pone.0064727) also perform a regression with density and per-capita incomes as control values, and with these controls, the scaling exponent for city size is no longer distinguishable from 1.0.

In a commentary, [Louf and Barthelemy (2014)](https://arxiv.org/html/1410.4964v1) observe that the main reason for the difference in results is the choice of city definitions. [Oliveria, Andrade, and Makse (2014)](https://doi.org/10.1038/srep04235) use the City Clustering Algorithm, while [Fragkias et al. (2013)](https://doi.org/10.1371/journal.pone.0064727) use metropolitan statistical areas. The fact that the observed scaling results are not robust to city definition choices raises concerns about how reliable they are.

Taking an international perspective, [Rybski et al. (2017)](https://doi.org/10.1177/0265813516638340) fit scaling relationships of CO₂ emissions, in terms of city size, to many countries worldwide. They find that CO₂ emissions tend to scale sublinearly in wealthier countries and superlinearly in poorer countries, with the cutoff at around a GDP per capita level of $10,000. In other words, for lower-income countries, urbanization leads to an increase in CO₂ emissions. In higher-income countries, urbanization leads to a decrease in CO₂ emissions.

There are several reasons to be cautious of the conclusion of [Rybski et al. (2017)](https://doi.org/10.1177/0265813516638340) that urbanization reduces emissions in wealthy countries but not in poorer countries. The data is drawn from several sources, which appear to differ in several ways that do not average out over GDP groups: the sectors of CO₂ emissions analyzed, how emissions are accounted, and the spatial definition of a city. This analysis suffers from a weakness that affects many urban scaling analyses, in that it does not make a case that larger cities cause emissions to go up or down as indicated by scaling laws.

## References

Bettencourt, L. ["The Origins of Scaling in Cities"](https://doi.org/10.1126/science.1235823). Science **340**(6139). June 2013.

Wurm, M., Erbertseder, T., Weigand, M., Taubenböck, H. ["Global scaling of urban air quality"](https://doi.org/10.1371/journal.pone.0333902). PLoS One **20**(10): e333902. October 2025.

Lamsal, L.N., Martin, R.V., Parrish, D.D., Krotkov, N.A. ["Scaling Relationship for NO₂ Pollution and Urban Population Size: A Satellite Perspective"](https://doi.org/10.1021/es400744g). Environmental Science & Technology **47**(14), pp. 7855-7861. July 2013.

Huang, C., Liu, X., Zhang, S., Jin, Z., Xu, N., Ou, W. ["A universal scaling law of intra-urban inequality"](https://doi.org/10.1038/s41467-026-73015-1). Nature Communications **17**: 6264. May 2026.

MacKenzie, A.R., Whyatt, J.D., Barnes, M.J., Davies, G., Hewitt, C.N. ["Urban form strongly mediates the allometric scaling of airshed pollution concentrations"](https://doi.org/10.1088/1748-9326/ab50e3). Environmental Research Letters **14**(12): 124078. December 2019.

Wei, Y., Lemoy, R., Caruso, G. ["The effect of population size on urban heat island and NO₂ air pollution: Review and meta-analysis"](https://doi.org/10.1016/j.cacint.2024.100161). City and Environment Interactions **24**L 100161. December 2024.

Paredes-Miranda, G. ["Aerosol Light Absorption and Scattering Assessments and the Impact of City Size on Air Pollution"](https://scholarwolf.unr.edu/items/52db8c09-40a6-4541-9966-b06194e32942). University of Nevada, Reno. 2011.

Oliveira, E.A., Andrade Jr, J.S., Makse, H.A. ["Large cities are less green"](https://doi.org/10.1038/srep04235). Scientific reports. 2014 Feb 28;4(1):4235.

Rozenfeld, H.D., Rybski, D., Andrade Jr, J.S., Batty, M., Stanley, H.E., Makse, H.A. ["Laws of population growth"](https://doi.org/10.1073/pnas.0807435105). Proceedings of the National Academy of Sciences **105**(48), pp. 18702-18707. December 2008.

Gudipudi, R., Rybski, D., Lüdeke, M.K., Kropp, J.P. ["Urban emission scaling—Research insights and a way forward"](https://doi.org/10.1177/2399808319825867). Environment and Planning B: Urban Analytics and City Science **46**(9), pp. 1678-1683. November 2019.

Fragkias, M., Lobo, J., Strumsky, D., Seto, K.C. ["Does Size Matter? Scaling of CO₂ Emissions and US Urban Areas"](https://doi.org/10.1371/journal.pone.0064727). Plos one. 2013 Jun 4;8(6):e64727.

Louf, R., Barthelemy, M. ["Scaling: Lost in the smog"](https://arxiv.org/html/1410.4964v1). Environment and Planning B: Planning and Design **41**(5), pp. 767-769. October 2014.

Rybski, D., Reusser, D.E., Winz, A.L., Fichtner, C., Sterzel, T., Kropp, J.P. ["Cities as nuclei of sustainability?"](https://doi.org/10.1177/0265813516638340). Environment and Planning B: Urban Analytics and City Science **44**(3), pp. 425-440. May 2017.