[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fbartolic/petnica_summer_school_2019/master)

# 2019 Petnica Summer School on Astrophysics 
Supporting materials for my lectures on exoplanets at the 2019 Summer School on Astrophysics in Petnica, Serbia.

# Schedule
## Day 1 - An overview of exoplanet science  and the two-body problem
Saturday, 27th July, 2019
- [Slides on exoplanets](https://github.com/fbartolic/petnica_summer_school_2019/blob/master/day_1/slides.pdf)(warning, these are ~30MB) 
- [Notes on the two-body problem](https://dynalist.io/d/ZXJTHF0rVkomeP0grFY5uqPK)

## Day 2 - Hands-on session on planetary dynamics and N-body simulations with REBOUND 
Sunday, 28th July, 2019
- [Introduction to N-body simulations with REBOUND](https://github.com/fbartolic/petnica_summer_school_2019/blob/solutions/day_2/intro_to_rebound.ipynb)
- [Exercise on the Kozai mechanism](https://github.com/fbartolic/petnica_summer_school_2019/blob/solutions/day_2/kozai_oscillations.ipynb)
- [Exercise on stability of circumbinary planets](https://github.com/fbartolic/petnica_summer_school_2019/blob/solutions/day_2/circumbinary_planets.ipynb)

## Day 3 - Data analysis and a hands-on session on fitting transit lightcurves using MCMC
Monday, 29th July, 2019
- [Notes on data analysis](https://dynalist.io/d/AFgXJclmrqBjmvk1lvUsTy2v)
- [Exercise on fitting a transit light curve with the Metropolis algorithm]()

# Instructions for running the Jupyter notebooks
## Running the notebooks using Binder
You don't need to install anything locally to run Jupyter notebooks with Binder, all 
you need is a web browser and decent wifi. 
Simply click on the "launch binder" icon on the top of these 
notes. It may take some time to start.

## Running the notebooks locally
If you have prior experience with Jupyter notebooks and Python, you can run the notebooks after
installing the following additional packages:
```
pip install numpy matplotlib rebound 
```

## Solutions to exercises
To check the solutions for the exercises, change the repository branch from "master" to 
"solutions" and navigate to the relevant directories. The Jupyter notebooks should render
in your browser.
