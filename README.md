# Workshop 1: Querying and data integration of genomic databases
### Repository for UH students to train the E-utilities from NCBI. 

This repository has been created to support the Workshop 1 (Querying and data integration of genomic databases) from the module Databases and Tools, in the MSc Bioinformatics. 

The environment.yml file has the basic instructions to build an environment where the E-utilities from NCBI are installed. If you are running these locally, you can always install these utilities manually by typing this in your terminal (considering you are using Linux or Unix)

``sh -c "$(curl -fsSL https://ftp.ncbi.nlm.nih.gov/entrez/entrezdirect/install-edirect.sh)"``

This repository also contains a Jupyter Notebook (ipynb file) which has the basic exercises for the workshop. If you want to run them online by free, you can use free online resources such as `Google Colab` or `GitHub Codespaces`. 

### In-class workshop

For the workshop in class, we will use [Binder](https://mybinder.org/). Visit this website and then copy the main address of this repository in Binder. 
The repository link should be: https://github.com/dmartimarti/UH_eutilities_training

Alternatively, you can always access a session by clicking [here](https://mybinder.org/v2/gh/dmartimarti/UH_eutilities_training/HEAD)

Let Binder build the site (it will take a bit), and then you should be able to access the Jupyter Notebook and a Linux terminal where to run your commands. 

When using Binder, please be aware of the following **LIMITATIONS**:
- **resources are limited**, you will get only 1 CPU and 2GB of RAM memory per session. Should be enough to run E-utilities commands.
- **Inactivity** for 10-15 minutes will automatically **terminate** your session.
- **Data** between sessions is **NOT stored**, so plan accordingly. 
- NCBI has a limit of 3 requests/second. It is unlikely we hit that limit, but to minimise this limit please **don't run many cells at the same time**, only one by one
