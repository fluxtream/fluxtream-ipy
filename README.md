fluxtream-ipy
=============

This is a repository for iPython notebooks which interface to Fluxtream.  This currently includes:
 * [netatmo-fluxtream-gateway.ipynb](http://nbviewer.ipython.org/github/fluxtream/fluxtream-ipy/blob/master/netatmo-fluxtream-gateway.ipynb): A notebook that walks you through reading data from a Netatmo account, either via CSV files downloaded from the Netatmo web site or via use of the Netatmo API, and sending it to Fluxtream.

 * [iPhoto-fluxtream-upload.ipynb](http://nbviewer.ipython.org/github/fluxtream/fluxtream-ipy/blob/master/iPhoto-fluxtream-upload.ipynb): A notebook that walks you through uploading photos from your computer's filesystem to Fluxtream.
 * [Nonin-SpO2-thresh](http://nbviewer.ipython.org/github/fluxtream/fluxtream-ipy/blob/master/Nonin-SpO2-thresh.ipynb): A notebook that walks you through reading data from an existing Fluxtream channel, modifying it, and re-uploading the result.  

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
* Select a different cell by clicking on it, or by using escape to enter command mode (grey outline) and use the keyboard shortcuts listed under the Help menu.
* Execute the currently selected cell by either clicking the play button on the icon bar at the top, selecting Cell/Run from the menu bar, or by using the keyboard shortcut Shift-Return.

Repository of iPython notebooks which interface to Fluxtream

If you are new to iPython notebooks, [here](http://ipython.org/notebook.html) is the main IP[y] website. 

You will need to install python and iPython notebook on your local system, run a local ipython kernel, and install a local copy of this notebook to be able to execute and modify the code below. 

Install instructions are [here](http://ipython.org/install.html). At least on osx systems, you can start the server by going to Terminal and calling 'ipython notebook'. This will start a local web server and open a an IP[y] page talking to it in a web browser. 

Within the IP[y] startup page, you can open an iPython notebook saved locally by clicking on the link near the top that says "To import a notebook, drag the file onto the listing below or click here."

The main website with info about iPython notebooks is [here](http://ipython.org/notebook.html).

You will need to install python and iPython notebook on your local system, run a local ipython kernel, and make a local copy of a given notebook to be able to execute and modify the code.

Install instructions for iPython Notebook are [here](http://ipython.org/install.html). At least on osx systems, after installation you can start the server by going to Terminal and calling 'ipython notebook'. This will start a local web server and open a root [IP[y] page](http://127.0.0.1:8890/tree) talking to that local server.

To view a properly formatted static copy of a given .ipynb file, you can go to the iPython Notebook Viewer [here](http://nbviewer.ipython.org/) and paste in its URL.

For example, for viewing the Netatmo/Fluxtream Gateway notebook (netatmo-fluxtream-gateway.ipynb), you can copy the URL for it in github (https://github.com/fluxtream/fluxtream-ipy/blob/master/netatmo-fluxtream-gateway.ipynb) into the box at the main page of the [iPython Notebook Viewer](http://nbviewer.ipython.org/).  You can also share the URL for this page with others so they can go there directly.  For example, the URL for viewing the Netatmo/Fluxtream Gateway notebook in this github repo is http://nbviewer.ipython.org/github/fluxtream/fluxtream-ipy/blob/master/netatmo-fluxtream-gateway.ipynb

The [iPython Notebook Viewer](http://nbviewer.ipython.org/) opens a static view of the .ipynb file and lets you download a copy to your local computer.  The download button in the static view is an arrow pointing down in the upper right corner.  

Another option for getting these .ipynb files to your local machine is to fork or clone this github project to a local directory.  This is the better option if you want to submit changes, but isn't necessary if you just want to use a given notebook as a starting point for personal customization.

From the [root IP[y] page on your local server](http://127.0.0.1:8890/tree), you can open an iPython notebook you have saved locally by clicking on the link near the top that says "To import a notebook, drag the file onto the listing below or click here."  You can also run 'ipython notebook' from within a directory containing your .ipynb files so they show up by default.  In that case you can just click on them.

Once you have IP[y] generally working on your system, here's a brief intro in how to use it:
* A green outline shows the currently selected cell.
* Select a different cell by clicking on it.
* Execute the currently selected cell by either clicking the play button on the icon bar at the top, selecting Cell/Run from the menu bar, or by using the keyboard shortcut Shift-Return.

Nonin-WristOx2-3150
-------------------

Using an iPython notebook, configure a Nonin WristOx2 3150 to log once per second, and then pull sessions from it over USB
to graph locally and to upload to fluxtream.org for exploration.

Once you've gotten the notebook running, evaluate each section in series.  This will configure logging, and set the current
time on the device.  (Because the Nonin device does not cope with timezones or daylight savings time, this package sets
the time on the Nonin according to GMT/UDT, and assumes the same when it pulls data from the Nonin.  So you're free
to use it across timezones and DST boundaries!)

When uploading to Fluxtream, you'll want to enter your username and password for fluxtream.org.  Be sure to click the
'set' button, which reads your password into the running python kernel, and clears the password field on the page.
In particular, be sure to click set and not leave your password in the textarea field before sharing your notebook
with someone else.

After you've downloaded a batch and uploaded to fluxtream, you can optionally clear out the data on the nonin.
Simply evaluate

    nonin.clear_sessions()

(Here's an [online view of the notebook](http://nbviewer.ipython.org/github/fluxtream/Nonin-WristOx2-3150/blob/master/Nonin-WristOx2-3150.ipynb), but you'll need to be running it locally to download data from the Nonin and upload to Fluxtream)
