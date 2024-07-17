<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/cd21f26b-a70a-4511-b170-96c171ff7eb5" width="350" style="margin-right: 10;"></td>
    <td><h1 style="margin: 0;">Enhancing Explainability in Fake News Detection: A SHAP-Based Approach for Bidirectional LSTM Models</h1></td>
  </tr>
</table>


## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Example Output](#example-output)
8. [Contributing](#contributing)
9. [License](#license)
10. [Author](#author)

## Introduction
Fake news detection has become a crucial task in the era of digital information. Identifying and mitigating the spread of misinformation is essential for maintaining the integrity of information ecosystems. This project focuses on enhancing the explainability of fake news detection models using SHAP (SHapley Additive exPlanations) to interpret Bidirectional LSTM (BiLSTM) models.

The goal is to provide a transparent and interpretable model that can help in understanding the underlying factors contributing to the classification of news articles as real or fake. By leveraging SHAP values, we aim to highlight the most influential features in the decision-making process, thus aiding in the explainability of the model.

## Dataset
The dataset used in this project includes labeled news articles, containing both fake and real news. Each sample is preprocessed to extract relevant features for model training and evaluation.

## Features
- Data preprocessing and feature extraction
- Implementation of Bidirectional LSTM model
- Model interpretability using SHAP
- Visualization of SHAP values for feature importance

## Technologies Used
- Python 3.x
- Jupyter Notebook
- TensorFlow/Keras
- Scikit-learn
- Pandas
- Numpy
- SHAP
- Matplotlib
- Seaborn

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/Fake-News-Detection-SHAP-BiLSTM.git
    cd Fake-News-Detection-SHAP-BiLSTM
    ```

2. **Create a virtual environment:**
    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment:**
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

4. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook SHAP_BiLSTM_Model.ipynb
    ```

2. **Run the cells in the notebook to preprocess the data, train the BiLSTM model, and evaluate the results.**

## Example Output
Here are some example outputs from the project:
- **Model Accuracy:** 94.5%
- **SHAP Summary Plot**

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

See the LICENSE file for details. [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## Author
For any questions or suggestions, please contact:
- Harsh Singh: [harshjuly12@gmail.com](mailto:harshjuly12@gmail.com)
- GitHub: [harshjuly12](https://github.com/harshjuly12)
