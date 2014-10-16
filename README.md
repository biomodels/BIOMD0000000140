# BIOMD0000000140: Hoffmann2002_WT_IkBNFkB_Signaling

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000140.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000140.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000140 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model corresponds to the IkB-NFkB signaling in wild type cells and
reproduces the dynamics of the species as depicted in Figure 2 F of the paper.
The authors mention that the simulation is carried out in three phases, where
the steady state values of the species in one phase are fed to the succeding
phase. This model captures the simulation dynamics of two phases and makes use
of the event section to introduce the stimulus and thereby transition to the
next phase. Accordingly, a few terms have been introduced that make this
transition possible, this in no way compromises the original model. Also, the
simulation plots are not an exact reproduction of the figures in the paper,
they do however match the simulation results that the authors shared with us.
Model was successfully tested on MathSBML.

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


