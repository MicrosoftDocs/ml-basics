# Running the labs on your own computer

We highly recommend using a Visual Studio Codespace for these labs - this setup ensures the correct version of Python and the various packages you will need are installed.

If you prefer to work on the labs using your own computer, and you have experience configuring Python development environments, you can install the following tools and packages.

- **Python 3.7**. We recommend the [miniconda distribution](https://docs.conda.io/en/latest/miniconda.html).
- **Git**. You'll need to install the [Git command line client](https://git-scm.com/downloads) to clone this repo.
- **Visual Studio Code**. We recommend downloading [Visual Studio Code](https://code.visualstudio.com/Download) and using it as your Python development environment for these labs.

After installing these tools, you must configure your environment and download the lab files.

1. In Visual Studio Code, install and enable the [Microsoft Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python).
2. In Visual Studio Code, open a Python terminal and use the following `pip` commands to install the required packages in your Python 3.7 environment:

 ```bash
pip install jupyter
pip install matplotlib
pip install pillow
pip install requests
pip install numpy
pip install pandas
pip install scikit-learn
pip install scikit-image
pip install scipy
pip install torch==1.6.0+cpu torchvision==0.7.0+cpu -f https://download.pytorch.org/whl/torch_stable.html
pip install tensorflow 
 ```
3. In Visual Studio Code, run the `git clone` command and clone the repo at https://github.com/MicrosoftDocs/ml-basics to your local computer.
4. Open the cloned repo and use the notebooks it contains to complete the labs.