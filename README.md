# Assignment-5-Data-Tools

Neural Networks, inspired by biological neural networks, mimic the way the brain processes information. In the brain, neurons receive inputs via dendrites, integrate them in the cell body, and transmit outputs through axons to other neurons. Artificial Neural Networks (ANNs) replicate this using interconnected nodes, where each node processes inputs, applies a weighted sum and bias, passes the result through an activation function, and produces an output. These nodes are organized into layers: an input layer for raw data, hidden layers for transformations, and an output layer for predictions.

The simplest ANN, the single-layer perceptron, models linear relationships. Each neuron in the perceptron calculates a weighted sum of inputs and applies an activation function to determine the output. While effective for simple tasks, perceptrons are limited to linear problems, driving the evolution of multi-layer networks capable of handling complex, non-linear data, forming the backbone of modern deep learning systems.

## Getting Started

This document provides step-by-step instructions to help you set up and execute the project on your local machine. It is assumed that users have a foundational knowledge of programming, with Python being the preferred programming language for this project. For students or users without prior Python experience, it is advised to familiarize themselves with the basics of Python before proceeding. Along with setup instructions, this document includes a detailed section on how to deploy the project in a live system, providing insights into ensuring smooth integration and functionality in real-world environments. These deployment guidelines will help you transition the project from a development setup to a fully operational state.


## Prerequisites

What things do you need to install the software and how to install them

```
1. GIT (Optional)
2. ANACONDA NAVIGATOR
3. DATASET TO RUN THE NEURAL NETWORK ALGORITHM
```

# Installation 

To set up your environment, follow these simple steps:

### Go to the Anaconda website:
Open your web browser and visit https://www.anaconda.com/download. This is where you can find the software needed for this project.

### Download the installer:
On the download page, choose the version that matches your operating system. You can select Windows, macOS, or Linux depending on the computer you are using. Once selected, click the download button to save the installer file to your computer.

### Install Anaconda:
After the file is downloaded, locate it in your "Downloads" folder and double-click on it to start the installation. Follow the on-screen instructions. You can keep the default settings unless you have specific preferences.

### Open the Anaconda application:
Once the installation is complete, look for the Anaconda application in your system. On Windows, you can find it in the Start Menu. On macOS or Linux, use the search feature to locate "Anaconda Navigator."

### Launch Jupyter Notebook:
Inside Anaconda Navigator, you will see several tools. Find and click on "Jupyter Notebook." This will open a new tab in your default web browser.

### Alternative way to open Jupyter Notebook:
If you prefer, you can search for "Jupyter Notebook" directly in your computer's search bar and click on it to open.

# Code Execution

1. Use a clone command that is Git clone ```git clone "the web URL"``` available by going to the Code option as a dropdown button.
2. The user can also choose the download zip option if the Git is not installed on the system.
3. Navigate to the Jupyter Notebook opened in your browser, browse the cloned or downloaded folder and double click on Assignment4-100942268-Intro to Data.ipynb.
4. Run the steps of the code by either using the shift + enter option on the keyboard or by clicking the play button on the toolbar.

# Explaining Code in Brief
## Installing the libraries
Install these required libraries using pip
### Breakdown of Neural Network Classifier 
Among the options, the following are selected: hidden_layer_sizes=(5, 4, 5) activation='relu' solver='adam' max_iter=10000 random_state=100 The performance of the model is assessed through the confusion matrix and the classification report.el using a confusion matrix and classification report.
### Decision Tree Classifier
Using DecisionTreeClassifier with argument random_state = 100. These metrics are confusion matrix and classification report in order to evaluate the model performance.

## Contributing

So, it is crucial to conclude that everyone can contribute to research to support the ideas of community members. If you'd like to contribute to this project, please follow these guidelines:

1. Fork this repository.
2. Open a new branch for your contribution.
3. Revise and edit your documents or articles.
4. Test your changes thoroughly.
5. Submit a pull request (PR) with a description of your change in details.


## Authors

* **Nandini**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Rejoy James, Professor DATA 1202-03 DATA ANALYSIS TOOLS ANALYTICS
