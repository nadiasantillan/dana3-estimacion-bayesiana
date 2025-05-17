### Run R from a Jupyter Notebook

1. In R console run:
    
    install.packages('IRkernel')
    IRkernel::installspec()

1. From Visual Studio Code
    1. Select Kernel
    2. Select Another Kernel...
    3. Jupyter Kernel...
    4. R


### Run Python from a Jupyter Notebook

1. Create a virtual environment with name .venv

    python -m venv .venv

1. Activate the virtual environment

    source .venv/bin/activate

1. Install dependencies

    pip install -r requirements.txt

    