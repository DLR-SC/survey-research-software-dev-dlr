<!--
SPDX-FileCopyrightText: 2020 German Aerospace Center (DLR)
SPDX-License-Identifier: CC-BY-4.0
-->

# Role and practice of research software development at DLR
The repository contains the results of a survey concerning
the role and practice of research software development at
the German Aerospace Center (DLR). The survey started 
end of November 2018 and ended mid-February 2019. We received
773 answers which gave us interesting insights concerning developer
demographics, tool usage, documentation, testing as well as
software citation at DLR.

In this repository you can find:
- [the survey questionnaire](01_survey-questions/questions.md),
- [the anonymized survey results](02_survey-results/data.csv) as well as
- [the analysis of the survey results](03_survey-analysis).

## Running the analysis code
The analysis has been performed on Windows 10 using Python 3.6.10 and Jupyter notebook.
In addition, the analysis code makes use of the libraries:
- [pandas](https://pandas.pydata.org) (BSD 3-Clause License),
- [matplotlib](https://matplotlib.org) (Matplotlib License),
- and [seaborn](https://seaborn.pydata.org/) (BSD 3-Clause License).

The concrete versions of these dependencies are captured
in the [requirements.txt](requirements.txt) file.

### Installation
- Install Python >= 3.6
- Install the dependencies via: `pip install -r requirements.txt`

### Run the Jupyter notebook(s)
- Start Jupyter: `jupyter notebook`
- Your browser should start and you can select the corresponding analysis notebook.

## Citation
If you use this work in a research publication, please cite the
specific version that you used using the citation metadata on Zenodo
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3611306.svg)](https://doi.org/10.5281/zenodo.3611306).

You can find an overview about the different versions of the material
 in the [changelog](CHANGELOG.md).

## License
Copyright © 2020 German Aerospace Center (DLR)

This work is licensed under multiple licenses:
- The survey questionnaire, the survey result data set, all written content, 
 and all images are licensed under [CC-BY-4.0](LICENSES/CC-BY-4.0.txt).
- The analysis source code is licensed under [MIT](LICENSES/CC-BY-4.0.txt).

For more accurate information, please see the individual files.

## Contributors
- Lynn von Kurnatowski
- Tobias Schlauch
