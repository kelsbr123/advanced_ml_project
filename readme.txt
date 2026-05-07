1. 

2. Python was used for this project

3. This code is structured as a Jupyter Notebook. You will need an environment capable of running a Jupyter Notebook to run it, such as VSCode with the Jupyter extension, or head to https://jupyter.org/try-jupyter/lab/ to run it in a browser. Each cell in the notebook holds a different function or chunk of code. The cells at the bottom of the notebook are the only cells that actually execute, and everything above them is function declarations.

4. To run this notebook:
    1. Run these commands:
        python3 -m venv .venv
        source .venv/bin/activate
        pip install -r requirements.txt //NOTE: This will take a while since pytorch, which is used in this project, is a very large library
    2. Open the notebook
    3. Select the virtual environment as the notebooks kernel
    4. Execute the cells in the notebook that are not for parameter search
        //NOTE: The parameter search cells are at the bottom of the notebook that train the model take a long time to run. Be prepared to wait unless running this on a very large computer
        IF: Torch cannot find a cuda device: The notebook can be run in CPU mode, but training is much slower
    