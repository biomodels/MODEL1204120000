# MODEL1204120000: ZebraGEM_2012

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1204120000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1204120000.git@20140916`

## Usage

Importing the model package.

`import MODEL1204120000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Bekaert2012 - Reconstruction of D.rerio Metabolic Network

_Danio rerio_ metabolic model accounting for subcellular compartmentalisation
(ZebraGEM)

This SBML representation of the _D. rerio_ (zebrafish) metabolic network is
made available under the Creative Commons Attribution-Share Alike 3.0 Unported
Licence (see [www.creativecommons.org](http://creativecommons.org/licenses/by-
sa/3.0/) ).

This model is described in the article:

[Reconstruction of Danio rerio Metabolic Model Accounting for Subcellular
Compartmentalisation.](http://identifiers.org/pubmed/23166792)

Bekaert M.

PLoS One. 2012;7(11):e49903.

Abstract:

Plant and microbial metabolic engineering is commonly used in the production
of functional foods and quality trait improvement. Computational model-based
approaches have been used in this important endeavour. However, to date, fish
metabolic models have only been scarcely and partially developed, in marked
contrast to their prominent success in metabolic engineering. In this study we
present the reconstruction of fully compartmentalised models of the Danio
rerio (zebrafish) on a global scale. This reconstruction involves extraction
of known biochemical reactions in D. rerio for both primary and secondary
metabolism and the implementation of methods for determining subcellular
localisation and assignment of enzymes. The reconstructed model (ZebraGEM) is
amenable for constraint-based modelling analysis, and accounts for 4,988 genes
coding for 2,406 gene-associated reactions and only 418 non-gene-associated
reactions. A set of computational validations (i.e., simulations of known
metabolic functionalities and experimental data) strongly testifies to the
predictive ability of the model. Overall, the reconstructed model is expected
to lay down the foundations for computational-based rational design of fish
metabolic engineering in aquaculture.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels)
and identified by:
[MODEL1204120000](http://www.ebi.ac.uk/biomodels/MODEL1204120000) .

To cite BioModels Database, please use: BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic models.
PMID: [20587024](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication>http://creativecommons.org/publicdomain/zero/1.0/] for more
information.


