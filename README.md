# NSF/IGERT Bootcamp, Day 3 --- "Everything Data"

*Instructor:* [Luca Foschini](www.lucafoschini.com) (email: luca@evidation.com) (twitter: @calimagna)

*Format:* Lecture and hands-on

# Goals
- Learn how perform basic data manipulation with python
- See all the things that python can do
- Learn about what makes your code run slow
- Do you really have big data? 

## Recap
  The lecture on data science and tools for reproducibile science thaught by Ben Best can be found here: [here](https://github.com/bbest/ucsb-network-data-science-2016/)

## Data Wrangling and Exploration

  - Python [basics](../Day02_EverythingData/notebooks/02%20-%20Introduction%20to%20Python.ipynb)
  - All Python [can do](..//Day02_EverythingData/notebooks/03%20-%20Libraries%20and%20Integration.ipynb)!
  - Numpy and Pandas (the missing library for [data manipulation](..//Day02_EverythingData/notebooks/04%20-%20Data%20Wrangling.ipynb)
  - Speed [considerations](..//Day02_EverythingData/notebooks/05%20-%20Theory%20and%20Practice.ipynb)

## Memory, cores, I/O

  - [Latency](https://gist.github.com/jboner/2841832): Register, Cache, RAM, Disk (SSD/HDD), network
  - Why is my code running slow? (profile! top/htop)
  - Out of core vs distributed
  - Embarrassingly parallel problems (shell/python parallel)

## How to deal with big data?

  - be smart: (sampling/approximation algorithms, divide-and-conquer)
  - be rich: [rent-a-cloud](https://aws.amazon.com/ec2/pricing/), [Digital Ocean](https://www.digitalocean.com/), [Cloud9](https://c9.io/pricing)
  
## Data Exploration

  - Work with text, networks, time series. Import your dataset into python, and start playing with it.
  - [Interesting notebook gallery](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#introductory-tutorials). Pick one!
  - [Miniproject](..//Day02_EverythingData/notebooks/07%20-%20Miniproject.ipynb)
