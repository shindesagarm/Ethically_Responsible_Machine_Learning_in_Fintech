# Ethics in Finance and Machine Learning

## Overview

This project is part of a collaboration between researchers from the [Faculty of Computer Science & Engineering](https://www.finki.ukim.mk/en) at the
Ss. Cyril and Methodius University in Skopje and [Boston University](http://www.bu.edu/).

## Features

The purpose of the project is to compare the ethical principles of finance and machine learning (ML) as part of a broader research related to the use of ethically responsible ML in fintech. The objective is to get insights into the ethical principles of finance which exhibit most influence on ML ethics and vice-versa. The project also aims to use those insights to analyze the [Credit Card Approval](https://archive.ics.uci.edu/ml/datasets/credit+approval) dataset with [XGBoost](https://xgboost.readthedocs.io/en/stable/) using state-of-the-art explainability approaches such as [SHAP](https://shap.readthedocs.io/en/latest/index.html) and Microsoft's [Responsible AI Widgets](https://github.com/microsoft/responsible-ai-widgets).

## Installation

The code is available as Jupyter notebooks. The easiest way to use the notebooks is to upload them to and run them in [Google Colab](https://research.google.com/colaboratory). The notebooks contain imports of the necessary Python libraries. There are no dependencies and no additional modules or libraries need to be installed. The notebooks have also been tested with a local installation of [Anaconda](https://www.anaconda.com/).

## Known Limitations

We suggest to use Anaconda to obtain seamless experience when working with the Explanation and Error Analysis Dashboards of the Responsible AI Widgets. The use of Google Colab exhibits a rather unstable behavior of the dashboards which requires frequest restarts of the Google Colab runtime.

## Authors

- [Maryan Rizinski](https://github.com/rizinski)
- [Hristijan Peshov](https://github.com/hristijanpeshov)
- [Kostadin Mishev](https://github.com/kokimishev)

## License

Apache License 2.0

## Citation

If you use this project in your research, we would appreciate a citation to the following paper:

```bibtex
@article{rizinski2022ethically,
  title={Ethically Responsible Machine Learning in Fintech},
  author={Rizinski, Maryan and Peshov, Hristijan and Mishev, Kostadin and Chitkushev, Lubomir T and Vodenska, Irena and Trajanov, Dimitar},
  journal={IEEE Access},
  volume={10},
  pages={97531--97554},
  year={2022},
  publisher={IEEE}
}
```
