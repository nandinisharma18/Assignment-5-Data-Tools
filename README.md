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

### Step 1: Clone the Repository (If Git is Installed)
i. Open your command prompt (Windows) or terminal (Mac/Linux).

ii. Use the git clone command to copy the project files onto your computer. 

This will create a folder on your computer containing all the project files.

### Step 2: Download as a ZIP File (If Git is Not Installed)
i. If Git is not installed, don’t worry! You can download the project files directly.

ii. Go to the repository page in your browser and find the Code button (usually a green dropdown button).

iii. Click the Code button and select Download ZIP from the dropdown menu.

iv. Save the ZIP file to your computer and extract it to a folder using any file extractor (e.g., Windows File Explorer or macOS Archive Utility).

### Step 3: Open Jupyter Notebook
i. Launch Jupyter Notebook by opening Anaconda Navigator and clicking on the Jupyter Notebook option. This will open Jupyter in your default web browser.

ii. In the Jupyter Notebook interface, navigate to the folder where you cloned or extracted the project files.

iii. Find the file named Assignment4-100942268-Intro to Data.ipynb and double-click it to open it.

### Step 4: Run the Code
i. Once the notebook is open, you will see blocks of code called cells.

ii. To execute a cell, click inside it and either: Press Shift + Enter on your keyboard, or Click the Play button in the toolbar at the top of the page.

iii. Follow this process for each cell, running them one by one in the order they appear.

# Explaining Code in Brief
## Installing the libraries
Install these required libraries using pip
### Breakdown of Neural Network Classifier 
Among the options, the following are selected: hidden_layer_sizes=(5, 4, 5) balancing model complexity, activation='relu'allows faster training by preventing the vanishing gradient problem, solver='adam'optimizer adapts the learning rate, requiring minimal tuning, max_iter=10000 which means training runs for up to 10,000 iterations, stopping early if the model converges, random_state=100 ensures reproducibility by controlling random number generation. The performance of the model is assessed through the confusion matrix and the classification report.el using a confusion matrix and classification report.
### Decision Tree Classifier
The DecisionTreeClassifier is set with random_state=100 for reproducibility, ensuring consistent results across runs.

Model performance is evaluated using two key metrics:

i. Confusion Matrix: This shows the comparison between predicted and actual values, highlighting true positives, true negatives, false positives, and false negatives.

ii. Classification Report: This includes precision (accuracy of positive predictions), recall (ability to identify positive cases), and F1-score (balance between precision and recall), along with support (class distribution).

## Contributing

So, it is crucial to conclude that everyone can contribute to research to support the ideas of community members. If you'd like to contribute to this project, please follow these guidelines:

i. Fork the repository: Create a personal copy of the project repository to work on.

ii. Create a new branch: For each contribution, start by creating a new branch to make your changes, ensuring the main branch remains stable.

iii. Make your changes: Edit the necessary documents, code, or content to improve the project.

iv. Test your changes: Thoroughly test your updates to ensure they work as expected and do not introduce errors.

v. Submit a pull request (PR): Once you're confident with your changes, submit a pull request and provide a clear description of the modifications you've made.


## Authors

* **Nandini**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Rejoy James, Professor DATA 1202-03 DATA ANALYSIS TOOLS ANALYTICS
