# BIOMD0000000379: DallaMan2007_MealModel_GlucoseInsulinSystem

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000379.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000379.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000379 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Meal simulation model of the glucose-insulin system. **   
Dalla Man C, Rizza RA, Cobelli C._IEEE Trans Biomed Eng._2007
Oct;54(10):1740-9. [ 17926672](http://www.ncbi.nlm.nih.gov/pubmed/17926672),  
**Abstract:**   
A simulation model of the glucose-insulin system in the postprandial state can
be useful in several circumstances, including testing of glucose sensors,
insulin infusion algorithms and decision support systems for diabetes. Here,
we present a new simulation model in normal humans that describes the
physiological events that occur after a meal, by employing the quantitative
knowledge that has become available in recent years. Model parameters were set
to fit the mean data of a large normal subject database that underwent a
triple tracer meal protocol which provided quasi-model-independent estimates
of major glucose and insulin fluxes, e.g., meal rate of appearance, endogenous
glucose production, utilization of glucose, insulin secretion. By decomposing
the system into subsystems, we have developed parametric models of each
subsystem by using a forcing function strategy. Model results are shown in
describing both a single meal and normal daily life (breakfast, lunch, dinner)
in normal. The same strategy is also applied on a smaller database for
extending the model to type 2 diabetes

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


