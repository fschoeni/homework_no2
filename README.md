# Homework #2 for the Course Open Source Energy System Modeling @ TUW 

Copyright 2020 Franziska Schöniger

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Description

Repository for the second homework during the course (SS2020)

The project was created for the purpose of the lecture "Open Source Energy System Modeling" in spring 2020 held as an online format. 
In this work, I conduct analyses with the [IAMC 1.5°C Scenario Explorer](https://data.ene.iiasa.ac.at/iamc-1.5c-explorer) to derive certain findings.
This analysis is based on the 2.0 release of the scenario ensemble.

## Overview

The notebooks included in this repository implement the categorisation of
scenarios by climate impact and generate figures, tables, summary statistics,
and assessment indicators used in the **IPCC Special Report on Global Warming
of 1.5°C** ([SR15](http://www.ipcc.ch/report/sr15/)).

A rendered version of this repository and the notebooks are available at
[data.ene.iiasa.ac.at/sr15_scenario_analysis](https://data.ene.iiasa.ac.at/sr15_scenario_analysis).

## Scenario ensemble download

The scenario ensemble used for this assessment 
and the metadata table of scenario categorisation and quantitative indicators
are available for download via
the [IAMC 1.5°C Scenario Explorer](https://data.ene.iiasa.ac.at/iamc-1.5c-explorer).

The scenario data is released under a custom license.
If appropriate reference is made to the data source, it is permitted to use
the data for scientific research and science communication.
However, redistribution of substantial portions of the data is restricted.

Please read the guidelines and legal code
at [data.ene.iiasa.ac.at/iamc-1.5c-explorer/#/license](https://data.ene.iiasa.ac.at/iamc-1.5c-explorer/#/license)
before redistributing this data or adapted material.

When using the scenario data for any analysis, figures or tables,
please clearly state the release version of the scenario ensemble.

## Scientific references

I use the **scenario ensemble data** for own analysis and **Jupyter notebooks containing figure plotting and analysis scripts**, based on previous work from:
> Daniel Huppmann, Elmar Kriegler, Volker Krey, Keywan Riahi, Joeri Rogelj,
> Katherine Calvin, Florian Humpenoeder, Alexander Popp,
> Steven K. Rose, John Weyant, et al.,  
> *IAMC 1.5°C Scenario Explorer and Data hosted by IIASA*.  
> Integrated Assessment Modeling Consortium & International Institute for Applied Systems Analysis, 2019.  
> doi: [10.5281/zenodo.33633459](https://doi.org/10.5281/zenodo.3363345) |
> url: [data.ene.iiasa.ac.at/iamc-1.5c-explorer](https://data.ene.iiasa.ac.at/iamc-1.5c-explorer)

> Daniel Huppmann et al.,
> *Scenario analysis notebooks for the IPCC Special Report on Global Warming of 1.5°C*. 2018.  
> doi: [10.22022/SR15/08-2018.15428](https://doi.org/10.22022/SR15/08-2018.15428) |
> url: [github.com/iiasa/ipcc_sr15_scenario_analysis](https://github.com/iiasa/ipcc_sr15_scenario_analysis)

Please refer to the [AUTHORS](AUTHORS.md) document for the full list of authors
of the scenario ensemble and the notebooks in this repository.

You can download these citations and the references
for all studies that submitted scenarios to the ensemble
as [Endnote (enl)](bibliography/iamc_1.5c_scenario_data.enl),
[Reference Manager (ris)](bibliography/iamc_1.5c_scenario_data.ris),
and [BibTex (bib)](bibliography/iamc_1.5c_scenario_data.bib) format.

## Dependencies

The notebooks included in this repository depend on the *pyam* package,
an open-source Python package for IAM scenario analysis and visualization
developed by Matthew Gidden ([@gidden](https://github.com/gidden))
and Daniel Huppmann ([@danielhuppmann](https://github.com/danielhuppmann/)).

See [pyam-iamc.readthedocs.io](https://pyam-iamc.readthedocs.io)
for installation instructions and the full documentation of *pyam*.
The source code is available at [github.com/IAMconsortium/pyam](https://github.com/IAMconsortium/pyam).
