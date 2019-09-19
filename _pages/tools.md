---
layout: splash
title: "SCI-CLAWPS Tools"
permalink: /tools/
author_profile: false
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/fremontweir.jpeg
excerpt: "Here is a list of tools developed by the research group."
---

## The STOchastic Rainstorm Model (STORM)
This is a decision-support tool created to simulate individual rainstorms over a basin or region at high temporal and spatial resolution. This parsimonious model enables simulation of stationary climate based on historical data, or climate change based on step changes and/or trends in key climate variables. The tool is still under development, but can be downloaded from [GitHub](https://github.com/blissville71/STORM). The supporting documentation can be found in this paper:

**Singer, M.B.**, Michaelides, K., Hobley, D.E.J. (2018); STORM 1.0: A simple, flexible, and parsimonious stochastic rainfall generator for simulating climate and climate change, _Geoscientific Model Development_, 11, 3713-3726, doi: [10.5194/gmd-11-3713-2018](https://www.geosci-model-dev.net/11/3713/2018/). [<span style="color:red">pdf</span>](https://www.geosci-model-dev.net/11/3713/2018/gmd-11-3713-2018.pdf)		
   
and the following paper provides an application of the model:

**Singer, M.B.**, Michaelides, K. (2017); Deciphering the expression of climate change within the Lower Colorado River basin by stochastic simulation of convective rainfall, _Environmental Research Letters_, 12:104011, doi: [10.1088/1748-9326/aa8e50](https://iopscience.iop.org/article/10.1088/1748-9326/aa8e50). [<span style="color:red">pdf</span>](https://iopscience.iop.org/article/10.1088/1748-9326/aa8e50/pdf) 

We are currently working on the next version of the model (STORM.v2), which will explicity capture the inherent relationships between rainfall intensity and duration, and it will include a front-end pre-processing code for creating input pdfs. 

 
## The Inverse Barbour Model (ISO-Tool)
This tool is designed to enable users to characterize the oxygen isotopic ratio of source waters used by plants during distinct periods of growth. It employs an inversion of the Barbour model of isotopic fractionation within plants (building on Craig-Gordon theory) to convert a known oxygen isotope ratio in tree ring cellulose into the ratio of its source water, based on climatic and physiological input variables. The model includes a Monte Carlo method for characterizing the uncertainty in this back-calculated ratio. The tool is currently being reviewed for publication, but it can be downloaded from [GitHub](https://github.com/blissville71/InverseBarbourModel). The supporting documentation can be found in this paper:

*Sargeant, C.I., **Singer, M.B.**, Vallet-Coulomb, C. (In Review); Identification of Source-water Oxygen isotopes in trees Toolkit (ISO-Tool) for deciphering historical water use by forest trees, _Water Resources Research_


## Water Balance Model for Drylands
This model is designed to address major shortcomings in the linkages between climate and the water balance within dryland regions. Specifically, this model incorporates spatially and temporally varying rainfall (via STORM--see above), partitioning of runoff and infiltration, transmission losses in dryland channels, and diffuse and focused groundwater recharge. The tool is still under development. It will be presented at the AGU Fall Meeting 2019 (Authors: Quichimbo, Cuthbert, Singer, Michaelides).

