# Wine country classification

## Getting started
```
python3 -m venv venv
source venv/bin/activate # for linux/mac
venv\Scripts\activate # for windows
pip install -r requirements.txt
```

Open `tree.ipynb`, and make sure the python installtion in ./venv is selected as the kernel.
- For VSCode, click the python version in the top right -> "Select another kernel" -> "venv"

Then run all cells in `tree.ipynb`. 
This will generate some visualisation, and run various models, namely a decision tree, neural network (w hyperparameters), and BERT (and LLM) for generating embeddings and classifying these using a RandomForestClassifier
