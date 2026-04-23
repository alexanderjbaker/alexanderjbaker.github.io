---
title: 'Tropical cyclones in state-of-the-art climate models'
date: 2024-08-28
permalink: /posts/2024/08/tropical-cyclones-in-state-of-the-art-climate-models/
tags:
  - tropical cyclones
---


Tropical cyclones, including hurricanes and typhoons, rank among the most costly natural hazards. Recent research has revealed an increasing trend in the destructiveness of tropical cyclones over the last few decades, and highlighted the fact that socioeconomically underprivileged populations are disproportionately exposed to their impacts. Simulating realistic tropical cyclones is therefore a vital ambition in weather and climate modelling.

> Tropical cyclones are born from ‘seeds’—tropical waves or rotating clusters of individual thunderstorms—in a process lasting from hours to weeks. This occurs at low latitudes over warm tropical oceans and, usually, at least a thousand kilometres from the equator, where planetary rotation is sufficient to aggregate convective activity into a coherent vortex. Once formed, tropical cyclones mature, increasing in intensity. Typically, they propagate westward and poleward before reaching the midlatitudes, where they weaken over a cooler ocean surface or transform into frontal weather systems.

The physical processes that govern a tropical cyclone’s lifecycle are relatively well understood, but many of these processes occur at scales below those resolved by global climate models. Simulated tropical cyclones intensify too slowly and fail to reach the highest category-four and -five strengths observed. Increasing the resolution of models may improve realism. In the ongoing [nextGEMS project](https://nextgems-h2020.eu/), two climate models are being developed to run at resolutions of around five kilometres—an order-of-magnitude improvement over typical models. Such simulations require significant computational resources, so for now model runs are around five years. Nonetheless, the data being produced offer up opportunities to explore state-of-the-art model capabilities.

In [a new study](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2024GL109841) published in *Geophysical Research Letters*, my colleagues and I used an algorithm to identify tropical cyclones in nextGEMS data, and analysed a range of simulated tropical cyclone characteristics. Here, I’ll describe our findings for two key ones: the frequency of tropical cyclones and how quickly they intensify—both highly relevant to cyclone predictability and societal impacts.

Simulated tropical cyclone frequency is sensitive to both model resolution and model physics. We compared the observed annual-mean number of tropical cyclones with that simulated by nextGEMS models (Figure 1). In one model, the [Integrated Forecasting System (IFS)](https://www.ecmwf.int/en/forecasts/documentation-and-support/changes-ecmwf-model), the annual number is closer to observations at higher atmospheric resolutions. Tropical cyclone frequency also changes with ocean model and resolution. Higher counts are seen in an IFS simulation at 9 km resolution in the atmosphere coupled to a high-resolution ocean model (the [Finite-Element Sea Ice-Ocean Model (FESOM)](https://fesom.de/) at a resolution of 5 km) than that same atmosphere coupled to lower-resolution ocean (the [Nucleus for European Modelling of the Ocean (NEMO)](https://www.nemo-ocean.eu/) at a resolution of 0.25 º).

A different climate model, the [Icosahedral Non-hydrostatic Weather and Climate (ICON)](https://www.icon-model.org/) model, shows sensitivity to model physics, rather than to changes in resolution (Figure 1). Simulated cyclone frequency was initially too high (see “cycle 2”), but is closer to observations following model improvements (see “cycle 3”). Overall, both IFS and ICON perform better globally than for the Northern Hemisphere, suggesting that further model improvements are still needed to capture some of the regional details of tropical cyclone activity.

![Figure 1](/images/blog/2024-08-28_fig1.jpg)
***Figure 1*** | *Annual-mean tropical cyclone frequency (“nTC”) in observations (“IBTrACS”) over the period 1980–2022 (black) and nextGEMS simulations performed in model-development cycles 2 and 3. Bars represent global frequency and hatched areas represent the Northern Hemisphere. The atmospheric resolution is indicated above each bar.*

The rate at which tropical cyclones intensify increases with finer atmospheric resolution (Figure 2). At low resolution (e.g., IFS at 28 km), even the most intense cyclones mature too slowly and reach a peak wind speed that is significantly lower than that observed in the real world. When resolution is increased, however, the intensification rate starts to resemble observations much more closely at resolutions of 4.4 km (IFS) and 5 km (ICON). These simulations also contain examples of tropical cyclone rapid intensification, which typical models do not represent. Rapid intensification cases [have become more frequent over recent decades](https://alexbakey.wordpress.com/2022/11/13/upward-global-trends-in-tropical-cyclone-rapid-intensification/), and forecasting these events is frequently error prone. Finer resolution is likely a key ingredient in understanding trends and improving forecasts.

![Figure 2](/images/blog/2024-08-28_fig2.jpg)
***Figure 2*** | *Tropical cyclone intensity in the days before and after their peak intensity (indicated by the grey, dashed line) in IBTrACS observations over the period 1980–2022 (black) and nextGEMS simulations. Two measures of cyclone intensity are shown: (a) maximum wind speed (“vmax”) and (b) minimum central pressure (“pmin”). This analysis was performed for the strongest ten percent of both observed and simulated cyclones.*

Our understanding of how climate change may impact tropical cyclones relies a lot on a generation of models whose resolutions are too coarse to capture critical hazards, such as rapid intensification. Therefore, Intergovernmental Panel on Climate Change assessments ascribe little to no confidence in the projected changes in such phenomena. State-of-the-art climate modelling may help reduce uncertainty. Our paper provides key evidence that tropical cyclone realism improves significantly with an atmospheric resolution of a few kilometres. In early 2024, the nextGEMS modelling teams completed simulations for longer periods: 1990–2010 and 2020–2050. These new data will help us better understand processes occurring in intense tropical cyclones and their behaviour in a warming climate. ♦

### Author’s note

‘Cycle 2’ and ‘cycle 3’ refer to phases of model development in nextGEMS during 2022–3. IFS is developed by the European Centre for Medium-Range Weather Forecasts. ICON is developed by the Max-Plank Institute for Meteorology. An edited version of this blog was originally published on [*nextGEMS News*](https://nextgems-h2020.eu/advancing-tropical-cyclone-simulations-for-improved-climate-predictions-and-resilience/).

### References

Baker, A. J., Vannière, B., and Vidale, P. L. [On the realism of tropical cyclones simulated in global storm-resolving climate models.](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2024GL109841) *Geophysical Research Letters* **51**, e2024GL109841.

