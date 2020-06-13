# Machine Learning Basics

This repository contains the exercise files for the **Create machine learning models** learning path on [Microsoft Learn](https://docs.microsoft.com/learn)

## Before You Start

To complete the labs, you'll need the following:

- A Microsoft Azure subscription. If you don't already have one, you can sign up for a free trial at <a href ='https://azure.microsoft.com' target='_blank'>https://azure.microsoft.com</a>.
- A Visual Studio Codespace. This provides a hosted instance of Visual Studio Code, in which you'll be able to run the notebooks for the lab exercises. To set up this environment:
1. Open <a href = "https://online.visualstudio.com/environments/new?name=ml-basics&repo=MicrosoftDocs/ml-basics" target="_blank" rel="noopener">Visual Studio Codespaces</a> in a new browser tab; and if prompted, sign in using the Microsoft account associated with your Azure subscription.
2. Create a codespace with the following settings (if you don't already have a Visual Studio Codespaces billing plan, you'll be prompted to create one):
    - **Codespace Name**: *A name for your codespace - for example, **ml-basics**.*
    - **Git Repository**: MicrosoftDocs/ml-basics
    - **Instance Type**: Standard (Linux) 4 cores, 8GB RAM
    - **Suspend idle Codespace after**: 30 minutes
3. Wait for the codespace to be created. This will take around 3 minutes. You'll see the following things happen:
    - A script will initialize and configure your codespace.
    - A list of notebook (.ipynb) files will appear in the pane on the left.
4. After preparation is complete, you can close the **Welcome** and **Creation Log** panes. You can also change the color scheme to suit your preference - just click the **&#9881;** icon at the bottom left and select a new **Color Theme**. A light color theme is recommended to make it easier to read the Python code in the notebooks.

## Labs

After you've completed the setup steps above, you can use your Visual Studio Codespace to complete the labs. The notebooks in this project are tutorials that include notes and code to explain key concepts. Each notebook covers a specific topic, but if you are new to Machine Learning, you should complete them in order.

- **01 - Data Exploration.ipynb** examines some of the core Python techniques and packages used to explore and visualize data - a key element of data science and machine learning.
- **02 - Regression.ipynb** introduces *regression*, a form of *supervised* machine learning that predicts numeric values.
- **03 - Classification.ipynb** covers another form of *supervised* machine learning that is used to predict which category, or *class*, something belongs to.
- **04 - Clustering.ipynb** deals with *unsupervised* machine learning that seeks to group similar data entities together based on statistical similarities.
- **05a - Deep Neural Networks (PyTorch).ipynb** and **05a - Deep Neural Networks (TensorFlow).ipynb** introduce the key concepts of *deep neural networks (DNNs)* using your choice of two popular *deep learning* frameworks: PyTorch and Tensorflow.
- **05b - Convolutional Neural Networks (PyTorch).ipynb** and **05b - Convolutional Neural Networks (Tensorflow).ipynb** describe how to build *convolutional neural networks (CNNs)* for image classification - a common use of *deep learning*.

> **Note:** These labs assume you have some basic familiarity with Python syntax and core data types. If not, consider working through the [Take your First Steps with Python](https://docs.microsoft.com/learn/paths/python-first-steps/) learning path first.

## Contributing

We are not currently accepting external contributions for this repo. If you encounter any problems, please report an issue.
