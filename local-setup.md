# Running the labs on your own computer

We highly recommend using an Azure Machine Learning compute instance for these labs - this setup ensures the correct version of Python and the various packages you will need are installed and that the environment has sufficient memory and compute resources to complete the exercises. 

If you prefer to work on the labs using your own computer, and you have experience configuring Python development environments, you can install the following tools and packages.

- **Python 3.7**. We recommend the [miniconda distribution](https://docs.conda.io/en/latest/miniconda.html).
- **Git**. You'll need to install the [Git command line client](https://git-scm.com/downloads) to clone this repo.
- **Visual Studio Code**. We recommend downloading [Visual Studio Code](https://code.visualstudio.com/Download) and using it as your Python development environment for these labs.

After installing these tools, you must configure your environment and download the lab files.

1. In Visual Studio Code, install and enable the [Microsoft Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python).
2. In Visual Studio Code, open a Python terminal and use `pip` to install the following packages in your Python 3.7 environment (you can use the `pip install` command to install them individually, or copy the following list into a *requirements.txt* file and use the command `pip install -r requirements.txt` to install them in a single step):

 ```bash
jupyter
matplotlib
pillow
requests
numpy
pandas
scikit-learn
scikit-image
scipy
 ```

3. In Visual Studio Code, run the `git clone` command and clone the repo at https://github.com/MicrosoftDocs/ml-basics to your local computer.
4. Open the cloned repo and use the notebooks it contains to complete the labs.

> **Note**: Due to the variety of possible local environment configurations, we can't support setup or resource issues when using the notebooks on your own computer. The notebooks have been tested in the recommended Azure Machine Learning compute instance environment.
