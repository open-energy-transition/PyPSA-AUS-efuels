<!--
SPDX-FileCopyrightText:  PyPSA-Earth and PyPSA-Eur Authors

SPDX-License-Identifier: AGPL-3.0-or-later
-->

# PyPSA-AUS-efuels
Repository for the PyPSA-AUS-efuels project

<img src="https://raw.githubusercontent.com/open-energy-transition/oet-website/main/assets/img/oet-logo-red-n-subtitle.png" alt="Open Energy Transition Logo" width="260" height="100" align="right">

This repository is a soft-fork of OET's [PyPSA-Earth](https://github.com/open-energy-transition/pypsa-earth) and contains the entire project `PyPSA-AUS-eFuel` supported by [Open Energy Transition (OET)](https://openenergytransition.org/)<sup>*</sup> and Osel / Sagax Capital, including code and report. The philosophy behind this repository is that no intermediary results are included, but all results are computed from raw data and code. The structure is also inspired by [cookiecutter-project](https://github.com/PyPSA/cookiecutter-project).

This repository is maintained using [OET's soft-fork strategy](https://open-energy-transition.github.io/handbook/docs/Engineering/SoftForkStrategy). OET's primary aim is to contribute as much as possible to the open source (OS) upstream repositories. For long-term changes that cannot be directly merged upstream, the strategy organizes and maintains OET forks, ensuring they remain up-to-date and compatible with upstream, while also supporting future contributions back to the OS repositories.

## Installation
More details on configuration, installation, and debuging is available at [OET's soft-fork](https://github.com/open-energy-transition/pypsa-earth).

## Running the model
- Run a dryrun of the Snakemake workflow by copying the following command:
  ```bash
  snakemake -c1 solve_sector_networks -n
  ```
- Run the Snakemake workflow by copying the following command:
  ```bash
  snakemake -c1 solve_all_networks
  ```

**More details will be added during the project execution.**

----

<sup>*</sup> Open Energy Transition (g)GmbH, Königsallee 52, 95448 Bayreuth, Germany

----
