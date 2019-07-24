---
title: "Intro and Preparation for Oceanhackweek"
teaching: 15
exercises: 0
questions:
- "Will my laptop work for this hackathon?"
- "What version of Python should I install?"
- "What tools do I need to participate?" 
objectives:
- "Getting participants ready for running code in the cloud and on their local machines during the hackweek"
keypoints:
- "participants will conduct tutorial exercises in a cloud environment"
- "everyone is encouraged to arrive with Python installed on their laptop for the project work"
- "Conda package and environment manager will be used to install python and other libraries"

---
This preliminary tutorial is one that we would like you to complete before arriving at Oceanhackweek. The purpose is to learn about the minimum system requirement for the Oceanhackweek, install the necessary software used during the week, and hopefully answer any other technical question about your computer setup. Our goal is to have everyone up-and-running prior to the event so we can focus our time more productively when you arrive in person.

> ## Python Version
> We will be using **Python 3** only during the hackweek. We encouraged participants who come from Python 2 to start reviewing the new syntax of Python 3.
> See [here](https://wiki.python.org/moin/Python2orPython3) for more details.
{: .callout}

### Overview

Python software is distributed as a series of *libraries* that are called within your code to perform certain tasks. There are many different collections, or *distributions* of Python software. Generally you install a specific distribution of Python and then add additional libraries as you need them. There are also several different *versions* of Python. The two main versions right now are 2.7 and 3.7. During the hackweek we will be using Python 3.7 for the tutorials, and encouraging participants to do so.

So even though Python is one of the most adaptable, easy-to-use software systems, you can see there are still complexities to work out and potential challenges when delivering content to a large group. Therefore we have a number of different ways that we are trying to simplify this process to maximize your learning during Oceanhackweek.

We will be using <http://ocean.pangeo.io>.
Pangeo is a [JupyterHub-like](https://jupyterhub.readthedocs.io/en/latest) implementation for the for ocean, atmospheric, and climate research community.
A Jupyter Notebook is an open-source web application that allows users to create and share documents containing live code, equations, visualizations, and markdown texts.
Here's a [overview](https://www.slideshare.net/willingc/jupyterhub-a-thing-explainer-overview) on JupyterHub.

We also provide instructions for using [Miniconda](https://conda.io/miniconda.html), which is our recommended Python distribution. We can assist in setting up "conda" environments that will simplify the gathering of Python libraries and version specific to the tutorial you are working on.

### Getting set up with Conda

[**Conda**](http://conda.pydata.org/docs/) is an **open source `package` and `environment` management system for python libraries**. We will be using various
Python libraries with multiple dependencies, so it is critical that you have some sort of 
package management system in place. Conda can be installed in almost any computer. The advantage of [`conda` compared to `pip`](https://jakevdp.github.io/blog/2016/08/25/conda-myths-and-misconceptions) is that it has a built in environment management system as well as the management of binaries, and non-python dependencies.

Here are the system requirements:

- 32-bit or 64-bit computer.
- Minimum 400 MB disk space to download and install.
- Windows Vista or newer, OS X 10.7+, or Linux (Ubuntu, RedHat and others; CentOS 5+)

*NOTE: You do not need administrative or root permissions to install conda if you select a user-writable install location.*

Click [here](/01-conda-tutorial/) to start our Conda tutorial. Let us know if on Slack you are having problems with installing Conda.


### Brushing up on Python

Given all the heavy use of python during the oceanhackweek, we will not be able to provide instruction in Python fundamentals. Here are some excellent resources we recommend using to brush up on your Python skills in advance of our event:

* [Software carpentry lessons](https://software-carpentry.org/lessons/), especially the [Python tutorial](http://swcarpentry.github.io/python-novice-inflammation/)
* [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook)

### Getting setup with Git and Github

Be sure to arrive at Oceanhackweek with your own [GitHub](https://github.com/) account.

**Git Installation**


* Windows
  - You need to install Git for Windows from this [link](https://gitforwindows.org/). For more setup details follow these [instructions](https://carpentries.github.io/workshop-template/#shell)

* MAC OS

  - Download the [git installer](https://git-scm.com/download/mac) and run it.

* Linux (Debian)

  ```
    sudo apt install git-all
  ```

### Getting started with Bash

During the hackweek it will be useful to know how to navigate between files from the command line. If you are not familiar with the unix shell commands you can review the first three sections of this [Software Carpentry Shell Novice](https://swcarpentry.github.io/shell-novice/) lesson. On Windows, use the Git Bash terminal to run these commands.


### Command line editor

When working on the command line, it is often handy to modify file content directly from there. For that you can use a command line editor such as `nano`. On Mac and Linux it is usually pre-installed, but for Windows you can follow the instructions in this [link](http://carpentries.github.io/workshop-template/#editor) to set it up.
  