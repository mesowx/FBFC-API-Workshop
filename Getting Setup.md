
### Getting our Notebooks

Our notebooks are located on this github account. If you have git and are familiar, we encourage you to create a fork of this respository in your own account, and clone that to your machine. If this sounds like jibberish to you, no worries, simply download the git repository as a [zip file](https://github.com/mesowx/FBFC-API-Workshop/archive/master.zip) (if you can unzip them) or manually download raw versions of each of the ipynb exercise files, and then navigate to where you put them in your Jupyter Notebook.


# Installation Guide

The best way to satisfy the course requirements is to install the Anaconda package/environment manager at https://www.continuum.io/downloads.

### Anaconda (aka Conda) Python Installation on Windows

We are going to use the Anaconda python suite for today's workshop, and we are going to use the Python 3.5 version of that suite. If you have 2.7, that is great, but some of the functions we are going to use don't exist in Python 2.7. For windows, installing the 3.5 anaconda is as simple as:

1. Visit https://www.continuum.io/downloads
2. Download the Python 3.5 Anaconda Graphical installer (you will need >360mb of free disk space for this)
3. Open the installer, and install (just for you unless you are an admin), mostly just click next.


#### To use this python

We talk a lot about notebooks, while we may call them Ipython Notebooks, these work the same as the Jupyter notebooks that came installed with Conda. Unless you are a console guru, we suggest you go to your applications list (start button, home screen, whichever) and under the Anaconda3 collection, you will see:

* Anaconda Navigator
* iPython
* Jupyter Notebook
* Spyder
* And some other things

Click Jupyter Notebook, and don't look back. Your windows command prompt also now has a `conda` command which you can use to do various things, and if you enter `jupyter notebook` into this terminal, it will do the same thing as clicking the application.

#### Adding Missing Libraries

Anaconda has a lot, but there are some things it does not have. To install a library which is not available in the default anaconda installation, you can attempt to use the navigator to add packages using the _Environments_ tab. This, however, is not always functional, and you might want to use a terminal and the commands shown later in the terminal commands section of this guide.

### Installing Conda on a Mac

The same steps for windows users apply for mac users:

1. Visit https://www.continuum.io/downloads
2. Download the Python 3.5 Anaconda Graphical installer (you will need >360mb of free disk space for this)
3. Open the installer, and install (just for you unless you are an admin), mostly just click next.


Once downloaded to your Mac, you will only see one new icon, possibly installed in your applications folder/exposé, or it might just be sitting on your desktop. For Macs, since specific application icons are not created, we recommend you use your terminal to open the notebook application. Important terminal commands are covered below. 

You can also open that navigator.app application, and in it you will see "launch" buttons for jupyter notebooks, which are what you want.

#### Adding Missing Libraries

Anaconda has a lot, but there are some things it does not have. To install a library which is not available in the default anaconda installation, you can attempt to use the navigator to add packages using the _Environments_ tab. This, however, is not always functional, and you might want to use a terminal and the commands shown later in the terminal commands section of this guide.


### Linux Installation

If you are using linux for this tutorial, we are more or less going to assume you can find and install your own packages. If not we're here to help, since we spend a lot of time using these packages on Ubuntu.

## Terminal Commands

While we don't want you to have to use the terminal for anything here, sometimes it is an easier way to get things set up. Fortunately, conda gives users the same commands whether they are using Windows, OSX or Linux. Some valuable commands are:

* `conda install [package]` This can be used to install something that is missing
* `conda install -c [source] [package]` This command will install something and tells anaconda where to look for it
* `jupyter notebook` will open up your notebook session if you can't or don't want to find the icon for that application
* `ipython` will open a terminal-based interactive python environment

### Installing CartoPy

One very exciting library out there is CartoPy, which lets you create powerful maps and geo-visualizations. Unfortunately CartoPy is a bit tricky to install. In some environments these commands work, and in others they don't. To try to install cartoPy, in a terminlal, enter:
`conda install -c scitools cartopy`

If that spews lots of unhappy things, you are probably not in luck. You can try `pip install cartopy` or `easy_install cartopy` but, they are not likely to work. If you can't get it to install on your machine, don't worry. 


### Some more advanced terminal options

You can improve your python experience by creating a virtual environment that you run our exercises in. Here is a set of commands you could use to do so. 

1. Open a command prompt and verify your anaconda installation by typing `conda info`. If the current version comes up, you're good to go. 
2. Now we can set up a clean working environment! Simply type `conda create -n apiworkshop anaconda` to create a new virtual environment that installs all of the common python libraries. 
3. Once that process is completed, activate this environment by typing `source activate apiworkshop`. 


### Questions? Problems?

* Shoot Josh an e-mail at joshua.m.clark@utah.edu or call 502-295-8895.
* Before the workshop: We'll be setting up the workshop at 7am on Monday. Stop by early and we'll work on getting you set up with the course requirements.



