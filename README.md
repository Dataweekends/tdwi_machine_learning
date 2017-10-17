# TDWI Machine Learning
Intro To Machine Learning Workshop for TDWI Accelerate, Seattle, October 2017

### [Slides](https://www.slideshare.net/FrancescoMosconi/machine-learning-techniques-best-practices-and-practical-application)

## Quick start guide

#### Clone this repository on your local computer

```
git clone https://github.com/Dataweekends/tdwi_machine_learning.git
```

#### Download and Install Anaconda Python 3.6

https://www.continuum.io/downloads

#### Change to course folder

```
cd tdwi_machine_learning
```

#### Launch Jupyter Notebook

```
jupyter notebook
```

#### Open your browser to

```
http://localhost:8888
```

You are good to go! Enjoy!



### Instructions for Conda environment creation

The following is not necessary if you have a recent version of Anaconda installed on your computer. If you want to create a virtual environment specifically for this tutorial, we provide an [environment configuration file](environment.yml). From the terminal follow these steps:

#### Change to course folder

```
cd tdwi_machine_learning
```

#### Create the course environment

```
conda env create
```

wait for the environment to create, this may take a few minutes

#### Activate the environment (Mac/Linux)
```
source activate tdwi
```

#### Activate the environment (Windows)
```
activate tdwi
```

Check that your prompt changed to

```
(tdwi) $
```

Now you can run jupyter notebook from within the environment.



### Troubleshooting

#### Updating Conda

If you have installed Anaconda a long time ago, you may want to update it by running

```
conda update conda
```

and then

```
conda update anaconda
```
