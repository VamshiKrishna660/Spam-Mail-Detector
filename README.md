# Spam Mail Detector

A machine learning-based Spam Mail Detector that classifies emails as spam or not spam using text analysis. The model is trained using a dataset of emails to identify patterns that distinguish spam messages from legitimate ones.

## Features
- Uses `TfidfVectorizer` for transforming text data into feature vectors.
- Implements logistic regression for classification.
- Filters out spam emails with high accuracy.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/spam-mail-detector.git
   cd spam-mail-detector


2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt

   
3. **Dataset:**
    - Dataset is in the CSV format with columns like Category (spam or not) and Message (email content).


## Project Structure
- train_model.py - Script to train the logistic regression model.
- test_model.py - Script to test the trained model's accuracy.
- spam_mail_detector.ipynb - Jupyter notebook for experimentation and visualization.
- data/ - Folder containing the dataset.
- models/ - Folder for saving trained models.


##Technologies Used
- Python for scripting and data handling.
- Scikit-learn for machine learning algorithms.
- Pandas for data processing.
- Numpy for numerical operations.

## License
  - This project is licensed under the MIT License.

## Acknowledgments
  - Deep learning guidance from Andrew Ng, founder of deeplearning.ai
  - Inspiration and learning support from the Siddhardhan YouTube channel.

