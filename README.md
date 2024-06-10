# English to Persian Wikipedia Translations of Technical Terms

## Overview

This repository aims to create a comprehensive dataset that maps technical terms and concepts between English and Persian (Farsi) Wikipedia. The focus is primarily on fields such as Computer Science, Artificial Intelligence, Software Engineering, and Bio-Medical Engineering.

## Objectives

- **Mapping Technical Terms**: Identify and map key technical terms and concepts from English Wikipedia to their corresponding entries in Persian Wikipedia.
- **Contextual Information**: Include keywords and descriptions to provide context for each term or concept.
- **Resource Creation**: Develop a resource to aid people in writing seminar papers and theses in Persian, which there is usually strict requirements for using Persian terms. For fields like Computer Science, where there are a ton of English terms and their Persian translations are not always clear, this dataset can relieve some of the pain of finding the right Persian term for a given English term.

## Project Structure

```
en-fa-wikipedia-translations/
│
├── data/
│   ├── dataset.csv
│   ├── dataset.tsv
│   ├── dataset.json
│
├── scripts/
│   ├── query.sparql
│
|── CONTRIBUTING.md
├── .gitignore
├── LICENSE
├── README.md
```

## Accessing The Data

The datasets are readily available in the `data/` directory. Furthermore, you can use the SPARQL query in the `./scripts/query.sparql` file to fetch the data directly from the Wikidata Query Service.

## Dataset Structure

The dataset will include the following fields:

- **English Term**: The term in English.
- **Persian Term**: The corresponding term in Persian.
- **Description (EN)**: A brief description of the term in English.
- **Description (FA)**: A brief description of the term in Persian.
- **Source URL (EN)**: The URL of the English Wikipedia entry.
- **Source URL (FA)**: The URL of the Persian Wikipedia entry.

## TODO

- [ ] Automate the process of fetching the data from the Wikidata Query Service and updating the dataset.
- [ ] Optimize the SPARQL query both in terms of performance and the quality of the results.
- [ ] Review the mappings to correct any potential inconsistencies or unwanted results.
- [ ] Integrate the dataset with other curated datasets for Persian equivalents of technical terms, to create a more comprehensive resource.
- [ ] Add workflow to automatically update the dataset with new terms and mappings.

## Contributing

Contributions are welcome! To contribute, fork the repository and create a new branch. Make your changes and submit a pull request. For more details, see the [CONTRIBUTING](CONTRIBUTING.md) file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions, suggestions, or feedback, feel free to open an issue or contact me at [j.razi@outlook.com](mailto:j.razi@outlook.com).
