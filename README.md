# PhenomEn - Phenological monitoring to assess Environmental impacts on Swiss agriculture

This repository is a collection of software generated within the research project "PhenomEn" funded by the [Swiss National Science Foundation](https://snf.ch/en/FKhU9kAtfXx7w9AI/page/home) (grant no. IZCOZ0_198091). At the same time, it is also the collection of software supporting the PhD thesis of [Lukas Valentin Graf](https://github.com/lukasValentin) (@lukasValentin).

## Abstract
Several threats connected to climate change are decreasing the productivity of currently established crops. While we have a conceptual understanding of the interaction of climate and growing patterns, we are in most cases unable to provide quantitative estimates of the magnitude of phenological shifts. Moreover, much of what we know about plant-environment-management interactions comes from controlled experiments that neglect the diversity of our heterogeneous landscapes, where the environment interacts with plant growth. However, understanding these interactions is key to develop short- and long-term adaptation strategies that improve the resilience and sustainability of current farming practices by using appropriate crop rotations as well as crop varieties (genotypes) adapted to the local conditions and by applying the right treatments at the right place, time and intensity.

The PhenomEn project will use the “landscape as a laboratory” and develop an approach that uses remote sensing technologies and geo information science to bridge the gap between ecology and agricultural research. Thereby, it will improve our understanding of plant-​environment interaction under “real world conditions” in the context of agriculture. By building a geospatial phenological database we will examine how combinations of environmental factors can mitigate or amplify climatic threats.
The project will be supported by the activities of the COST action “[Optical synergies for spatiotemporal SENsing of Scalable ECOphysiological traits](https://www.senseco.eu/)" (SENSECO; CA17134) that aims to close spatial and temporal gaps in ecosystem monitoring by improving spatial scaling approaches and time-​series processing.

## Software

The software generated in the project, i.e., during the PhD thesis of [Lukas Valentin Graf](https://github.com/lukasValentin), is listed as [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) in this repository. Clicking on the directories will redirect you to the actual Github repositories.

The table below lists the single sub-modules, i.e. software components created, their main purpose and license.

| Submodule | Main purpose | Scientific Publication | License |
| --------- | ------------ | ---------------------- | ------- |
| [eodal](https://github.com/EOA-team/eodal) | The Earth Observation Data Analysis Library (EOdal) is the base software to work with (remotely sensed) Earth Observation (EO) data. | [Graf et al., 2022, COMPAG](https://doi.org/10.1016/j.compag.2022.107487) | [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html) |
| [s2toarup](https://github.com/EOA-team/s2toarup) | Uncertainty propagation from Sentinel-2 top-of-atmosphere radiometry into spectral indices, functional traits, and land surface phenology. | [Graf et al., 2023, IEEE J-STARS](https://doi.org/10.1109/JSTARS.2023.3297713) | [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)