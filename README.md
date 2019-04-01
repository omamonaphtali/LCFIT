# Stochastic mortality modelling using the Lee-Carter model
The aim of the project is to forecast Kenyan mortality using the Lee-Carter model for mortaity. This model was proposed by Lee and Carter in 1992 and has since then been successfully used in forecasting the mortality of the United States of America.

## Data & Literature
### Data
So far, I am using the demographic data from Sweden as obtained from the Human Mortality Database https://www.mortality.org/ for the purposes of model development and testing.
The specific dataset is the 1x5(1-year age interval with 5-Calendar Years interval) death rates.

Upon completion of the model development, I am going to apply the model on Kenyan mortaity data as obtained from the Insurance Regulatory Authority (Kenya).

All data resides within the 'datasets' folder

## Technical Specifications
### Installing the dependencies
I used python 3 for the following project on a Linux-based operating system (Ubuntu 18.04 Bionic Beaver). The language used is Python 3.7.1. However, it is also possible to model the same using the R statistical software with some adjustments to the code.

Open the terminal and run the command:
`pip install -r requirements.txt`

You may be prompted to install other dependencies not included in the requirements.txt file. When that happens, consent to it.

PS. Don't forget to initialize an environment :)
Clear for take off!!

### Running the code
My code editor of choice is the Microsoft VS Code. I installed the pylint and jupyter notebook extensions for ease of use. Alternatively, you can just use the browser-based Jupyter notebook.
To open VS Code or Jupyter Notebook, browse into the folder where your files reside. While within this folder, launch the terminal and enter the command `code .` to launch VS Code or `jupyter notebook` to launch the notebook on the default browser. Both should open almost immediately.
