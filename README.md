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
   - Place the dataset in the `data/` folder.

## Usage

1. **Preprocessing:**
   ```bash
   python preprocessing.py
   ```

2. **Training:**
   ```bash
   python training.py
   ```

3. **Evaluation:**
   ```bash
   python evaluation.py
   ```

## Results
- **Accuracy:** 74%
- **Precision:** 73%
- **Recall:** 75%
- **F1-Score:** 74%

### Visualizations
- Accuracy by Class
- Confusion Matrix
- Word Cloud

All visual outputs are stored in the `assets/` folder for reference.

## Ethical Considerations

1. **Bias in Dataset:**
   - The dataset may reflect biases inherent in user reviews (e.g., language variations, cultural differences).
   - Future iterations can include additional datasets to mitigate such biases.

2. **Data Privacy:**
   - All dataset rows were anonymized to ensure compliance with data privacy regulations (e.g., GDPR).
   - Preprocessing steps maintained strict safeguards to prevent exposing sensitive information.

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
- **GitHub:** Abdelrhman62(https://github.com/your-username)

