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

### Installing Miniconda

##### Windows
Click [here](https://docs.conda.io/en/latest/miniconda.html) to download the proper installer for your Windows platform (64 bits).
We recommend to download the Python 3 version of Miniconda. You can still create Python 2 environments using the Python 3 version of Miniconda.

When installing, you will be asked if you wish to make the Anaconda Python your default Python for Windows, just follow the default options.

##### Linux and maxOS
You may follow the manual download to the instructions on Windows (see above). Alternatively, you can execute these commands on a terminal shell (in this case, the bash shell):

```bash
url=bit.ly/miniconda3
wget $url -O miniconda.sh
bash miniconda.sh -b -p $HOME/miniconda
export PATH="$HOME/miniconda/bin:$PATH"
conda update conda --yes
```

### Installing Python
We will be using Python 3.7 during the week. 
If you are already familiar with Python 2.7, you can take a look at the syntax differences [here](http://sebastianraschka.com/Articles/2014_python_2_3_key_diff.html), but the main point to remember is to put the print statements in parentheses:
```python
print('Hello World!')
```


``` bash
$ conda create -n OHW python=3.7
```

To use Python 3.7: 

``` bash
$ source activate OHW
```

To check if you have the correct version: 

``` bash
$ python --version
```
