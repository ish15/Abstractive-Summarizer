# Abstractive-Summarizer
A bidirectional LSTM model to make abstractive summaries

Overview
The Abstractive Summarizer is a project that leverages language modeling techniques, specifically bidirectional LSTM, to generate abstractive summaries of text. The project includes data cleaning, tokenization, vocabulary sorting based on count, and employs models for data generation. Two encoding methods, Greedy Search and Beam Search, are utilized for predicting upcoming words in the generated summaries.

Features
Bidirectional LSTM for language modeling.
Data cleaning, tokenization, and vocabulary sorting.
Greedy Search and Beam Search encoding methods.
Dataset: CNN-Dailymail News Text Summarization.
License: Apache 2.0.
Installation
To install the Abstractive Summarizer, follow these steps:

Clone the repository: git clone https://github.com/your-username/abstractive-summarizer.git
Navigate to the project directory: cd abstractive-summarizer
Install dependencies: pip install -r requirements.txt
Usage
Prepare your dataset: Download and preprocess the CNN-Dailymail News Text Summarization dataset.
Run data cleaning and preprocessing scripts.
Train the bidirectional LSTM model using the prepared data.
Use the trained model for abstractive summarization.
Explore and experiment with Greedy Search and Beam Search encoding for predictions.
bash
Copy code
# Example commands
python data_preprocessing.py
python train_model.py
python generate_summary.py --input_text "your_input_text_here"
Contributing
We welcome contributions! If you want to contribute to the Abstractive Summarizer project, please follow these guidelines:

Fork the repository.
Create a new branch for your feature: git checkout -b feature-name
Commit your changes: git commit -m 'Description of the changes'
Push to the branch: git push origin feature-name
Open a pull request.
License
This project is licensed under the Apache 2.0 License - see the LICENSE file for details.

Acknowledgments
We would like to express our gratitude to the authors of the CNN-Dailymail News Text Summarization dataset.
