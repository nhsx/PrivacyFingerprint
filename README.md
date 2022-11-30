# Privacy Fingerprint
## NHS England Digitial Analytics and Research Team - PhD Internship Project

### About the Project

[![status: experimental](https://github.com/GIScience/badges/raw/master/status/experimental.svg)](https://github.com/GIScience/badges#experimental)

This repository holds the public view of code and materials for the Privacy Fingerprint -  a structured calculation of unstructured text privacy

The NHS deal with huge amounts of sensitive data, structured and unstructured, which is private. Patient records, staff records, treatments, etc. all contribute to this corpus. Often this data is of value to researchers seeking new approaches to treatment, etc. but sharing such data with them is often challenging. This work seeks to quantify the privacy risk around their data (or subsets thereof). A ‘privacy fingerprint’ or ‘privacy risk score’ is desired to help articulate and quantify privacy risks. Of note, this is NOT a tool to anonymise or de-identify records – there are existing vendors of tools that seek to do this – but how can that risk be quantified in the first place? How might that risk score change after applying a particular privacy enhancing tool?
 
This goes beyond first order PII – identifying gender, age or even name is relatively straightforward, but particular diseases such as rare ones, their symptoms, familial relationships, etc. may not be part of an existing ontology and rather entered as free text. A good example of this is mental health records that often are in a long story format, rather than existing SNOMED codes. The tool will need to judge privacy and derive a risk score based on factors such as these; and explain this score, perhaps through categories.

_**Note:** Only public or fake data are shared in this repository._

### Project Stucture

PROJECT ONGOING SO NO CODE AVAILABLE YET
- The main code is found in the root of the repository (see Usage below for more information)
- The accompanying [report](./reports/PrivacyOfUnstructuredDataReport_Nov2022.pdf) is also available in the `reports` folder
- More information about the code usage can be found in the [model card](./model_card.md)

### Built With

[![Python v3.8](https://img.shields.io/badge/python-v3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
- {LIST OF MAIN PACKAGE VERSIONS}

### Getting Started

#### Installation

To get a local copy up and running follow these simple steps.

To clone the repo:

`git clone https://github.com/nhsx/privacyfingerprint`

To create a suitable environment:
- ```python -m venv _env```
- `source _env/bin/activate`
- `pip install -r requirements.txt`

{ADDITIONAL TECHNICAL SUPPORT AND NEEDS} 

### Usage
{DESCRIPTION OF CODE}

#### Outputs
{LIST AND DESCRIPTION OF OUTPUTS}

{NOTES ON REPRODUCIBILITY OF RESULTS}

#### Datasets
{DESCRIPTION AND LINKS TO DATASETS}

{LINK TO FAKE DATA TO SUPPORT INITAIL CODE RUNS}

### Roadmap

See the {LINK TO REPO ISSUES} for a list of proposed features (and known issues).

### Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

_See [CONTRIBUTING.md](./CONTRIBUTING.md) for detailed guidance._

### License

Unless stated otherwise, the codebase is released under [the MIT Licence][mit].
This covers both the codebase and any sample code in the documentation.

_See [LICENSE](./LICENSE) for more information._

The documentation is [© Crown copyright][copyright] and available under the terms
of the [Open Government 3.0][ogl] licence.

[mit]: LICENCE
[copyright]: http://www.nationalarchives.gov.uk/information-management/re-using-public-sector-information/uk-government-licensing-framework/crown-copyright/
[ogl]: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/

### Contact

To find out more about the [Digitial Analytics and Research Team](https://www.nhsx.nhs.uk/key-tools-and-info/nhsx-analytics-unit/) visit our [project website](https://nhsx.github.io/AnalyticsUnit/projects.html) or get in touch at [analytics-unit@nhsx.nhs.uk](mailto:analytics-unit@nhsx.nhs.uk).

<!-- ### Acknowledgements -->

