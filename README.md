# Emotional Context Analyzer

## Description

This project showcases the transfer learning process. The notebook begins by explaining some of the context of the task — explaining emotional content of Twitter posts — as well as the foundational model, BERT. It then proceeds to show a custom transformer architecture using TensorFlow, which is trained on a Kaggle dataset of Twitter posts. The embeddings from this original exercise are transferred into a foundational model from HuggingFace. This process begins with a few unfrozen layers, but the entire model is enabled for tuning by the end. Finally, a Wilcoxon test is used to prove the statistically significant impact of this exercise on the classification task.

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contribute](#contribute)
- [Tests](#tests)
- [Contact](#contact)

## Installation

```
You will need to install the following dependencies to run the code: 

pip install numpy
pip install pandas
pip install scikit-learn
pip install tensorflow
pip install transformers

```

## Usage
I recommend Python 3.9 to ensure all dependencies work as intended. Anaconda also works for dependencies, but I recommend using a virtual environment with pip.

If you use an Apple Silicon like me, you can use the following article for instructions on configuring your virtual environment. https://developer.apple.com/metal/tensorflow-plugin/

## License

![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Contribute
If interested in further contribution, please contact me at the following:

Github: eddie-diaz-ms
Email: ediaz@smu.edu
