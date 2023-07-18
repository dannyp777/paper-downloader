![Static Badge](https://img.shields.io/badge/Project%20Status-Alpha-yellow)

# Paper Downloader
A powerful, Python-based utility for automating research paper downloads from ArXiv, Semantic Scholar, and Google Scholar.

## Introduction
Paper Downloader is a Python application curated to alleviate the human effort involved in sourcing and downloading research papers. The application fetches, filters, and systematically downloads scholarly research papers based on a predetermined set of topics: Artificial Intelligence, Machine Learning, Natural Language Processing, Large Language Models, and Prompt Engineering. Papers within the last six months are targeted for collection.

Key features:
- Interactive command-line/shell interface.
- Configurable API endpoints and search query terms.
- Respectful of API rate limits.
- Avoids downloading duplicate papers.
- Employs optional load balancing to facilitate faster downloads.
- Runs under a Unix/Linux shell.

## Installation
Please ensure Python 3 and conda are installed on your system. Then set up your environment and install necessary dependencies with the following commands:

```
/bin/bash
git clone https://github.com/dannyp777/paper−downloader.git 
cd paper-downloader
```

###Configure the Conda environment###
```
/bin/bash
conda create −−name paper−downloader python=3.8 
conda activate paper-downloader
```
###Install poetry###
```
/bin/bash
pip install poetry
poetry install
```
## Usage
Use the shell script to run the application, passing as arguments any search query terms desired:

`sh $ ./download-papers.sh <search terms...>`

Alternatively, supply search query terms from an input stream.

API endpoints and search parameters can be configured via a YAML, TOML, or LUA configuration file.

## Contributing
Pull requests are welcome. For major changes, open an issue first to discuss the change you'd like to make, and please ensure that tests are updated as appropriate.

## Disclaimer
This application was developed with the technical assistance of Phind.com through their Pair Programming service with GPT4 LLM.

## License
This project is licensed under the [GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html).
