[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/schlende/practical-pandas-projects/master)

# Practical pandas projects

[pandas](https://pandas.pydata.org/) is a python library for doing exploratory data analysis.

There are [great docs](https://pandas.pydata.org/pandas-docs/stable/) and [lots of online tutorials](https://pandas.pydata.org/pandas-docs/stable/getting_started/tutorials.html) teaching the basics, but I've seen a lot of people asking what they can work on after they've gone through the tutorials.

My aim here is to create a list of project ideas that are exciting and practical.

Most projects include:

* An explanation of why the dataset is interesting
* Ideas for questions the data can answer
* A bit of sample data you can play with (in some cases)
* Instructions for how to get data

## The project ideas

### Market research

* [Figure out which products sell best on Etsy](notebooks/etsy-listing-dataset.ipynb)
* [Figure out what apps to build using Google Play data](notebooks/google-play-apps.ipynb)
* [Find products to sell on Amazon](notebooks/amazon-products.ipynb)
* Find freelance opportunities using Fiverr data
* Search for products you could build on Creative Market

### Website metrics

* [Track your business KPIs with your webserver's log data](notebooks/webserver-log-data.ipynb)

### Government data

* [Understanding global market trends with import / export data](notebooks/usgov-import-export.ipynb)

### Content marketing

* Munge data to create sharable infographics
* Figure out what kind of content gets shared on Facebook

### Measuring Yourself

* Tracking your fitness
* Tracking your productivity
* Tracking your phone usage

# How to use the sample data

The easiest way to is to use run the notebooks online using Binder. [Click this link](https://mybinder.org/v2/gh/schlende/practical-pandas-projects/master) and wait for Binder to load. You'll be able to start exploring the data without having to install any dependencies on your computer.

Want to run the notebooks yourself on your computer?

You'll need iPython notebook and pandas.

Open a terminal and run:

    git clone https://github.com/schlende/practical-pandas-projects.git

    pip install jupyter
    pip install -r requirements.txt

    cd practical-pandas-projects
    jupyter notebook


A tab should open in your browser at ```http://localhost:8888```


# Contrubute
Want to contribute your own ideas? Send me an email or make a pull request!


# License

MIT