# Climate Risks Academy 2021 - Modelling Lab

Copyright 2021 Daniel Huppmann

This repository is licensed under the Apache License, Version 2.0 (the "License");  
see the [LICENSE](LICENSE) for details. 

[![license](https://img.shields.io/badge/License-Apache%202.0-black)](https://github.com/IAMconsortium/pyam/blob/main/LICENSE)
[![python](https://img.shields.io/badge/python-3.7_|_3.8_|_3.9-blue?logo=python&logoColor=white)](https://github.com/IAMconsortium/pyam)

## Overview

This repository contains solutions for the advanced assignment of the Modeling Lab of
the **Climate Risks Academy 2021** organized by the European University Institute (EUI)
School of Banking and Finance in cooperation with Oliver Wyman.
See [here](https://fbf.eui.eu/climate-risks-academy/) for more information.

## The NGFS Scenario Ensemble (Phase 2)

The exercise uses the scenario ensemble compiled by a cooperation between several
integrated-assessment modelling teams and the
*Network for Greening the Financial System* (NGFS), in particular Phase 2 (June 2021)
of the scenario data.
See [this presentation](https://www.ngfs.net/sites/default/files/medias/documents/ngfs_climate_scenarios_phase2_june2021.pdf)
about the release of Phase 2.

The scenario data is available via the [NGFS Scenario Explorer hosted by IIASA](https://data.ece.iiasa.ac.at/ngfs) 

## The pyam package

<img src="./_static/pyam-logo.png" width="133" height="100" align="right" alt="pyam logo" />

This exercise uses the Python package **pyam**, an open-source community toolbox for
analysis & visualization of scenario data.
The package was developed to facilitate working with timeseries scenario data
conforming to the format developed by the
[Integrated Assessment Modeling Consortium (IAMC)](https://www.iamconsortium.org).
The package is used in ongoing assessments by the IPCC and in many model comparison
projects at the global and national level, including several Horizon 2020 projects.

[Read the docs](https://pyam-iamc.readthedocs.io) for more information!

## Getting started

To run the notebooks on your machine, please install Python version 3.7 or higher.
To install the required packages and dependencies, download or git-clone this repository
and run the following command in the root folder:

```
pip install -r requirements.txt
```