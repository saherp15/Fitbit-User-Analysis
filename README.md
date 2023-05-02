# Fitbit-User-Analysis

This code loads a dataset of Fitbit logs and demonstrates some basic operations on the data using NumPy library. The Fitbit data is loaded from a file named fit.txt using the numpy.loadtxt() function. The data contains 96 rows and 6 columns.

## Dependencies
This code requires the following dependencies:
* NumPy

## How to Run
* Install the dependencies.
* Download the fit.txt file using the gdown command.
* Run the code.

## Code Explanation
The code does the following:
1. Load the fit.txt data using the numpy.loadtxt() function and stores it in a NumPy array named fitbit.
2. Prints the first 5 rows of the dataset using array slicing.
3. Prints the shape of the fitbit array.
4. Transposes the fitbit array, extracts the first row (which contains the dates), and prints it.
5. Transposes the fitbit array again, extracts the first two rows (which contain the dates and steps), and prints them.

## Note
The code uses the gdown command to download the fit.txt file from Google Drive. If you don't have gdown installed, you can manually download the file and place it in the same directory as the code.
