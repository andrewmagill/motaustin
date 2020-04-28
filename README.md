## MOTAustin

Researchers at the Texas Advanced Computing Center, in conjunction with the City of Austin, have published an analysis of pedestrian safety based on video captured at city intersections [1](#austin). The analysis by Xu et al. used a two step process of detection and tracking to track seven classes of objects (person, car, bus truck, bicycle, motorcycle, traffic light). The authors state in their discussion that tracking of pedestrians proved the most difficult task. This is an attempt to improve the analysis with small modifications to the tracking algorithm.

### Requirements

* [Python 3.6](https://wiki.python.org/moin/BeginnersGuide/Download)
* [pip](https://pip.pypa.io/en/stable/installing/) or [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)
* [Jupyter (Notebook or Lab)](https://jupyter.org/install)
* [numpy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [opencv](https://opencv.org/)
* [matplotlib](https://matplotlib.org/3.1.1/index.html)
* [MOTChallenge 17 Data](https://motchallenge.net/data/MOT17/)

### Installation

The requirements can be easily installed with pip or conda.

#### Python/Pip
Use the [venv](https://docs.python.org/3/library/venv.html) module to create a virtual environment and pip install the necessary dependencies

```
$ python3 -venv ~/.envs/motaustin
$ source ~/.envs/motaustin/bin/activate
$ pip install -r requirements.txt
```

#### Conda
**Conda is not supported until opencv 4.3.0+ is available**

Use conda to create a virtual environment and install the necessary dependencies

```
$ conda env create -f environment.yml
$ activate motaustin-env
```

### References

<b id="austin">1.</b> [Xu, W., Ruiz-Juri, N., Huang, R., Duthie, J.C., & Clary, J.J. (2018). Automated pedestrian safety analysis using data from traffic monitoring cameras. SCC '18.](https://dl.acm.org/doi/10.1145/3236461.3241972)
