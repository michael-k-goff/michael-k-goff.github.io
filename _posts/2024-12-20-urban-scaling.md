---
layout: post
title: 'Urban Scaling'
tags: []
comments: true
mathjax: true
author: Michael Goff
---
In [another post](/2024-12-07-agglomeration-sources.md), we consider the theoretical causes for agglomeration economies in cities, which are the tendency for some per-capita socioeconomic quantities, such as wages and output per capita, to increase with city size. In this post, we will consider empirically results on how socioeconomic quantities scale with city size.

## Theoretical Scaling

[Bettencourt (2013)](https://doi.org/10.1126/science.1235823), operating from a physics perspective, derives a 7/6 power scaling law for socioeconomic rates in a city, including economic output. Equivalently, per capita output increases with the 1/6 power of size. Also equivalently, the elasticity of per-capita output with population is 1/6 = 0.1666..., or with a 1% increase in city size, we should expect about a 0.1666...% increase in per-capita output. While economic output, or GDP, is a focus, socioeconomic quantities cover a range of factors affecting a person's life, including negative outcomes such as crime.

Bettencourt derives several additional scaling laws. Area should grow with the 2/3 power of population. Infrastructure lengths, such as the number of lane-miles of road and the length of all water pipes and power lines, grow with the 5/6 power of population. What Bettencourt calls "network power dissipation" grows with the 7/6 power of population. Analogizing the city's function to an electrical network, power dissipation refers to quantities such as traffic throughput. Because power dissipation and output grow with the same exponent, we see that urban efficiency, the power required per unit output, is independent of city size.

Under Bettencourt's model, cities form when the benefits of the interactions they foster outweigh dissipative costs. However, for sufficiently large cities, costs grow at a faster rate than interactions fostered, and this places a limit on how large cities can grow.

Bettencourt's model is based on four assumptions.

- Mixing populations. A resident at any point in the city should be able to commute daily to any other point in the city. As discussed in [an article](/2024-10-26-marchetti) on Marchetti's Constant (see [Marchetti (1994)](https://doi.org/10.1016/0040-1625(94)90041-8)), the city size is then very roughly defined a 30 minute commute radius around a central business district.
- Incremental network growth. Because cities grow incrementally and naturally, infrastructure networks (roads, water, electric, etc.) are decentralized. A consequence of this, in light of the first assumption, is that travel paths are generally not straight lines, nor should residents at the city fringe expect highway speed travel to the city center.
- Bounded human effort. As noted in the next assumption, socioeconomic quantities are modeled to grow with the number interactions between people, but this can lead to a problem where, as a city grows, the number of interactions required is too great for an individual person. Bettencourt resolves this by assuming that individual does not grow unbounded.
- Socioeconomic outputs are proportional to social interactions. This captures the intuition that a city is not merely a collection of people who live near each other, but rather wealth is created through the interactions between them. This point is emphasized by [Jacobs (1969)](https://www.penguinrandomhouse.com/books/86059/the-economy-of-cities-by-jane-jacobs/).

The last assumption concerns me the most because of the local manner in which interactions are defined. Bettencourt considers interactions as local and bounded by the region that a resident is able to travel in a daily commute. However, interactions can also be non-local--intermediated by telecommunications rather than face-to-face contact--and they occur between cities on a lesser than daily frequency, intermediated by long-distance road trips or aviation. For these reasons, I would suspect that smaller cities have a relative advantage to Bettencourt's model and thus the strength of the scaling relationship may be less than what Bettencourt assesses.

## Empirical Findings

Now that we have considered some theory on how city output should vary with size, let us consider some empirical results.

[Bettencourt (2013)](https://doi.org/10.1126/science.1235823) also presents findings based on Metropolitan Statistical Areas (MSAs) in the United States for the year 2006. Performing a regression of gross metropolitan product against population, Bettencourt finds that the best fit is that output scales with the 1.126 power of size. The 95% confidence interval is 1.126 ± 0.023 with a remarkably high R² value of 0.96, meaning that population explains most of the variation in per-capita output. However, the theoretical value of 7/6 (1.1666...) lies above the upper end of the confidence interval, suggesting that the scaling is not as strong as the model would predict. Bettencourt also finds that the number of lane-miles scales with the 0.849 ± 0.038 power (95% confidence interval) of population, this time containing the theoretical value of 5/6 = 0.8333..., but with a less impressive R²=0.65.

Here, a "city" is defined as a metropolitan statistical area, as defined by the U.S. Office of Management and Budget. These regions, which generally do not correspond to the political boundaries of a city, refer to a central city and surrounding areas that function as a unified labor market with a high degree of social and economic integration.

[Lobo et al. (2013)](https://doi.org/10.1371/journal.pone.0058407) examine 942 cities in the United States as of 2011 and find that the elasticity of per-capita output with respect to population size is 1.146. Equivalently, if a city size doubles, then per-capita output increases by just under 11%. These values are close to the theoretical elasticity of 7/6 that is argued by [Bettencourt (2013)](https://doi.org/10.1126/science.1235823). Size fits the per-capita output data well.

![Per-Capita Output and City Size](/assets/img/pone.0058407.g001.tif){: .mx-auto.d-block :}
*Per-capita output and city size. Image from [Lobo et al. (2013)](https://doi.org/10.1371/journal.pone.0058407).*
pone.0058407.g001.tif

Similar to [Bettencourt (2013)](https://doi.org/10.1126/science.1235823), Lobo et al. define cities as metropolitan or micropolitan statistical areas. These regions roughly correspond to labor markets that are unified under a feasible daily commute.

[Lobo et al. (2013)](https://doi.org/10.1371/journal.pone.0058407) estimate a residual ξ for each city, a deviation between the predicted output, given the city's size, and the actual output. They proceed to estimate a residual ξᴬ, which is the deviation between the predicted total factor productivity (TFP) of a city and the actual TFP. Here, TFP is the portion of output for an economy that is not explained by the total labor force of capital deployment. Wage data, or return to labor, was available, but data to directly measure the capital deployment across cities was not available, and so the authors estimate this quantity by assuming that labor's share of income is 0.7. Gross metropolitan product data was also available, and so all of these values allow TFP to be calculated. Once residuals are estimated to account for the size of a city, there is no obvious pattern as to which cities have higher TFP.

[Melo et al. (2017)](https://doi.org/10.1177/0042098015624850) consider agglomeration at a smaller scale than a full metropolitan region. Considering the 50 largest metros in the United States, they find the elasticity of wages with respect to job density and the number of jobs available within a given travel time are, respectively, 0.072 and 0.096. These results confirm a prediction of the [standard urban model](/2024-11-02-sum.md) that areas with higher access to jobs are more desirable, manifested through higher wages. The two variables of interest are highly correlated, but the fact that job access shows a greater influence on wages than job density suggests that urban planners would be advised to priortize transportation access over density.

[Schläpfer et al. (2014)](https://doi.org/10.1098/rsif.2013.0789) does not consider economic output directly, but rather they examine social interaction, for which mobile phone connectivity is taken to be a good proxy. Recall that in [Bettencourt (2013)](https://doi.org/10.1126/science.1235823), output was assumed to be proportional to social interaction. They find that in Portugal, the 92-day call volume scales with the 1.10 (1.08-1.11) power of city size, whereas in the United Kingdom, the 31-day call volume scales with the 1.10 (1.07-1.14) power of city size. There are various other metrics related to the call data set, all of which show similar scaling properties. One thing especially interesting about the paper is that they find that, for two of a given person’s contacts, the probability that they are themselves connected is independent of city size, which challenges the popular notion that larger cities are more atomizing than small towns.

## The Objection of Causality

[Lobo et al. (2013)](https://doi.org/10.1371/journal.pone.0058407) state the following caveat.

> To be clear, we do not claim that there is a causal relation between urban scaling and urban productivity; scaling reveals a systematic relationship between urban population size and productivity, which itself is a manifestation of a more general relationship between population size and productivity.

[Melo et al. (2017)](https://doi.org/10.1177/0042098015624850) elaborate with two specific problems that challenge empirical measurement of urban scaling. First, there might be unobserved variables that correlate with output, and so a measurement of output in terms of size may actually be capturing some other cause of output. The second problem is reverse causality. It is possible that metropolitan areas that are more productive for reasons unrelated to size, such as favorable geography or good governance, attact more residents, and so rather than population causing output, it is the reverse.

To address the reverse causality issue, Melo et al. note that the most common solution is an instrumental variable analysis between long-lagged measures of urban agglomeration and geographic or geological variables. [Combes et al. (2010)](https://www.nber.org/books-and-chapters/agglomeration-economics/estimating-agglomeration-economies-history-geology-and-worker-effects) apply this approach in a measurement of the elasticity of wages against density in France. Without attempting to correct for unobserved variables or reverse causality, Combes et al. find that the elasticity is about 0.05. They consider possible endogenous sources of a relationship between density and wages: more productive workers may prefer to live in denser areas, and more productive cities may attract more workers. Controlling for all these sources of bias reduces the observed elasticity to 0.027. The authors find a further reduced elasticity to 0.02 when they account for the spillover of agglomeration effects across spatial boundaries.

After all the corrections, [Combes et al. (2010)](https://www.nber.org/books-and-chapters/agglomeration-economics/estimating-agglomeration-economies-history-geology-and-worker-effects) do still find an agglomeration effect, albeit one much more modest than that of the theoretical model of [Bettencourt (2013)](https://doi.org/10.1126/science.1235823). However, it is not clear that Combes et al. account for every conceivable endogenous variable.

## Consequences for Policy

To maximize a nation's wealth, theoretical models and empirical observations suggest that supporting large city development is important. The model of [Bettencourt (2013)](https://doi.org/10.1126/science.1235823) and many other models demonstrate that city size is determined by an equilibrium between the benefits and the costs of agglomeration. There are two paths to increasing city size under Bettencourt's model. The first is to increase the value of agglomeration by reducing the downsides, such as by more effective law enforcement to reduce crime. The second approach is to, as presented by Bettencourt, reduce dissipative power of infrastructure. [Zakharenko (2016)](https://doi.org/10.1016/j.regsciurbeco.2016.09.003), for example, models that the arrival of autonomous vehicles will increase city size by reducing the amount of parking required next to destinations. Under Bettencourt's model, parking can be considered a form of pwer dissipation.

However, planners should be careful not to overestimate the value of agglomeration effects. We have seen that many empirical findings about the elasticity of economic output to population size are less than the theoretical prediction of [Bettencourt (2013)](https://doi.org/10.1126/science.1235823), including Bettencourt's own figures. Furthermore, as shown in [Combes et al. (2010)](https://www.nber.org/books-and-chapters/agglomeration-economics/estimating-agglomeration-economies-history-geology-and-worker-effects), observed agglomeration effects may be significantly less than suggested by a naive regression, when one accounts for the possibilities of reverse causation and unobserved variables. Planners should, to the maximum extent feasilbe, base their decisions on [tangible agglomeration benefits](/2024-12-07-agglomeration-sources.md) alongside hypothetical scaling models.

Finally, planners should consider the goal of maximizing economic output along other social goals, such as environmental concerns, risks that may arise from too heavily concentrating economic activity in a small number of cities, and regional inequities.

## References

Lobo, J., Bettencourt, L., Strumsky, D., West, G. ["Urban scaling and the production function for cities"](https://doi.org/10.1371/journal.pone.0058407). PLoS ONE **8**(3). 2013.

Bettencourt, L. ["The Origins of Scaling in Cities"](https://doi.org/10.1126/science.1235823). Science **340**(1438). June 2013.

Marchetti, C. ["Anthropological Invariants in Travel Behavior"](https://doi.org/10.1016/0040-1625(94)90041-8). Technological Forecasting and Social Change **47**(1), pp. 75-88. September 1994.

Jacobs, J. [*The Economy of Cities*](https://www.penguinrandomhouse.com/books/86059/the-economy-of-cities-by-jane-jacobs/). Vintage, ISBN 9780394705842. February 1970.

Melo, P.C., Graham, D.J., Levinson, D., Aarabi, S. ["Agglomeration, accessibility and productivity: Evidence for large metropolitan areas in the US"](https://doi.org/10.1177/0042098015624850). Urban Studies **54**(1), pp. 179-195. January 2017.

Combes, P.P., Duranton, G., Gobillon, L., Roux, S. ["Estimating agglomeration economies with history, geology, and worker effects"](https://www.nber.org/books-and-chapters/agglomeration-economics/estimating-agglomeration-economies-history-geology-and-worker-effects). In Agglomeration Economics (pp. 15-66). University of Chicago Press. February 2010.

Schläpfer, M., Bettencourt, L.M., Grauwin, S., Raschke, M., Claxton, R., Smoreda, Z., West, G.B., Ratti, C. ["The scaling of human interactions with city size"](https://doi.org/10.1098/rsif.2013.0789). Journal of the Royal Society Interface **11**(98): 20130789. September 2014.

Zakharenko, R. ["Self-driving cars will change cities"](https://doi.org/10.1016/j.regsciurbeco.2016.09.003). Regional science and urban economics **61**, pp. 26-37. November 2016.