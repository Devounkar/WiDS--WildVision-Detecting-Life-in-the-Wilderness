# WiDS--WildVision-Detecting-Life-in-the-Wilderness

Week 1 – Learn Python & Data Science Basics
Goal: Transition from C++ to Python and get comfortable with data handling.
Learning Topics:
Python basics: variables, loops, conditionals, and functions
Lists, dictionaries, and arrays
Using numpy and pandas for data operations
Reading/writing CSV files
Basic plotting with matplotlib
Mini Tasks:
Write small programs to get used to Python syntax
Load a simple dataset (e.g., Iris or Titanic) and explore it
Plot a bar chart or scatter plot
End-of-Week Goal:
Comfortable writing Python scripts and handling tabular data.
Week 2 – Introduction to Images and OpenCV
Goal: Learn how computers represent and process images.
Learning Topics:
What is an image (pixels, RGB, grayscale)?
Reading, displaying, and saving images using OpenCV
Image resizing and cropping (maintaining aspect ratio)
Drawing grids (lines, rectangles) on images
Mini Tasks:
Load and display a few images
Resize an image to 800×600
Draw an 8×8 grid over the image
End-of-Week Goal:
Understand how to manipulate and visualize images in Python.
Week 3 – Feature Extraction & Data Preparation
Goal: Convert image regions into numerical data for ML.
Learning Topics:
Concept of “features” in computer vision
Extracting features:
Color histograms
Edge detection (Sobel/Canny)
Texture statistics (mean, std, contrast)
Dividing images into 8×8 grids and computing features for each cell
Mini Tasks:
Write a Python function that extracts features for one image
Store features for all grid cells into a CSV file
Visualize how different cells vary in feature values
End-of-Week Goal:
Create a feature dataset ready for training machine learning models.
Week 4 – Machine Learning Basics
Goal: Build and train models to identify wildlife regions.
Learning Topics:
Introduction to Machine Learning and classification
Training and testing data
Algorithms: Logistic Regression, Random Forest, SVM
Model evaluation: Accuracy, Precision, Recall, F1-score
Mini Tasks:
Train a simple ML model on your extracted features
Test it on unseen data and check performance metrics
Save the trained model using pickle
End-of-Week Goal:
Have a trained ML model capable of classifying wildlife-containing regions.
Week 5 – Integration & Output Generation
Goal: Apply your model on new images and generate final outputs.
Learning Topics:
Loading a trained model and making predictions on new images
Highlighting detected wildlife cells visually on the image
Generating a final output CSV file (ImageFileName, c01…c64)
Mini Tasks:
Apply your model to all images in the dataset
Highlight the 8×8 grid cells that contain wildlife
Export the final CSV file with predictions
End-of-Week Goal:
A fully functional wildlife detection system that takes images as input and outputs visual results and CSV predictions.
