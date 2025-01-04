# Zoo and Glass Classification Using KNN

## Overview
This project demonstrates the use of the K-Nearest Neighbors (KNN) algorithm to classify data in two datasets: the Zoo dataset and the Glass dataset. The Zoo dataset is used to classify animals based on various characteristics, while the Glass dataset classifies glass types based on chemical compositions. The project includes data preprocessing, model training, cross-validation, and performance evaluation.

## Datasets

1. **Zoo Dataset**:
   - The Zoo dataset is used for classifying animals into different categories based on various features like hair, feathers, legs, tail, and more.

2. **Glass Dataset**:
   - The Glass dataset contains chemical composition attributes like refractive index, sodium, magnesium, aluminum, silicon, potassium, calcium, barium, and iron. The target variable is the type of glass.

## Data Description

### Zoo Dataset:
- **Hair**: Whether the animal has hair (1) or not (0).
- **Feathers**: Whether the animal has feathers (1) or not (0).
- **Legs**: Number of legs the animal has.
- **Tail**: Whether the animal has a tail (1) or not (0).
- **Type**: The animal category (e.g., mammal, bird, reptile, etc.).

### Glass Dataset:
- **RI**: Refractive index
- **Na**: Sodium (weight percent in corresponding oxide)
- **Mg**: Magnesium
- **AI**: Aluminum
- **Si**: Silicon
- **K**: Potassium
- **Ca**: Calcium
- **Ba**: Barium
- **Fe**: Iron
- **Type**: Type of glass (e.g., building windows, containers, headlamps, etc.).

## Project Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/R-Mahesh45/zoo-glass-classification-knn.git
   cd zoo-glass-classification-knn
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook or Python script to start working with the data:
   ```bash
   jupyter notebook
   ```

## Workflow

### Zoo Classification Using KNN:

1. **Data Preprocessing**: Load the Zoo dataset, clean the data, and standardize the features.
2. **Model Training**: Train a KNN model using the Zoo dataset with an optimal number of neighbors (e.g., 5).
3. **Model Evaluation**: Evaluate the model performance using classification metrics like accuracy, precision, recall, and F1-score.
4. **Cross-Validation**: Perform cross-validation to assess the generalization ability of the model.

### Glass Classification Using KNN:

1. **Data Preprocessing**: Load the Glass dataset, clean the data, and standardize the features.
2. **Model Training**: Train a KNN model using the Glass dataset with an optimal number of neighbors (e.g., 9).
3. **Model Evaluation**: Evaluate the model performance using classification metrics like accuracy, precision, recall, and F1-score.
4. **Cross-Validation**: Perform cross-validation to assess the generalization ability of the model.

## Results

- **Zoo Dataset**:
    - Cross-validation training accuracy: **0.85**
    - Cross-validation test accuracy: **0.80**

- **Glass Dataset**:
    - Cross-validation training accuracy: **0.70**
    - Cross-validation test accuracy: **0.63**

## Conclusion

The KNN algorithm provides a solid approach for classification tasks in both the Zoo and Glass datasets. While the Zoo dataset provides a higher accuracy, the Glass dataset requires further exploration and fine-tuning to improve model performance.

## Contributing

Feel free to fork the repository, make changes, and submit pull requests. Contributions are always welcome!
