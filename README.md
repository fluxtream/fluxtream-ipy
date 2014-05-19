fluxtream-ipy
=============

This is a repository for iPython notebooks which interface to Fluxtream.  This currently includes:
 * [netatmo-fluxtream-gateway.ipynb](http://nbviewer.ipython.org/github/fluxtream/fluxtream-ipy/blob/master/netatmo-fluxtream-gateway.ipynb): A notebook that walks you through reading data from a Netatmo account, either via CSV files downloaded from the Netatmo web site or via use of the Netatmo API, and sending it to Fluxtream.

The main website with info about iPython notebooks is [here](http://ipython.org/notebook.html).

You will need to install python and iPython notebook on your local system, run a local ipython kernel, and make a local copy of a given notebook to be able to execute and modify the code.

Install instructions for iPython Notebook are [here](http://ipython.org/install.html). At least on osx systems, after installation you can start the server by going to Terminal and calling 'ipython notebook'. This will start a local web server talking to an iPython kernel and open a [root IP[y] page](http://127.0.0.1:8890/tree).  

The  directory where you start the iPython Notebook server will be treated as iPython's home directory.  New and imported notebooks will be put in that directory, so it's good to remember where you started the server from and be consistent about it.

To view a properly formatted static copy of a given .ipynb file, you can go to the iPython Notebook Viewer [here](http://nbviewer.ipython.org/) and paste in a URL to the .ipynb file.

For example, for viewing the Netatmo/Fluxtream Gateway notebook in this repo (netatmo-fluxtream-gateway.ipynb), you can copy the github URL for it (https://github.com/fluxtream/fluxtream-ipy/blob/master/netatmo-fluxtream-gateway.ipynb) into the box at the main page of the [iPython Notebook Viewer](http://nbviewer.ipython.org/).  You can also share the URL for this page with others so they can go there directly.  For example, the URL for viewing the Netatmo/Fluxtream Gateway notebook in this github repo is http://nbviewer.ipython.org/github/fluxtream/fluxtream-ipy/blob/master/netatmo-fluxtream-gateway.ipynb

The [iPython Notebook Viewer](http://nbviewer.ipython.org/) opens a static view of an .ipynb file and lets you download a copy to your local computer.  The download button in the static view is an arrow pointing down in the upper right corner.  

Another option for getting these .ipynb files to your local machine is to fork or clone this github project to a local directory.  This is the better option if you want to submit changes, but isn't necessary if you just want to use a given notebook as a starting point for personal customization.

From the [root IP[y] page on your local server](http://127.0.0.1:8890/tree), you can open an iPython notebook you have saved locally by clicking on the link near the top that says "To import a notebook, drag the file onto the listing below or click here."  You can also run 'ipython notebook' from within a directory containing your .ipynb files so they show up by default.  In that case you can just click on them.

Once you have IP[y] generally working on your system, here's a brief intro in how to use it:
* A green outline shows the currently selected cell.
* Select a different cell by clicking on it.
* Execute the currently selected cell by either clicking the play button on the icon bar at the top, selecting Cell/Run from the menu bar, or by using the keyboard shortcut Shift-Return.
