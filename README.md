# Machine-Learning-based-New-Reactions-Discovery
Transition-metal-free carbon-carbon (C-C) couplings, involving secondary alcohols and boronic acids, offer an atom-efficient and environmentally sustainable route, yet remain challenging to execute. This study aims to expedite the discovery of reactions through the implementation of a machine learning (ML)-guided workflow. By leveraging data from 761 pertinent transformations, encompassing boronic acids and activated moieties, the optimized ML model enables precise predictions (with a correlation coefficient of R² = 0.92) and extrapolations. Screening 100 potential reactions led to the experimental validation of four promising reactions across diverse alkenyl boronic acids and secondary alcohols bearing varying substituents (R² ranging from 0.89 to 0.98). This yielded a series of 2-(4-phenylbut-3-en-2-yl)phenols, which can be further transformed into valuable scaffolds. This study offers a rapid and effective screening methodology for secondary alcohols suitable for C-C couplings with boronic acids, supported by ML predictions. This approach not only facilitates the exploration of alternative methods for target reactions but also broadens the horizons of reaction design possibilities.


The Transformer model has recently ushered in transformative advancements in the field of natural language processing. Additionally, it has demonstrated remarkable utility in chemistry through the utilization of a textual representation known as the simplified molecular input line system (SMILES), which encodes molecular and chemical reactions. These studies clearly indicate that the Transformer model possesses the capability to acquire knowledgepertaining to organic chemistry and chemical reactions by analyzing SMILES.

# Requirements
As the library is based on the chemoinformatics toolkit [RDKit](http://www.rdkit.org) it is best installed using the [Anaconda](https://docs.conda.io/en/latest/miniconda.html) package manager. Once you have conda, you can simply run:

pip install numpy
pip install pandas
pip install rdkit
pip install tensorflow==2.0.0
pip install keras==2.3.1
pip install matplotlib
pip install sklearn

The Transformer model has recently ushered in transformative advancements in the field of natural language processing. Additionally, it has demonstrated remarkable utility in chemistry through the utilization of a textual representation known as the simplified molecular input line system (SMILES), which encodes molecular and chemical reactions. These studies clearly indicate that the Transformer model possesses the capability to acquire knowledgepertaining to organic chemistry and chemical reactions by analyzing SMILES.

# Files
data/: Contains the data used for the experiments in the paper. 
d_rxn_predictionCNN.ipynb:Contains the code for the CNN model 

# run

