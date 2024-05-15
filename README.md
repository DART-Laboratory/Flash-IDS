# FLASH 

Welcome to the FLASH repository. Here, we offer the implementation details of the method introduced in our research paper titled "_FLASH: A Comprehensive Approach to Intrusion Detection via Provenance Graph Representation Learning_". Our paper can be found at this [Link](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a139/1Ub23WQw20U).

## Prerequisites
To run Flash you need to install Jupyter Notebook. More detailed instructions on installing and running Jupyter Notebooks can be found at this [Link](https://jupyter.org/install).

## Installation
We have provided a requirements.txt file detailing the specific dependency versions. Use the following command to install the required libraries.
```bash
pip install -r requirements.txt
```

## Datasets
Flash is evaluated on open-source datasets from Darpa and the research community. You can access these datasets using the following links.

### Darpa OpTC
```bash
https://github.com/FiveDirections/OpTC-data
```

### Darpa E3
```bash
https://drive.google.com/drive/folders/1fOCY3ERsEmXmvDekG-LUUSjfWs6TRdp
```

### Streamspot
```bash
https://github.com/sbustreamspot/sbustreamspot-data
```

### Unicorn
```bash
https://github.com/margoseltzer/shellshock-apt
```
## Code Structure
The parsers for each dataset are integrated within their respective Jupyter Notebooks. For every dataset, there is a dedicated Notebook designed for evaluation. These Notebooks handle the downloading, parsing, and executing evaluations on their respective datasets. We have provided pre-trained model weights to run evaluations. Each notebook has parameters to control different components of the system. More detailed instructions are given in the Notebooks. After running these Notebooks, the results will be displayed at the end of each execution.

## Contributing
We welcome all feedback and contributions. If you wish to file a bug or enhancement proposal or have other questions, please use the Github Issue. If you'd like to contribute code, please open a Pull Request.

## BibTeX
```
@inproceedings{flash2024,
  title = {FLASH: A Comprehensive Approach to Intrusion Detection via Provenance Graph Representation Learning},
  author = {Rehman, Mati Ur and Ahmadi, Hadi and Hassan, Wajih Ul},
  booktitle = {IEEE Symposium on Security and Privacy (S\&P)},
  year = {2024},
}
```
