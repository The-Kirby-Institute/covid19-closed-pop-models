# covid19-closed-pop-models

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3825969.svg)](https://doi.org/10.5281/zenodo.3825969)

This project repository is for models of COVID-19 in closed population settings developed by researchers at the [_The Kirby Institute_](https://kirby.unsw.edu.au/). It currently only contains a spreadsheet model of CoV-SARS-2 transmission within prison settings and the subsequent impact of COVID-19. Further models and tools for other closed population settings are in development.

## Maintainers and developers

* Jisoo (Amy) Kwon (akwon@kirby.unsw.edu.au)
* Richard T. Gray (Rgray@kirby.unsw.edu.au)

**For any inquiries, please contact Rgray@kirby.unsw.edu.au** or flag an issue. The spreadsheet model will be updated as required to correct issues or to improve or add features. Please check for updated versions periodically. 

## COVID-19 Incarceration Model

The model of COVID-19 in correctional facilities is contained in the Microsoft Excel spreadsheet `COVID-19_Incarceration_Model-v2.1.xlsx`. This spreadsheet model builds on the spreadsheet developed by [Recidiviz](https://www.recidiviz.org/) (original spreadsheet model available [here](https://github.com/Recidiviz/covid19-dashboard)). It was developed with funding from [Corrective Services NSW](https://www.correctiveservices.justice.nsw.gov.au/) and [Justice Health and Forensic Mental Health Network](https://www.justicehealth.nsw.gov.au/). 

The current version of the COVID-19 Incarceration Model is [version 2.2](https://github.com/The-Kirby-Institute/covid19-closed-pop-models/releases/tag/v2.2) which is an upgrade from the version used in the Advancing Corrections publication (see below for details). In particular, version 2.2 improves the approach used to model vaccination to account for sterilizing immunity.

The aim of the model is to track an outbreak of COVID-19 in a correctional setting and assess the potential impact of prevention strategies and interventions. The main directory contains a blank spreadsheet model ready for use. Example spreadsheets with inputs and outputs are available in the `Examples\` directory. A short manual `COVID-Incarceration-Manual.docx` provides further user instructions and details of the interventions incorporated into the model. 

### Summary of the model 

The model is a simple compartmental deterministic model of SARS-CoV-2 transmission and COVID-19 progression within a correctional setting. It includes inmates, correctional staff, healthcare staff, non-essential visitors, and family visitors. It is designed to be flexible and to compare intervention scenarios. Specific interventions incorporated include reductions in population size, effects social distancing, quarantine at reception, isolation of inmates in cohorts, PPE, screening of staff and visitors, and vaccination. The effects of different variants of SARS-CoV-2 on transmission and disease can also be captured. 

### Other contributors to the incarceration modelling project

* Prof Andrew Lloyd, Kirby Institute, UNSW Sydney
* Dr Neil Bretana, University of South Australia
* Reference group made up of members from Corrective Services NSW and Justice Health and Forensic Mental Health NSW. 

### Publication

The following publication is associated with this project and used Excel files in this repository to generate the results and figures. 

- Kwon, Jisoo A, Neil A Bretaña, Luke Grant, Jennifer Galouzis, Wendy Hoey, James Blogg, Andrew R Lloyd, and Richard T Gray. “The COVID-19 Incarceration Model: A Tool for Corrections Staff to Analyze COVID-19 Outbreak Strategies.” Advancing Corrections, no. 12 (2021): 15.
    - Published results produced using [version 2.0](https://github.com/The-Kirby-Institute/covid19-closed-pop-models/releases/tag/v2.0); doi:[10.5281/zenodo.5502347](https://zenodo.org/record/5502347).
    - [MedRxiv preprint](https://www.medrxiv.org/content/10.1101/2021.02.18.21252032v1) produced using [version 1.4](https://github.com/The-Kirby-Institute/covid19-closed-pop-models/releases/tag/v1.4); doi:[10.5281/zenodo.3923903](https://zenodo.org/record/3923903).
<br></br>
### Disclaimer

The model has been made publicly available for transparency and replication purposes and in the hope it will be useful under the terms and conditions of the GNU General Public License. We take no responsibility for results generated with the spreadsheet and their interpretation but are happy to assist with its use and application. 

