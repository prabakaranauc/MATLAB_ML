
# Fabric Defect Detection with Optimization

This MATLAB program compares the performance of various classifiers for multiclass classification in fabric defect detection using the TILDA dataset. It includes preprocessing steps, model training, evaluation, and comparison of classification algorithms.

## Table of Contents
1. [Introduction](#introduction)
2. [Usage](#usage)
3. [Dataset](#dataset)
4. [Dependencies](#dependencies)
5. [Instructions](#instructions)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction
The program aims to evaluate the effectiveness of different classification algorithms for fabric defect detection. It preprocesses the data, divides it into training and validation sets, trains various classifiers, evaluates their performance, and compares the results.

## Usage
1. Clone or download the repository to your local machine.
2. Ensure MATLAB is installed on your system.
3. Open MATLAB and navigate to the directory containing the MATLAB script (`fabric_defect_detection.m`).
4. Run the script in MATLAB to execute the classification and evaluation process.
5. View the results displayed in the MATLAB console.

## Dataset
The dataset used in this program is the TILDA dataset, stored in the file `IMPROVED_FABRICDATASET.xlsx`. It contains features related to fabric defects and is loaded into the program using MATLAB's `xlsread` function.

## Dependencies
- MATLAB (R2016a or later)

## Instructions
1. The program preprocesses the dataset by reading the data from the Excel file, normalizing it, and dividing it into training and validation sets.
2. Various classification models are trained using the training data and optimized using hyperparameter optimization.
3. The trained models are evaluated using the validation data, and performance metrics such as resubstitution loss, confusion matrix parameters, sensitivity, specificity, detection accuracy, false alarm rate, detection rate, and positive predictive value are calculated.
4. The results are displayed in the MATLAB console for comparison.

## Results
The program outputs the performance metrics of each classifier, including resubstitution loss, loss, confusion matrix parameters, sensitivity, specificity, detection accuracy, false alarm rate, detection rate, and positive predictive value. The results are displayed in tabular format for easy comparison.

## Contributing
Contributions to improve the program or add additional classifiers are welcome. Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the [GNU General Public License v3.0](LICENSE).

---

Feel free to customize the README according to your specific project details, such as adding more detailed usage instructions or providing information about the classifiers used.
