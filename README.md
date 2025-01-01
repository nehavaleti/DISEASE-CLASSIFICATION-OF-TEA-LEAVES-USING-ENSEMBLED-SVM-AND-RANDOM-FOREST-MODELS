# DISEASE-CLASSIFICATION-OF-TEA-LEAVES-USING-ENSEMBLED-SVM-AND-RANDOM-FOREST-MODELS


## Overview
This project, developed as part of VIT's Capstone Project, focuses on classifying and predicting tea leaf diseases and deficiencies using an ensemble machine learning approach. By leveraging advanced techniques in machine learning and deep learning, the project aims to provide an automated system for precision agriculture, aiding in early detection and optimized resource utilization.

## Features
- **Automated Detection**: Identifies diseases and deficiencies in tea leaves.
- **Feature Extraction**: Utilizes MobileNetV2 for efficient feature extraction.
- **Ensemble Classification**: Combines Random Forest and Support Vector Machine (SVM) models for enhanced classification.
- **Precision Agriculture**: Contributes to early detection, improving agricultural decision-making and resource management.

## Methodology
1. **Data Collection**:
   - Images of tea leaves were collected from agricultural datasets and field samples.
   - Labels were assigned based on disease type or deficiency.

2. **Data Preprocessing**:
   - Images were resized and augmented to increase variability.
   - Normalization techniques were applied to standardize input data.

3. **Feature Extraction**:
   - MobileNetV2, a lightweight convolutional neural network, was used to extract high-level features from images.

4. **Classification**:
   - Random Forest and Support Vector Machine models were ensembled to classify the extracted features.
   - Hyperparameter tuning was performed to optimize performance.

5. **Evaluation**:
   - Metrics such as accuracy, precision, recall, and F1-score were used to evaluate the system.
   - Cross-validation ensured robustness of the models.

## Results
- The ensemble approach demonstrated significant improvement in classification accuracy compared to standalone models.
- Early detection of diseases and deficiencies was achieved, contributing to improved agricultural outcomes.

## Tools and Technologies
- **Programming Languages**: Python
- **Libraries**: TensorFlow, scikit-learn, NumPy, Pandas
- **Models**: MobileNetV2, Random Forest, Support Vector Machine (SVM)
- **Other Tools**: Jupyter Notebook, Matplotlib for visualization

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository/tea-leaves-classification.git
   ```
3. Run the training script:
   ```bash
   python tester3.py
   ```
4. Test the model with sample images:
   ```bash
   python tester3.py --image_path sample.jpg
   ```

## Dataset
- The dataset includes labeled images of tea leaves.
- Since the dataset is a huge file, The Link to it is provided "https://drive.google.com/drive/folders/1AQJ9cWz3lOUxaslunDQ8j21xemTX7k3P?usp=sharing"

## Future Work
- Integration with IoT devices for real-time field monitoring.
- Expansion to classify a wider range of crop diseases and deficiencies.
- Development of a mobile application for farmers.

## Contributions
This project was developed by Neha Valeti and team as part of VIT's Capstone Project.

## Acknowledgments
- Thanks to Vellore Institute of Technology (VIT) for the opportunity to work on this project.
- Gratitude to mentors and collaborators for their guidance and support.
