# COMP472_Project
## Prerequisites

- The project is set up to run with **Python 3.12**

- To avoid conflicts between our Python version and your current version, we set up and use a conda environment:

1. You will need to install Anaconda from:
   https://docs.anaconda.com/anaconda/install/
2. Create a conda environment with Python 3.12 from:

```
conda create --name comp472 python=3.12
```

3. Activate comp472 from:

```
conda activate comp472
```

4. Make sure that the Python version within your environment is 3.12 from:

```
python -V
```

## Getting Started
1. All pretrained models are stored in the "Models" folder on OneDrive: Models Folder[https://liveconcordia-my.sharepoint.com/:f:/r/personal/yih_l_live_concordia_ca/Documents/COMP472%20Project/Models?csf=1&web=1&e=h4Avcb].
2. Download and unzip the "Models" folder 
3. Open the "Models" folder. Inside, you will find another "Models" folder 
4. Move the inner "Models" folder to the same directory as the Final Submission.ipynb file. The path to a model should then look like ./Models/{pretrained_model}
5. Open Final Submission.ipynb in jupyter notebook
6. Since some code blocks are interdependent, we recommend running them in order to avoid errors. Alternatively, you can select "Run All" to execute all blocks.
