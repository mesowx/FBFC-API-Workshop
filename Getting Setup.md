#Hello!

Thanks for signing up for the MesoWest/SynopticLabs API workshop at the Fire Behavior and Fuels Conference.

In this course, we'll explore the API in great detail, working through examples and some interactive sessions to ensure you know how to best use our data.

This course assumes you have some background in programming. If you're not familar with Python or JavaScript, that's okay! We've tried to use simple syntax to keep the focus on the data and the resulting demo. We will be using Jupyter/iPython notebooks (http://jupyter.org/) when working in Python and JsFiddle (https://jsfiddle.net/) in our JS demo. These tools allow us to execute our code in real-time and work through examples more interactively.

##Oh, by the way.

All of our examples, schedule, and instructions can be found here, on Github at https://github.com/mesowx/FBFC-API-Workshop. You can follow along online at that link (non-interactive) or clone the repo by making sure you have git installed on your computer and then typing git clone https://github.com/mesowx/FBFC-API-Workshop.git in to a command prompt. Come to the workshop at least 30 minutes before the start if you need help setting this up.

## Course Requirements:

In order to get the most out of this course, we've tried to use modern libraries and teaching solutions. This course requires your computer to have the following installed:

*Python 3.4/3.5
*A web browser
*The following python libraries: IPython, CartoPy, and their dependencies. All other libraries should be built-in to your python installation

The best way to satisfy the course requirements is to install the Anaconda package/environment manager at https://www.continuum.io/downloads.


### If you are comfortable in terminals, try this:

Once you complete that download, 
1. open a command prompt and verify your anaconda installation by typing conda info. If the current version comes up, you're good to go. 2. Now we can set up a clean working environment! Simply type conda create -n apiworkshop anaconda to create a new virtual environment that installs all of the common python libraries. 
3. Once that process is completed, activate this environment by typing source activate apiworkshop. 
4. Now, run conda install -c scitools cartopy fulfill the course requirements. Lastly, navigate to your git clone of the workshop repo, and type ipython notebook. Your notebooks should be good to go!
5. 
Cool, so what are these Jupyter/iPython notebooks anyway?
Simply put, they are interactive, shareable notebooks containing live code and visualizations. These notebooks are perfect for teaching, as they allow us to add markup and visuals right in line with our code. You're viewing all of this in a Jupyter notebook!
The notebook consists of cells which contain code or markdown. These cells are ran when you press play on the top menu. Like the python interpreter, these cells are executed line by line, so always run cells in order from top to bottom.
Questions? Problems?
Before the conference: shoot Josh an e-mail at joshua.m.clark@utah.edu or call 502-295-8895.
Before the workshop: We'll be setting up the workshop at 7am on Monday. Stop by early and we'll work on getting you set up with the course requirements.

#Let's get things installed

We are just going to quickly go through how we expect you to install and use today's Python applications.

## Installation on Windows

We are going to use the Anaconda suite for today's workshop, and we are going to use the Python3.5 version of that suite. If you have 2.7, that is great, but some of the functions we are going to use don't exist in Python 2.7. For windows, installing the 3.5 anaconda is as simple as:

1. Visit https://www.continuum.io/downloads
2. Download the Python 3.5 anaconda GUI installer
3. Open the installer, and install (just for you unless you are an admin), mostly just click next.

### To use this python

We talk a lot about notebooks, while we may call them ipython Notebooks, these work the same as the Jupyter notebooks that came installed with conda. Unless you are a console guru, we suggest you go to your applicatios list (start button, home screen, whichever) and under the Anaconda3 collection, you will see:

* Anaconda Navigator
* iPython
* Jupyter Notebook
* Anaconda Prompt
* Spyder
* And some other things

Each of these will do awesome things for you, but for this exercise we are going to only be using the notebooks. Feel free to double click the Jupyter notebook application, and you will see your favorite web browser open up to a folder listing. 

## For Macs

We still recommend downloading the graphical downloader for macs, though more comfortable users can use services like homebrew



