# MAGRE - A Multimodal and Multitask Approach for Adaptive Geospatial Region Embeddings
MAGRE builds adaptive spatial region embeddings that can be used in multiple downstream tasks.
# Prerequisites

* Python  >= 3.8
* pytorch

# Setup

1. Clone the repository
````
git clone https://github.com/Rajjat/MAGRE
cd MAGRE
````

2. Install the Python Requirements
```python
pip install -r requirements.txt
```

# Usage

```
python model.py # to train the model   
python model -tr embed # to generate the embeddings        
python regression_tasks.py # to run crime prediction and check-in prediction    
python3 landusage_classfication.py # to run the land use classification task
```  
# Environment 
The experiments were conducted using Ubuntu 22.04.2 LTS, utilizing a system equipped with 1TB RAM and 96 cores
