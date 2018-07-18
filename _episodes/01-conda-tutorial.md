---

title: "Getting Started with Conda"
teaching: 15
exercises: 0
questions:
- "What is Conda?"
- "How do I install Conda?" 
objectives:
- Get conda installed!
keypoints:
- conda can be installed in two ways (Anaconda and Miniconda)
- conda package manager works across systems

---

### What is Conda?
[**Conda**](http://conda.pydata.org/docs/) is an **open source `package` and `environment` management system for any programming languages, but very popular among python community,** for installing multiple versions of software packages, their dependencies and switching easily between them. It works on Linux, OS X and Windows.

[This Continuum blog post is a terrific, recent and comprehensive introduction to conda](http://www.continuum.io/blog/conda-data-science) targeted to data scientists. It also has links to a presentation (Youtube and slides) on the same material. An extra nifty aspect of this material is that it "explores how to use conda in a multi-language data science project" with an example combining Python and R libraries.

### Installing Miniconda

##### Windows
Click [here](http://conda.pydata.org/miniconda.html) to download the proper installer for your Windows platform (32 or 64 bits).
We recommend to download the Python 3 version of Miniconda. You can still create Python 2 environments using the Python 3 version of Miniconda.

When installing, you will be asked if you wish to make the Anaconda Python your default Python for Windows.
If you do not have any other installation that is a good option.  If you want to keep multiple versions of python on your machine (e.g. ESRI-supplied python, or both 32 and 64 bit versions of Anaconda), then don't select the option to modify your path or modify your windows registry settings.

##### Linux and OSX
You may follow manual steps from [here](http://conda.pydata.org/miniconda.html) similar to the instructions on Windows (see above). Alternatively, you can execute these commands on a terminal shell (in this case, the bash shell):

```bash
url=bit.ly/miniconda3
wget $url -O miniconda.sh
bash miniconda.sh -b -p $HOME/miniconda
export PATH="$HOME/miniconda/bin:$PATH"
conda update conda --yes
```

### Installing Python
We will be using Python 3.6 during the week. 
If you are already familiar with Python 2.7, you can take a look at the syntax differences [here](http://sebastianraschka.com/Articles/2014_python_2_3_key_diff.html). 


``` bash
$ conda create -n py36 python=3.6
```

To use Python 3.6: 

``` bash
$ source activate py36
```

To check if you have the correct version: 

``` bash
$ python --version
```
