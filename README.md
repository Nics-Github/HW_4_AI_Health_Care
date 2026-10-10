

The only files you need to consider to get started are: hw_4.pdf, hw_4.jupytr and hw_4.qmd



# Load the environment

Environment for this project created with conda. Install conda [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html). 

## Loading environment option 1
Load  hw_4_AI_Health.yml for the conda environment. 

```
conda env create -f hw_4_AI_Health.yml

conda activate hw_4_AI_Health
```

## Loading environment option 2. 
If you are not using conda, you can load the required packages with the requirements.txt file. In a terminal in your working directory run. 

Install Python Version 3.11

```
# 1. Create the environment
python3.11 -m venv .hw_4_AI_Health
# or in windows py -3.11 -m venv .hw_4_AI_Health

# 2. Activate it (macOS/Linux)
source .hw_4_AI_Health/bin/activate

# 3. Install the requirements
pip install -r requirements.txt
```

## Option 3 

Open the .jupytr document in a Google Colab and have Gemini help you install the correct packages. 


