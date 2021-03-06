.. :changelog:

Release History
---------------

Next release
++++++++++++++++++

* Pre-sprints
    * Update of tutorial files and docs #176, #172
    * Adds np.int64() functions around some variables to get rid error caused by numpy update #188
    * Made examples Readme.md more readable #189

* From PyCon Sprints
    * Updating model example readmes #207
    * Added nose to requirements #208
    * Updated link on style google style guide #209
    * Reset visualization when websocket connection is opened #210
    * Remove unused scipy dependency #211
    * Introduce a requirements.txt for the tutorial. #212
    * Remove references to running in tutorial #213
    * Simplify travis.yml; add python versions #215
    * Update Flocker Readme.md #216
    * Syntax error in .rst was swallowing a code block #217
    * Fixup HistogramModule in the tutorial. #218
    * add more test coverage to time #221
    * add a requirements.txt for WolfSheep. #222
    * add a requirements.txt for Schelling. #224
    * Refactor color patches example #227
    * Ignored _build sphinx docs still in repo #228
    * Intro Tut completely in ipynb #230
    * pass optional port parameter to ModularServer.launch #231
    * open vis immediately when running color patches #232
    * Adds .DS_store to .gitignore #237
    * Documentation Update #240
    * Small fix for reading links #241
    * Test batchrunner #243
    * clean up TextVisualization #245


0.7.0 (2016-03-06)
++++++++++++++++++
* #184 Adding terminal echo for server launch to signal person running the model
* #183 Adding Conway's Game of Life simulation to the examples.

0.6.9 (2016-02-16)
++++++++++++++++++

* #170 Adding multi-stage activation
* #169 Wolf-Sheep Cleanup
* Updates requirements to latest libraries


0.6.7 (2015-07-11)
++++++++++++++++++

* Improvements
    * Allow cell_list_content methods in Grids to accept single tuples in addition to lists


0.6.6 (2015-07-11)
++++++++++++++++++

Theme: Scipy Sprints ( ‘-’)人(ﾟ_ﾟ )

* Improvements
    * Standardizes the arguments passed to spatial functions to only tuples, not separate x and y coordinates. (Breaks backwards compatibility)


0.6.5.1 (2015-07-11)
++++++++++++++++++

Theme: Scipy Sprints ( ‘-’)人(ﾟ_ﾟ )

* Improvements
    * Adding version, license, copyright, title to __init__.py
    * Auto updating version in setup.py
* Bug fix
    * Updating MANIFEST.in to include visualization templates that were missing.


0.6.5 (2015-07-11)
++++++++++++++++++

Theme: Scipy Sprints ( ‘-’)人(ﾟ_ﾟ )

* Edits
    * Additions to tutorial doc
    * Minor edits to README & Intro
    * Minor edits / clean up to setup.py
    * Removing .ipynb_checkpoints
    * Removing out-of-date planning documentation.
* Bug fix
    * Use setuptools' find_packages function to get the list of packages to install, fixes #141
* Improvements
    * Use package_data for include the web files
    * Use a MANIFEST.in file to include the LICENSE file in source distributions
    * Using conda on Travis allows much faster builds and test runs


0.6.2 (2015-07-09)
++++++++++++++++++

* Improvement: Adding continuous space.
* Improvement: Adding a simultaneous activation scheduler.
* New models:
	- Flockers
	- Spatial Demographic Prisoner's Dilemma (PD_Grid)

0.6.1 (2015-06-27)
++++++++++++++++++

* Bug Fix: Order of operations reversed: agent is removed first and then it is placed.
* Improvement: `LICENSE`_ was updates from MIT to Apache 2.0.

.. _`LICENSE` : https://github.com/projectmesa/mesa/blob/master/LICENSE


0.6.0 (2015-06-21)
++++++++++++++++++

* Improvment: Add modular server feature, which breaks up a model into a .py file and a .js file. This breaks backwards compatibility.

Pre 0.6.0
++++++++++++++++++

Code that is pre-0.6.0 is very unstable.

Our inital release was 0.5.0 (2014-11).

It included code for placing agents on a grid; a data collector and batch runner; and a front-end visualization using HTML 5 and JavaScript.

**General**

* Objects create -- Agent, Time, Space
* Project moved to Python 3
* Tornado server setup

**Front-end**

* Front-end grid implemented
* ASCII visualization implemented

**Examples models**

* Forest Fire
* Schelling
* Wolf-Sheep Predation

**0.1.0 (2014-09-19)**

* A conversation
* Birth
