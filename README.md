# Build a Machine Learning Pipeline for Airfoil Noise Prediction

![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fpregismond%2Fbuild-ml-pipeline-airfoil-noise-prediction&label=Visitors&countColor=%230d76a8&style=flat&labelStyle=none)
[![License](https://img.shields.io/badge/License-Apache_2.0-0D76A8?style=flat)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.7.12](https://img.shields.io/badge/Python-3.7.12-green.svg)](https://shields.io/)

## Disclaimer

This repository contains my submission for the ***Final Project: Build a Machine Learning Pipeline for Airfoil Noise Prediction***. The original files were provided by the IBM Skills Network as part of the **[Machine Learning with Apache Spark](https://www.coursera.org/learn/machine-learning-with-apache-spark)** course on Coursera. I have made modifications to fulfill the project requirements.

### Usage

* You are welcome to use this repository as a reference or starting point for your own project.

* If you choose to fork this repository, please ensure that you comply with the terms of the Apache License and give proper credit to the original authors.

## Project Scenario

As a data engineer at an aeronautics consulting company, we take pride in our ability to efficiently design airfoils for use in both planes and sports cars. While our data scientists excel at Machine Learning, they rely on me to handle ETL (Extract, Transform, Load) tasks and construct ML pipelines.

## Objectives

* Clean the dataset
* Create a Machine Learning pipeline
* Evaluate the model's performance
* Persist it for future use

## Datasets

For this project, we will use a modified version of the NASA Airfoil Self-Noise dataset `NASA_airfoil_noise_raw.csv`, which is available in this repository.

The original dataset can be found here: NASA Airfoil Self-Noise dataset. https://archive.ics.uci.edu/dataset/291/airfoil+self+noise

The dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.

Diagram of an airfoil (Source: IBM Skills Network).

![Airfoil with flow](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-BD0231EN-Coursera/images/Airfoil_with_flow.png)

Diagram showing the Angle of attack (Source: IBM Skills Network).

![Airfoil angle of attack](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-BD0231EN-Coursera/images/Airfoil_angle_of_attack.jpg)

## Notes

The metric values presented in the `Final_Project.ipynb` notebook can vary across different Python versions. These variations may occur due to changes in underlying libraries, algorithms, or default behavior. To ensure successful completion of the **Quiz: Final Project - Evaluation Submitted**, it is essential to complete this project using the Python version available in the Skill Network Labs (SN Labs) environment. Python 3.7.12.

## Setup

Install the required libraries using the provided `requirements.txt` file. The command syntax is:

```bash
python3 -m pip install -r requirements.txt
```

Download the required `NASA_airfoil_noise_raw.csv` file using the terminal command:

```bash
wget https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-BD0231EN-Coursera/datasets/NASA_airfoil_noise_raw.csv
```

Create folder to save model:

```bash
mkdir -p Final_Project
```

Execute the code using the command:

```bash
python3 Final_Project.py
```

## Learner

[Pravin Regismond](https://www.linkedin.com/in/pregismond)

## Acknowledgments

* IBM Skills Network © IBM Corporation 2023. All rights reserved.
