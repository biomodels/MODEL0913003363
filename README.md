# MODEL0913003363: Cui2006_CalciumHomeostasis

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL0913003363.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL0913003363.git@20140916`

## Usage

Importing the model package.

`import MODEL0913003363 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Mathematical modeling of calcium homeostasis in yeast cells.**   
Cui J, Kaandorp JA. _Cell Calcium_ 2006 Apr;39(4):337-48
[16445978](http://www.ncbi.nlm.nih.gov/pubmed/16445978) ,  
**Abstract:**   
In this study, based on currently available experimental observations on
protein level, we constructed a mathematical model to describe calcium
homeostasis in normally growing yeast cells (Saccharomyces cerevisiae).
Simulation results show that tightly controlled low cytosolic calcium ion
level can be a natural result under the general mechanism of gene expression
feedback control. The calmodulin (a sensor protein) behavior in our model cell
agrees well with relevant observations in real cells. Moreover, our model can
qualitatively reproduce the experimentally observed response curve of real
yeast cell responding to step-like disturbance in extracellular calcium ion
concentration. Further investigations show that the feedback control mechanism
in our model is as robust as it is in real cells.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Cui J, Kaandorp JA. (2006) - version03**
](http://www.cellml.org/models/cui_kaandorp_2006_version03)  
The original CellML model was created by:  
**Lloyd, Catherine, May**   
c.lloyd@aukland.ac.nz  
The University of Auckland  
The Bioengineering Institute  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


