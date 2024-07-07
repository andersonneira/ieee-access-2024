
# A Novel Ensemble of outlier identification techniques for DDoS attack prediction

## Authors

- Anderson B. de Neira [abneira@inf.ufpr.br](https://scholar.google.com/citations?user=v6KDZ4oAAAAJ&hl=en)

- Ligia F. Borges [ligiaborges@dcc.ufmg.br](https://scholar.google.com/citations?user=w2vZypkAAAAJ&hl=en)

- Michele Nogueira [michele@dcc.ufmg.br](https://scholar.google.com/citations?user=1CfmgaAAAAAJ&hl=en)


## Abstract

Text


## Datasets
- [Exp 1](https://mcfp.felk.cvut.cz/publicDatasets/CTU-Malware-Capture-Botnet-51)
- [Exp 2](https://mcfp.felk.cvut.cz/publicDatasets/CTU-Malware-Capture-Botnet-52)
- [CICDDoS2019](https://www.unb.ca/cic/datasets/ddos-2019.html)

## Folder and Files descriptions
#### 1. requirements.txt: versions of the libraries used in the experiments.

#### 2. Experiment_1: This folder contains the data and the scripts related to Experiment 1 reported in the article.
- data.csv: This file contains the original data collected in Capture-51 of the CTU-13 dataset. Furthermore, this file contains the preprocessed data used in the prediction.
- label.csv: This file contains the label of the second that bots send two or more packets. 
- script.ipynb: This file contains the code used in Experiment 1 to evaluate the ELUCIDATION technique on the CTU-13 dataset (capture-51). 

#### 3. Experiment_2: This folder contains the data and the scripts related to Experiment 2 reported in the article.
- data.csv: This file contains the original data collected in Capture-52 of the CTU-13 dataset. Furthermore, this file contains the preprocessed data used in the prediction.
- label.csv: This file contains the label of the second that bots send two or more packets. 
- script.ipynb: This file contains the code used in Experiment 2 to evaluate the ELUCIDATION technique on the CTU-13 dataset (capture-52). 

#### 4. Experiment_3: This folder contains the data and the scripts related to Experiment 3 reported in the article.
- data.csv: This file contains the original data collected in CICDDoS2019 dataset. Furthermore, this file contains the preprocessed data used in the prediction.
- label.csv: This file contains the label of the second that bots send two or more packets. 
- script.ipynb: This file contains the code used in Experiment 3 to evaluate the ELUCIDATION technique on the CTU-13 dataset (capture-52). 




## Install packages
```
pip3 install -r requirements.txt
```    
## Install Jupyter
```
pip install jupyterlab
``` 

See more on [Jupyter docs](https://jupyter.org/install)

## Instructions to execute the scripts

##### 1. Open the Jupyter 
```
jupyter notebook
```
##### 2. Browser de ELUCIDATION technique folder

##### 3. Open the experimentation script

##### 4. Run all cells

## Usage of Python Virtual Env [Optional]

##### 1. Create a Virtual Env
```
python3 -m venv .venv
```

##### 2. Activate Virtual Env
```
source .venv/bin/activate
```


##### 3. Deactivate Virtual Env
```
deactivate
```

See more on [Python docs](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)