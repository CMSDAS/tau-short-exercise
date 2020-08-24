# Tau short exercise for the 2020 CMSDAS

General information on CMSDAS 2020:
* https://indico.cern.ch/e/cmsvdas2020
* https://twiki.cern.ch/twiki/bin/view/CMS/WorkBookExercisesCMSDataAnalysisSchool#CmsDas2020CERN

**Video introduction**: [watch here!](https://videos.cern.ch/record/2728115)

### Recommended way to run the exercise (SWAN)

The Tau exercise is organised in two Jupyter notebooks, both contained in this repository.

To run the notebooks with regular CERN resources:
* Open a SWAN session at swan.cern.ch (the defaults are good, as of writing this pick software stack 97a and make sure to use Python3)
* In the SWAN session, click on the item on the right-hand side that says "Download Project from git"
* Copy-paste https://github.com/cmsdas/tau-short-exercise.git
* You're all set and can click on the two exercises, `tau_short_exercise_1.ipynb` and `tau_short_exercise_2.ipynb`

### Alternative way to run the exercise

The exercise can also be run on any system that has Python 3, ROOT including PyROOT, and jupyter installed.

Note:
* The exercise can also be made to run with Python 2, but we use f-strings so it will require a few changes. Given the end of lifecycle of Python 2, we decided to not retain backwards compatibility.
* The software stack can be installed with conda (root, jupyter, python3). In this case, pick root version 6.20 since 6.22 currently has a bug (which is already being addressed) that prevents it to work together with jupyter.
