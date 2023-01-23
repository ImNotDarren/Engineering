# Engineering

## Table of Contents
- [Abstract](#link-part-1)
- [Design](#link-part-2)
- [Data](#link-part-3)
- [Algorithm](#link-part-4)
- [Tools](#link-part-5)
- [Communication](#link-part-6)
- [**How to run**](#link-part-7)

## <a name="link-part-1">Abstract</a>

Atrial fibrillation (AF) is the most frequent arrhythmia, and many people are suffering from atrial fibrillation. Usually people need to go to hospitals to be diagnosed which would take time and money. Now we're providing a model that can make early detection of AF based on your PPG signals. Users simply need to upload the data to our website, and they can get the predicted result.

## <a name="link-part-2">Design</a>

The project has three main parts: training and testing the model, building the front-end with React.JS, and building its back-end API with Flask. The front-end will receive a .cvs file uploaded from user, and post it to the Flask API. Flask will then load the file into a numpy array, checking if it's in the correct format. Then it will return the results to the front-end page, which will then plot all the signals users uploaded and show the classification results of all signals.

## <a name="link-part-3">Data</a>

The data is sourced from UCLA's clinical dataset. It's a huge dataset with more than 20GB of PPG signals recorded from different hospitals and devices.

## <a name="link-part-4">Algorithm</a>

## <a name="link-part-5">Tools</a>

* **Pandas** for exploratory data analysis
* **PyTorch** for building neural network
* **React.JS** for front-end development
* **React-plotly.js** for plotting
* **Spring Boot** and **Flask** for back-end development
* **AWS** for deployment

## <a name="link-part-6">Communication</a>

The project proposal is shown [here](/documents/proposal.md).

## <a name="link-part-7">How to run</a>

To view the webpage, visit [this link](https://blog.darren.com/publications)(not finished yet, may show an error page now).
