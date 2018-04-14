IT105 Introduction to Computer Science -- Based on How to Think Like a Computer Scientist 
=========================================================================================

This project began with the original How to Think Like a Computer Scientist text by Jeffrey Elkner, Peter Wentworth, Allen B. Downey, Chris  Meyers, and Dario Mitchell. Since 2011 Brad Miller, David Ranum, Barbara Ericson, Mark Guzdial, and many others have built on the text making it interactive.

Programming is not a "spectator sport".  It is something you do,
something you participate in. It would make sense, then,
that the book you use to learn programming should allow you to be active.
That is our goal.

This book is meant to provide you with an interactive experience as you learn
to program in Python.  You can read the text, watch videos,
and write and execute Python code.  In addition to simply executing code,
there is a unique feature called 'codelens' that allows you to control the
flow of execution in order to gain a better understanding of how the program
works.

.. image:: http://bnmnetp.me:8088/buildStatus/icon?job=thinkcspyBuild

Getting Started
===============

We have tried to make it as easy as possible for you to build and use this book.  

1. You can see and read this book online at `interactivepython.org <http://interactivepython.org/runestone/static/thinkcspy/index.html>`_

2.  You can build it and host it yourself in just a few simple steps:

    1.  ``pip install -r requirements.txt``  -- Should install everything you need
    2.  ``runestone build`` -- will build the html and put it in ``./build/thinkcspy``
    3.  ``runestone serve``   -- will start a webserver and serve the pages locally from ``./build/thinkcspy``

IT105 Specific Update Guidance
==============================

The master branch is tied directly to the production environment at code.it015.army. When the course is modified and rebuilt is is done so from the master branch. Assistance with content and updates to make the book better are appriciated. Please do the following to assist.

1. Fork this repository or create a new branch.

2. Follow the instructions above to install.

3. The content files are all in ``_sources``. Key files and information listed below.

   1. ``index.rst`` - This is the table of content for the entire page. It creates index.html
   2. Each chapter folder contains:

      1. ``toctree.rst`` - This is the chapter table of contents.
      2. ``Excercises.rst`` - A number of pertinant problems.
      3. ``glossary.rst`` - self explanitory
      4. A number of sections.

   3. Some of the Chapters such as ``ICE`` and ``Labs`` are just a list of exercises.
	 
4. Only modify content in the specifed directories below **(Any other changes will effect the thinkcspy course)**:

   1. ``ICE``
   2. ``Communications``
   3. ``IT105Resources``
   4. All new directories associated with IT105 will follow the naming convention of ``IT105_XXXX``

5. Coordinate with LTC Babbitt to merge and push to master.


