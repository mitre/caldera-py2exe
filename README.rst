py2exe for Python 3
===================

This is a fork of py2exe version 0.9.2.2 that has been modified to work with
Python 3.5. 

How to build and install on Python 3.5:

- Install VS2015 or `VC++ Build Tools <http://landinghub.visualstudio.com/visual-cpp-build-tools>`_
- Open the "VS2015 x64 Native Tools Command Prompt" 
- navigate to the py2exe folder
- execute `python setup.py bdist`
- execute `python setup.py bdist_egg`
- install with easy_install
