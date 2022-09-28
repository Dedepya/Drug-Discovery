# Drug-Discovery
Developed by @Dedeepya Yarlagadda

# Description
Drug discovery and development pipelines are long, complicated and depend on several factors. Machine learning (ML) approaches offer a set of tools for improving discovery and decision-making for well-defined issues with lots of good data. ML can be used at any step of the drug development process. Target validation, the discovery of prognostic biomarkers, and the analysis of digital pathology data in clinical trials are just a few examples. The context and technique of the applications varied, with some producing precise forecasts and insights. The lack of interpretability and reproducibility of ML-generated findings, which may restrict their use, is one of the main difficulties of using ML. Systematic and thorough high-dimensional data are still required in all domains. With further attempts to address these challenges, as well as increased knowledge of the elements required to validate ML techniques, the use of ML can encourage data-driven decision making and has the potential to speed up the drug research and development process while lowering failure rates.

# Environment
- Google Colab
- System Modules
- Numpy
- Pandas
- Dataframe
- Scikit Learn
- Chemistry
- Matplotlib
- Linear Regression

# Setup
! wget https://repo.anaconda.com/miniconda/Miniconda3-py37_4.8.2-Linux-x86_64.sh 

! chmod +x Miniconda3-py37_4.8.2-Linux-x86_64.sh 

! bash ./Miniconda3-py37_4.8.2-Linux-x86_64.sh -b -f -p /usr/local 

! conda install -c rdkit rdkit -y 


# Dataset
Dataset was extracted from https://raw.githubusercontent.com/dataprofessor/data/master/delaney.csv

# Output
Experimental LogS vs Predicted LogS
![Screenshot (218)](https://user-images.githubusercontent.com/48832097/192740465-4803c3e5-34a0-4b61-b8f0-855d6e798ec9.png)

