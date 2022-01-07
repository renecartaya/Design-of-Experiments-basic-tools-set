# Design-of-Experiments-basic-tools-set

The current repository contain a compilation of statistical tools for Design of Experiments mainly in python and R. The current repository has been implemented using the interactive development environment Jupyterlab 3.2.1 under the Anaconda distribution. 

Important part of this repository is based in the python packages pyDOE, pyDOE2, and DOEPY according to the official webpages, this packages are designed for their use for scientist, engineers, statistician to support optimal experimental designs. The Capabilities includes:

 1) Factorial Designs.
 
    1.1) General Full Factorial.
    1.2) 2-Level Full Factorial.
    1.3) 2-Level Fractional-Factorial.
    1.4) Plackett-Burman
    
 2) Response-Surface Design.
    2.2) Box-Behnkel
    3.2) Central-Composite
    
 3) Randomized Designs.
    3.1) Latin-Hypercube

The functionalities requires the use of the packages:

 1) NumPy a well known fundamental package for scientific computing.
 2) SciPy consisting of a set of fundamental algoritms for scientific computing in Python.

For the use of the above mentioned functions, the packages pyDOE, pyDOE2 and DOEPY should be installed. The installation in the case of the Anaconda distribution could be performed in the Anaconda prompt using the following comands:

>> pip install --upgrade pyDOE
>> pip install pyDOE2
>> pip install doepy

For the case of DOEPY previusly should be installed

>> pip install diversipy

All the available functionalities from pyDOE can be accessed by the statement

 >> from pyDOE import *

For the case of 

For more information about pyDOE please visit the web: https://pythonhosted.org/pyDOE/.

For more information about DOEPY please visit the web: https://doepy.readthedocs.io/en/latest/


