Steps to install visual studio code and setup:

1. To install the visual studio code, go to this link and download the IDE:

https://visualstudio.microsoft.com/downloads/

2. Install the Python Extension for the Visual Studio code from the extension tab in Visual Studio Code

3. Similary, install the Jupyter Notebook Extension



Steps to create a virtual environment for the project using conda (if you have any other virtual environment manager, create your virtual environment and activate it and follow step 4)

# 1. Change directory to the 'codes' directory
cd /path/to/codes

# 2. Create a Conda virtual environment named 'deap_venv' with Python 3.8
conda create -n deap_venv python=3.8

# 3. Activate the newly created virtual environment
conda activate deap_venv

# 4. Install the required Python packages listed in 'requirements.txt'
pip install -r requirements.txt