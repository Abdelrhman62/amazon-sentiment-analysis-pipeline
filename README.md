# Amazon Reviews Sentiment Analysis Pipeline

## Overview
This project integrates big data technologies to analyze Amazon customer reviews for sentiment classification. The pipeline is built using Apache Spark and Logistic Regression, offering a scalable solution for handling large-scale textual data.

## Features
- Preprocessing of large-scale text data.
- Sentiment classification (positive/negative).
- Scalable implementation using Apache Spark.
- Open-source contribution for community adoption.

## Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Abdelrhman62/amazon-sentiment-analysis-pipeline.git
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset:**
   - The dataset can be found [here on Kaggle](https://www.kaggle.com/datasets/yacharki/amazon-reviews-for-sa-binary-negative-positive-csv).
   - Place the dataset in a folder named `data/` within the project directory.

## Usage

1. **Run the Pipeline:**
   Execute the entire pipeline (preprocessing, training, and evaluation) using the following command:
   ```bash
   python project_Amazon.py
   ```

2. **Outputs:**
   - **Metrics**: Accuracy, precision, recall, and F1-score.
   - **Visualizations**: Accuracy by class, confusion matrix, and word cloud.
   - Outputs are saved in the `results/` folder.

## Results
The pipeline achieved the following metrics on the test dataset:
- **Accuracy**: 74%
- **Precision**: 73%
- **Recall**: 75%
- **F1-Score**: 74%

These results demonstrate the model's effectiveness in classifying Amazon reviews.

### Visualizations
The following visualizations provide insights into the dataset and model performance(View them in the paper):

#### Accuracy by Class

#### Confusion Matrix

#### Word Cloud of Text Data


## Ethical Considerations
- The dataset used in this project was anonymized, ensuring no personally identifiable information (PII) is present.
- Potential biases in sentiment classification due to language or cultural variations are acknowledged and may impact results.
- Safeguards were implemented during preprocessing to avoid overfitting and biased model predictions.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or feedback, please reach out:
- **Email:** ab.akram@nu.edu.eg
- **GitHub:** [Abdelrhman62](https://github.com/Abdelrhman62)
