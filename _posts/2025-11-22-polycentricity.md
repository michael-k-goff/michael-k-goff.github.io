---
layout: post
title: 'Polycentricity'
tags: []
comments: true
mathjax: true
author: Michael Goff
---

"Polycentricity" refers to an urban design pattern in which there are several separate centers of employment and commerce, and not a single dominant center. The [monocentric standard urban model](/2014-11-02), also known as the Alonso-Muth-Mills model, holds that cities development around a single core, known as the central business district. Although useful, the standard urban model makes many simplifications, such as the the assumption of monocentricity, that generally do not hold in the real world.

## Polycentricity Defined

A major challenge of assessing the performance of polycentric design is defining the term. [Wiechmann and Siedentop (2018)](https://www.econstor.eu/handle/10419/225827) observe that polycentricity can operate at three scales. The term may refer to multiple commerce subcenters within the same city. It may refer to multiple cities of comparable size within a single metropolitan area, defined as a unified commuter-shed by [Marchetti's constant](/2025-07-05-marchetti). Or it may refer to multiple metropolitan areas within a large region that is not a unified commuter-shed. Uses of the same term for different meanings, as well as different techniques for measuring polycentricity, make it difficult to directly compare results from different works ([Bartosiewicz and Marcińczak 2020](https://doi.org/10.1016/j.cities.2020.102855)).

[Bartosiewicz and Marcińczak (2020)](https://doi.org/10.1016/j.cities.2020.102855) distinguish between morphological polycentrism, which is an even distribution of population throughout an urban region, and functional polycentrism, which is an even distribution of metropolitan functions.

The term "polycentric urban region" is frequently used, such as by [Meijers, Hoogerbrugge, and Cardoso (2018)](https://doi.org/10.1111/tesg.12292) (hereafter referred to as MHC), to refer to a metropolitan area that is a unified commuter-shed but does not have a sharply defined commercial center. [MHC](https://doi.org/10.1111/tesg.12292) use the [Herfindahl-Hirschman index](https://en.wikipedia.org/wiki/Herfindahl%E2%80%93Hirschman_index), which is most commonly used as a measure of firm concentration in an industry for antitrust purposes. If there are N administrative cities in a region, with city i having a share S_i of the region's population, then the Herfindahl-Hirschman index H is defined as

![Herfindahl-Hirschman index](/assets/img/hhi.png){: .mx-auto.d-block :}

If all commercial activity in the region is concentrated in a single city, then H=1. In the other extreme, if all N cities have equal shares of activity, then H=1/N. Thus smaller numbers indicate higher levels of polycentricity, as given by the number of cities and equality in their distribution. [MHC](https://doi.org/10.1111/tesg.12292) choose a cutoff value of 0.56, above which a region is considered to be monocentric, and below which a region is considered to be polycentric.

## The Performance of Polycentricity

[MHC](https://doi.org/10.1111/tesg.12292) ask whether greater integration between the cities in a polycentric urban region improves its performance via [agglomeration economies](/2024-12-07-agglomeration-sources). To do so, it is necessary to develop metrics for both integration and performance.

"Integration" refers to the extent to which the cities of a polycentric urban region act as a coherent, unified city. [MHC](https://doi.org/10.1111/tesg.12292) develop three classes of metrics. Functional coherence is measured by three metrics: speed of road travel, speed of rail travel, and frequency of passenger rail service. Institutional coherence is measured by three metrics: the existence and type of a regional governing body and the length of time it has existed. Cultural coherence is measured by political and linguistic homogeneity.

It is well-established that, all else equal, larger cities tend to perform better than smaller cities due to agglomeration economies, where performance is assessed over several socioeconomic quantities such as GDP per capita. To measure performance, [MHC](https://doi.org/10.1111/tesg.12292) assess metropolitan functions, which include institutions such as universities and research organizations, headquarters of Fortune 500 companies, sports stadiums, opera houses, and other functions. Since larger cities are more likely--relative to population--to contain such metropolitan functions, the authors assess that the presence of these functions is an effective proxy of agglomeration economies.

With this data in hand, [MHC](https://doi.org/10.1111/tesg.12292) perform regressions on urban performance in terms of integration on polycentric urban regions (PURs) in Europe. Here, a PUR is a collection of distinct administrative cities that are close enough together to function as a unified commuter-shed. They find that, in general, more integrated PURs host more metropolitan functions. However, of the various integration measures, frequency of passenger rail service is the only metric that shows a relationship with metropolitan functions at a significance of 0.01. Furthermore, it is not clear that integration *causes* agglomeration strictly from the data presented in [MHC](https://doi.org/10.1111/tesg.12292). Nevertheless, their work offers evidence that, all else equal, integrated regions will benefit more strongly from agglomeration economies than less integrated regions. The research presents a case for various forms of integration--road and rail connectivity, regional governance, and measures to promote cultural integration--as an economic development strategy.

## References

Wiechmann, T., Siedentop, S. ["Polyzentralität"](https://www.econstor.eu/handle/10419/225827)([English Translation](https://www.arl-international.com/sites/default/files/dictionary/2023-01/Polycentricity.pdf)). Akademie für Raumforschung und Landesplanung, Hannover. 2018.

Meijers, E., Hoogerbrugge, M., Cardoso, R. ["Beyond Polycentricity: Does Stronger Integration Between Cities in Polycentric Urban Regions Improve Performance?"](https://doi.org/10.1111/tesg.12292). Tijdschrift voor Economische en Sociale Geografie **109**(1), pp. 1-12. February 2018.

Bartosiewicz, B., Marcińczak, S. ["Investigating polycentric urban regions: Different measures–Different results"](https://doi.org/10.1016/j.cities.2020.102855). Cities **105**:102855. October 2020.