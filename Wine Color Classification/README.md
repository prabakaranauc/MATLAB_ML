# Wine Color Classification with Machine Learning

This MATLAB program is designed to classify wines as red or white based on various parameters using machine learning algorithms. It utilizes a dataset provided in a TXT file containing several features such as acidity levels, sugar content, and alcohol percentage, along with the color of the wine. The program employs different machine learning models to train on this dataset and evaluates their performance to determine the best model for accurate classification.

## Dataset (This dataset is provided courtesy of MathWorks)
The dataset used in this program is stored in `Wine_Multiclass_Color_classification.txt`. It consists of the following parameters:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality
- Color (response variable)

## Features
- **Machine Learning Models**: SVM (Support Vector Machine), Decision Tree, and Random Forest are implemented to perform the classification.
- **Evaluation Metrics**: The accuracy of each model is measured on a testing dataset to assess its performance.
- **Cross-Validation**: The dataset is split into training and testing sets using stratified holdout cross-validation to ensure unbiased evaluation.

## Usage
1. **Installation**: Ensure you have MATLAB installed on your system.
2. **Clone or Download**: Clone or download this repository to your local machine.
3. **Dataset Placement**: Place the dataset file (`Wine_Multiclass_Color_classification.txt`) in the same directory as the MATLAB script.
4. **Run the Script**: Open MATLAB and execute the `wine_classification.m` script.
5. **View Results**: The program will display the accuracy of each machine learning model and indicate the best-performing model based on the evaluation metrics.

## License
This program is licensed under the GNU General Public License v3.0. You are free to use, modify, and distribute this software under the terms of the license. See the [LICENSE](LICENSE) file for more details.

## Support and Feedback
For any questions, issues, or feedback regarding this program, please feel free to [open an issue](https://github.com/yourusername/yourrepository/issues) on GitHub. Your input is highly appreciated and will contribute to the improvement of this project.
