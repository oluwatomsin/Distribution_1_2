## Title

Stat Package 101

## Description

This project was created to showcase my OOP knowledge and also to
practice how to deploy a python package. The package contains helps you 
in calculation relating to stsatistical distributions. Four distributions were
 chosen for this project which includes; 
* Normal Distribution
* Bernoulli Distribution
* Binomial Distribution
* Poisson Dsistribution.

## Prerequisites

Before you continue, ensure you have met the following requirements:

* You have a basic understanding of statistics.

## Installation:
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Distribution_1_2
```bash
pip install distribution_1_2
```
## Usage:

```python
from Distribution.binomial import Binomial

b = Binomial(3, 0.2)
print(b)

b = b.binomial_distribution_formula(2)
print(b)
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
go to my GitHub page [here](https://github.com/oluwatomsin)
