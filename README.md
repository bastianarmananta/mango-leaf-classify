# Mango Leaf Classification using SVM

This project focuses on developing an image classification model to distinguish between healthy and diseased mango leaves. The classification task is accomplished using the Support Vector Machine (SVM) algorithm. By exploring various hyperparameters, such as C and gamma, we fine-tuned the SVM model to achieve optimal performance.

To ensure reliable results, we employed the k-fold cross-validation technique. This technique helped us evaluate the model's effectiveness by dividing the dataset into k subsets and training and testing the model on different combinations of these subsets.

By successfully implementing the SVM algorithm for mango leaf classification, this project demonstrates our expertise in machine learning and showcases our ability to utilize SVM algorithms for image classification tasks.

## Installation

To install and run the project, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies using pip. You can do this by running the following command in your terminal:
`pip install -r requirements.txt`
3. Run the web app using the following command: `streamlit run app.py`
4. Access the web app by opening your web browser and navigating to `http://localhost:8501`.

## Usage

Just pop your text into the app and it'll sort the data for you. Or, if you've got a CSV file, upload it and the app will use 13 models to classify the data. The app will spit out a model that you can use for other stuff too.

## Example

Here's an example of how to use the web app:

1. Open your web browser and navigate to `http://localhost:8501`.
2. Drag and drop your image data.
3. Click the "Predict" to predict the image.

## Issues

There issues related to storages on this project.

## Acknowledgements

This project was built using scikit-learn and Streamlit framework.
