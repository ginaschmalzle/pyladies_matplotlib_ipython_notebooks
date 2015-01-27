# Pyladies!  

This repo contains information on the **IPython Notebooks/Matplotlib** workshop.

The directions contained here have been done on a Mac.  Not sure how to do it on a PC, but Google is a good source of help :-).

If you have a Mac you should have Xcode and command line tools already installed (you can download these through the app store).  

Things to do before the workshop:

(1) Pull this github repository.

cd into your working directory and type:

  git clone https://github.com/ginaschmalzle/pyladies_matplotlib_ipython_notebooks

this will create a directory called pyladies_matplotlib_ipython_notebooks.  In this directory contains this readme file as well as the python requirements you will need, the data we will be exploring during the course and the ipython notebook.

(2) Prepare your version of Python

We recommend using a virtual environment.  If you don't have virtualenv installed you can install it using your default python package by typing in the command line:

  easy_install virtualenv

In your working directory then type:

  virtualenv env

To use your new version of your virtual environment type (in your working directory):

  source env/bin/activate

Now you should be using your new python through the virtual environment.

To participate in the workshop you will need the modules in requirements.txt.  Install them by typing:

pip install -r requirements.txt

(3) Download and install Basemap. You will have to go here:

http://matplotlib.org/basemap/users/installing.html

and follow the directions under Installation.

Now you are set for the workshop!  The ipython notebook in this repository is the notebook we will be going through in the class.  We will go through all the steps, and there will be time in the end to play with the codes, ask questions or whatever you like.
