#Hello!

Thanks for signing up for the MesoWest/SynopticLabs API workshop at the Fire Behavior and Fuels Conference.

In this course, we'll explore the API in great detail, working through examples and some interactive sessions to ensure you know how to best use our data.

This course assumes you have some background in programming. If you're not familar with Python or JavaScript, that's okay! We've tried to use simple syntax to keep the focus on the data and the resulting demo. We will be using Jupyter/iPython notebooks (http://jupyter.org/) when working in Python and JsFiddle (https://jsfiddle.net/) in our JS demo. These tools allow us to execute our code in real-time and work through examples more interactively.

##Oh, by the way.

All of our examples, schedule, and instructions can be found here, on Github at https://github.com/mesowx/FBFC-API-Workshop. You can follow along online at that link (non-interactive) or clone the repo by making sure you have git installed on your computer and then typing git clone https://github.com/mesowx/FBFC-API-Workshop.git in to a command prompt. Come to the workshop at least 30 minutes before the start if you need help setting this up.

## Course Requirements:

In order to get the most out of this course, we've tried to use modern libraries and teaching solutions. This course requires your computer to have the following installed:

* Python 3.4/3.5
* A web browser
* The following python libraries: IPython or jupyter notebooks, CartoPy*, Bokeh, Matplotlib and their dependencies. All other libraries should be built-in to your python installation

_* CartoPy does not come with Anaconda, and can be tricky to install. For now, if you want you can try a couple of our suggestions below, but we are not likely to use our CartoPy-requiring example_

## Python Notebooks

As we said above, we are going to use interactive "notebooks" as the main way to play with and build applications using our API.

##### What are these Jupyter/iPython notebooks anyway?
Simply put, they are interactive, shareable notebooks containing live code and visualizations. These notebooks are perfect for teaching, as they allow us to add markup and visuals right in line with our code. You're viewing all of this in a Jupyter notebook!
The notebook consists of cells which contain code or markdown. These cells are ran when you press play on the top menu. Like the python interpreter, these cells are executed line by line, so always run cells in order from top to bottom.

When you open a notebook your computer will open a terminal (or keep the terminal open) and then create a tab on your default web browser. Don't worry, this is all perfectly normal. 

### Getting our Notebooks

Our notebooks are located on this github account. If you have git and are familiar, we encourage you to create a fork of this respository in your own account, and clone that to your machine. If this sounds like jibberish to you, no worries, simply download the git repository as a zip file (if you can unzip them, there is a button on the repository home page) or manually download raw versions of each of the ipynb exercise files, and then navigate to where you put them in your Jupyter Notebook.


# Installation Guide

The best way to satisfy the course requirements is to install the Anaconda package/environment manager at https://www.continuum.io/downloads.

### Anaconda (aka Conda) Python Installation on Windows

We are going to use the Anaconda python suite for today's workshop, and we are going to use the Python3.5 version of that suite. If you have 2.7, that is great, but some of the functions we are going to use don't exist in Python 2.7. For windows, installing the 3.5 anaconda is as simple as:

1. Visit https://www.continuum.io/downloads
2. Download the Python 3.5 Anaconda Graphical installer (you will need >360mb of free disk space for this)
3. Open the installer, and install (just for you unless you are an admin), mostly just click next.


#### To use this python

We talk a lot about notebooks, while we may call them ipython Notebooks, these work the same as the Jupyter notebooks that came installed with Conda. Unless you are a console guru, we suggest you go to your applications list (start button, home screen, whichever) and under the Anaconda3 collection, you will see:

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


Once downloaded to your mac, you will only see one new icon, possibly installed in your applications folder/exposé, or it might just be sitting on your desktop. For Macs, since specific application icons are not created, we recommend you use your terminal to open the notebook application. Important terminal commands are covered below. 

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

One very exciting library out there is CartoPy, which lets you create exciting maps and geo-visualizations. Unfortunately CartoPy is a bit tricky to install. In some environments these commands work, and in others they don't. To try to install cartoPy, in a terminlal, enter:
`conda install -c scitools cartopy`

If that spews lots of unhappy things, you are probably not in luck. You can try `pip install cartopy` or `easy_install cartopy` but, they are not likely to work. If you can't get it to install on your machine, don't worry. 


### Some more advanced terminal options

You can improve your python experience by creating a virtual environment that you run our exercises in. Here is a set of commands you could use to do so. 

1. open a command prompt and verify your anaconda installation by typing conda info. If the current version comes up, you're good to go. 2. Now we can set up a clean working environment! Simply type conda create -n apiworkshop anaconda to create a new virtual environment that installs all of the common python libraries. 
3. Once that process is completed, activate this environment by typing source activate apiworkshop. 


### Questions? Problems?

* Before the conference: shoot Josh an e-mail at joshua.m.clark@utah.edu or call 502-295-8895.
* Before the workshop: We'll be setting up the workshop at 7am on Monday. Stop by early and we'll work on getting you set up with the course requirements.



