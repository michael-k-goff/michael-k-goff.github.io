---
layout: post
title: 'City Size and Crime'
tags: []
comments: true
mathjax: true
author: Michael Goff
---
Large cities tend to facilitate more [social interaction](/2024-12-20-urban-scaling), which includes negative interactions such as crime.

## Background on Urbanization and Crime

The relationship between city size and crime is well-known as is widely considered one of the drawbacks of large cities. As [Friendly (2007)](https://doi.org/10.1214/07-STS241) recounts, early important work goes back to André-Michel Guerry and such works as Balbi and Guerry (1829) and Guerry (1833). Balbi and Guerry (1829) found an inverse correlation between personal crimes and property crimes across départements in France, but both were higher in urban areas. Guerry (1833) collects and presents "moral statistics" in France, including data on crime, literacy, suicide, and according to [Friendly (2007)](https://doi.org/10.1214/07-STS241), is both a pioneering work in social science and in data visualization.

## Why Does Crime Scale?

[Chamlin and Cochran (2004)](https://heinonline.org/HOL/LandingPage?handle=hein.journals/wescrim5&div=15&id=&page=) discuss three major models for how and why crime scales with population.

### Social Control

The social control model holds that in larger cities, the informal social norms that restrain antisocial behavior break down. [Groff (2015)](https://doi.org/10.1177/1043986214552619) distinguishes between formal social control--consisting of formal institutions such as the police--and informal social control, which is enforced by residents who are outside of formal institutions. Most social control is informal, and she further subdivides informal social control into two mechanisms.

The "eyes of the street" perspective, associated with the urban activist Jane Jacobs ([Jacobs (1961)](https://www.amazon.com/Death-Life-Great-American-Cities/dp/067974195X) and [Jacobs (1968)](https://www.amazon.com/search-community-modern-America/dp/B00005WRUR)), holds that a large number of engaged people able to watch for crime is an effective deterrant. The human territorial functioning perspective, as presented in [Taylor (1988)](https://psycnet.apa.org/doi/10.1017/CBO9780511571237), holds that residents deter crime by engaging in territorial behavior with their property.

[Greenberg, Rohe, and Williams (1982)](https://www.ojp.gov/ncjrs/virtual-library/abstracts/safe-and-secure-neighborhoods-physical-characteristics-and-informal) examine several high- and low-crime neighborhoods in Atlanta, Georgia. They find that important difference between the two is that high-crime neighborhoods have larger amounts of vacant and non-residential land, more blocks with major thoroughfares rather than small streets, more public parking, and a more stable population, even after controlling for age and sex. They argue that the data is evidence against Jacobs' "eyes of the street" hypothesis. Furthermore, [Greenberg, Rohe, and Williams (1982)](https://www.ojp.gov/ncjrs/virtual-library/abstracts/safe-and-secure-neighborhoods-physical-characteristics-and-informal) find that, in contrast to the human territorial functioning hypothesis, territoriality tends to be higher in high-crime neighborhoods. They suggest that the reason for this is that territoriality is more a response to high crime than a method of preventing it.

[Browning and Jackson (2013)](https://doi.org/10.1111/1745-9125.12026) attempt to test Jacobs' "eyes on the street" hypothesis by identifying a relationship between the proportion of active streets and the level of crime for neighborhoods in Chicago. Here, "active" streets are defined by the presence of adult pedestrians and are identified by video data the from Project on Human Development in Chicago Neighborhoods. The proportion of active streets are then related to the level of violence witnessed by adolescents and independent measures of the level of crime. They find violent crime shows an inverse-U relationship to the proportion of active streets. At a low level, increasing the proportion of active streets tends to increase the level of violent crime, while at a high level, further increasing the proportion of active streets tends to decrease the level of violent crime. An interpretation of these findings is that, when there are few active streets, the presence of active streets draws out pedestrians who are then victimized at non-active streets, while this problem is avoided when most streets are active. These results are ambiguous in establishing the "eyes on the street" hypothesis.

### Structuralism

The structuralist model posits that crime is a product of dense social interactions, and consequently, larger and denser cities have higher rates of crime. Although he does not use the term, the physics-inspired analysis of [Bettencourt (2013)](https://doi.org/10.1126/science.1235823) suggests a structuralist model by presenting crime, as well as other positive and negative socialeconomic quantities such as gross domestic product and the spread of disease, as a product of the rate of social interaction, which is greater in large cities. As [Chamlin and Cochran (2004)](https://heinonline.org/HOL/LandingPage?handle=hein.journals/wescrim5&div=15&id=&page=) note, the structuralist model does not necessarily imply that larger cities have higher crime rates, as larger cities can also foster integrative interactions, i.e. interactions that reduce crime.

[Greenberg, Rohe, and Williams (1982)](https://www.ojp.gov/ncjrs/virtual-library/abstracts/safe-and-secure-neighborhoods-physical-characteristics-and-informal), noted above, may provide some evidence for a structuralist model of crime, insofar as mixed use development, major thoroughfares, and public parking all increase the accessibility of a neighborhood and thus the number of interactions that may give rise to crime.

### Subculturalism

The subcultural model, developed in [Fischer (1975)](https://doi.org/10.1086/225993), holds that larger cities foster more opportunity for the emergence of subcultures, some of which promote deviant social norms, and thus increase the crime rate.

[D'Alessio and Stolzenberg (2010)](https://doi.org/10.1016/j.jcrimjus.2010.04.045) attempt to empirically distinguish the subcultural model from the social control model of crime rates. Under subculturalism, we might expect that, as a consequence of the prevalence of deviant subcultures, there would be a higher rate of co-offense in crime, which [D'Alessio and Stolzenberg (2010)](https://doi.org/10.1016/j.jcrimjus.2010.04.045) define as multiple people with prior socially connections who participate in the same crime. Drawing on crime data from the  National Incident-Based Reporting System, they perform regressions of several measures of city size or population density against the rate of co-offense. [D'Alessio and Stolzenberg (2010)](https://doi.org/10.1016/j.jcrimjus.2010.04.045) find that measures of city size are either negative correlated with the rate of co-offense, or there is no statistically significant relationship between the two, and they find adjusted R² values between 0.34 and 0.36. However, they also find that the crime rate is positively correlated with the rate of co-offense. [D'Alessio and Stolzenberg (2010)](https://doi.org/10.1016/j.jcrimjus.2010.04.045) conclude that, while not decisively, their evidence weighs against the subcultural model of the size-crime relationship and instead supports a model of social breakdown, which is expected under the social control model.

## How Crime Scales with City Size

[Hanley, Lewis, and Riberio (2016)](https://doi.org/10.1371/journal.pone.0149546) consider the relationship between crime levels and population density in the 537 Parliamentary Constituencies in England and Wales. They find that population density yields better predictions than overall population size in a constituency, and the density of crime (number of crimes per hectare per year) yields better predictions than overall crime level. They also find that daytime population density yields slightly better predictions than overall population density. They find a scaling coefficient of 1.16 ± 0.01, meaning that for a small increase ε in population density, an increase of 1.16ε in crime level should be expected. Equivalently, if population density doubles, then crime density should increase by a factor of 2.23.

For many crimes, [Hanley, Lewis, and Riberio (2016)](https://doi.org/10.1371/journal.pone.0149546) find "urban effects", or discontinuities in the scaling rates at certain population density thresholds. For the majority of crimes, including bike theft, drugs, order, other theft, robbery, theft from the person, and violence, an *accelerated urban effect* was found, by which the scaling factor increases above a population density threshold. *Inhibited urban scaling*, indicating that the scaling coefficient decreases above a population density threshold, was found for anti-social behavior, criminal damage and arson, and shoplifting. For several crime categories, including total crime, no such urban effect was found. All data in the analysis is publicly available, with crime data taken from the UK Home Office and population data taken from Ordnance Survey and the Office of National Statistics.

Considering cities in 12 countries, [Oliveira (2016)](https://doi.org/10.1186/s40163-021-00155-8) examines rates of burglary and theft across cities of different sizes where statistics are available. He finds that in most countries for which data is available, theft increases superlinearly in city population size, meaning that as cities grow, the number of thefts per person increases. By contrast, he finds that burglary generally scales linearly with city size, meaning that as cities grow, the number of burglaries per person generally remains constant. However, in both cases, there is substantial variance across countries in the growth rate.

[Nolan (2004)](https://doi.org/10.1016/j.jcrimjus.2004.08.002) uses the the Uniform Crime Reports, published by the American Federal Bureau of Investigation, to establish a link between crime rates and city size. The UCR reported crimes rates for 1294 cities in the United States with a population of at least 25,000. The paper divides the cities into four groups, delineated by population size, and finds that crime rates (the number of crimes per capita) are indeed higher on average for groupings of larger cities. Within most groups, the crime rate and population are also positively correlated. However, in the largest group--population at least 250,000--a negative correlation between city size and crime is found, with a negative correlation specifically for property crimes and no statistically significant correlation for violent crimes. This suggests that the crime/size relationship might break down for sufficiently large cities.

## References

Hanley, Q. S., Lewis, D., Riberio, H. V. ["Rural to Urban Population Density Scaling of Crime and Property Transactions in English and Welsh Parliamentary Constituencies"](https://doi.org/10.1371/journal.pone.0149546). PLoS One **11**(2): e0149546. February 2016.

Guerry, A.-M. *Essai sur la statistique morale de la France*. Crochard, Paris. 1833.

Balbi, A., Guerry, A.-M. *Statistique comparée de l’état de l’instruction et du nombre des crimes dans les divers arrondissements des Académies et des Cours Royales de France*. Paris: Everat. 1829.

Friendly M. ["A.-M. Guerry's "Moral Statistics of France": Challenges for Multivariable Spatial Analysis"](https://doi.org/10.1214/07-STS241). Statistical Science **22**(3), pp. 368-399. August 2007.

Oliveira, M. ["More crime in cities? On the scaling laws of crime and the inadequacy of per capita rankings—a cross-country study"](https://doi.org/10.1186/s40163-021-00155-8). Crime Science **10**(1): 27. December 2021.

Nolan, J. J. III. ["Establishing the statistical relationship between population size and UCR crime rate: Its impact and implications"](https://doi.org/10.1016/j.jcrimjus.2004.08.002). Journal of Criminal Justice **32**(6), pp. 547-555. November 2004.

Chamlin, M.B., Cochran, J.K. ["An excursus on the population size-crime relationship"](https://heinonline.org/HOL/LandingPage?handle=hein.journals/wescrim5&div=15&id=&page=). Western Criminology Review **5**(2), pp. 119-130. 2004.

Bettencourt, L. ["The Origins of Scaling in Cities"](https://doi.org/10.1126/science.1235823). Science **340**(1438). June 2013.

Groff, E. R. ["Informal Social Control and Crime Events"](https://doi.org/10.1177/1043986214552619). Journal of Contemporary Criminal Justice **31**(1), pp. 90-106. February 2015.

Jacobs, J. [*The Death and Life of Great American Cities*](https://www.amazon.com/Death-Life-Great-American-Cities/dp/067974195X). New York, NY: Vintage Books. 1961.

Jacobs, J. "Community on the city streets". In E. D. Baltzell (Ed.), [*The search for community in modern America*](https://www.amazon.com/search-community-modern-America/dp/B00005WRUR), pp. 74-93. New York, NY: Harper & Row. 1968.

Greenberg, S. W., Rohe, W. M., Williams, J. R. ["Safe and Secure Neighborhoods - Physical Characteristics and Informal Territorial Control in High and Low Crime Neighborhoods - Final Report"](https://www.ojp.gov/ncjrs/virtual-library/abstracts/safe-and-secure-neighborhoods-physical-characteristics-and-informal). National Institute of Justice, United States Department of Justice. 1982.

Taylor, R.B. [*Human territorial functioning: An empirical, evolutionary perspective on individual and small group territorial cognitions, behaviors, and consequences*](https://psycnet.apa.org/doi/10.1017/CBO9780511571237). Cambridge University Press; August 1988.

Browning, C. R., Jackson, A. L. ["The Social Ecology of Public Space: Active Streets and Violent Crime in Urban Neighborhoods"](https://doi.org/10.1111/1745-9125.12026). Criminology **51**(4), pp. 1009-1043. November 2013.

D'Alessio, S.J., Stolzenberg, L. ["Do cities influence co-offending?"](https://doi.org/10.1016/j.jcrimjus.2010.04.045). Journal of Criminal Justice. **38**(4), pp. 711-719. July 2010.

Fischer, C. S. ["Toward a Subcultural Theory of Urbanism"](https://doi.org/10.1086/225993). American Journal of Sociology **80**(6), pp. 1319-1341. May 1975.