# How to measure inventive speed? A new patent activity assessment dimension. Dataset
This repository contain dataset description and links to dataset used in paper «How to measure inventive speed? A new patent activity assessment dimension»

## Table of Contents
- [Dataset Card Creation Guide](#dataset-card-creation-guide)
  - [Table of Contents](#table-of-contents)
  - [Dataset Description](#dataset-description)
    - [Dataset Summary](#dataset-summary)
    - [Languages](#languages)
  - [Dataset Structure](#dataset-structure)
    - [Data Instances](#data-instances)
    - [Data Fields](#data-fields)
    - [Data Splits](#data-splits)
  - [Dataset Creation](#dataset-creation)
    - [Curation Rationale](#curation-rationale)
    - [Annotations](#annotations)
  - [Additional Information](#additional-information)
    - [Dataset Curators](#dataset-curators)
    - [Citation Information](#citation-information)
  - [Download Links](#download-links)
  - [Contact](#contact)

## Dataset Description

### Dataset Summary

This dataset contains approximately 64,000 JSON-formatted bibliography data entries used in the final computations of the paper titled "How to measure inventive speed? A new patent activity assessment dimension." The dataset includes information about patents and their associated metadata.

### Languages

The dataset is predominantly in English and presents patent-related information for analysis.

## Dataset Structure

### Data Instances

An illustrative instance from the dataset is as follows:

```json
{
  "title_en": ["Area mapping employing reference clusters for high quality noninteger resolution conversion with enhancement"],
  "priorities": ["US45137695A 1995-05-26"],
  "publication_date": ["1997-11-18"],
  "abstract_en": ["The method and apparatus presented here elevate input image resolution to noninteger multiples of the original. Employing clustered arrangements of output pixels, each pixel is assigned a reference value derived from input signal levels. A template-based enhancement filter refines signal levels before they manifest as high-resolution images."],
  "ci_cpci": ["G06T3/4023 (EP,US)", "H04N1/40068 (EP,US)"],
  "ipc_icai": ["G06T3/40", "G06T5/00", "H04N1/387", "H04N1/393", "H04N1/40"],
  "patent_number": ["US5689343A"],
  "applicants": ["XEROX CORP"],
  "inventors": ["LOCE ROBERT P", "JODOIN RONALD E", "LIN YING-WEI"]
}
```

### Data Fields

Explore the dataset's patent-related insights through meticulously curated data fields:

- `title_en`:  Title of the patent in English
- `priorities`: Priority date marking patent inception
- `publication_date`: Date of patent publication
- `abstract_en`: Abstract describing the patent in English
- `ci_cpci`: Cooperative Patent Classification and Cooperative Patent Central Index codes
- `ipc_icai`: International Patent Classification and International Classification of Alliances and Interests codes
- `patent_number`: Patent number
- `applicants`: Applicants of the patent
- `inventors`: Inventors of the patent

## Dataset Creation

### Curation Rationale

The dataset was curated to support the research detailed in "How to measure inventive speed? A new patent activity assessment dimension."

### Annotations

The dataset does not include additional annotations beyond the initial data collection.

## Additional Information

### Dataset Curators

The dataset's curation was integral to the research spotlighted in "How to measure inventive speed? A new patent activity assessment dimension."

### Citation Information

When utilizing this dataset, kindly acknowledge its contribution through the following citation:

```
@article{article_id,
  author    = {Aleksei L. Kalinichenko, Nikita A. Paplavsky, Ivan V. Oseledets},
  title     = {How to measure inventive speed? A new patent activity assessment dimension.},
  journal   = {Research Policy},
  year      = {2023}
}
```


## Download Links

Access the dataset through the following download links:

- [Google Drive](URL_PLACEHOLDER_1)
- [Dropbox](URL_PLACEHOLDER_2)

## Contact
If you have any questions or inquiries related to the dataset, please don't hesitate to contact Nikita.Paplavsky@skoltech.ru .
