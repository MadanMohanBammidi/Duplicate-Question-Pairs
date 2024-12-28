# Duplicate Question Pairs Detection

This project aims to identify duplicate question pairs using machine learning techniques. It utilizes various text processing methods and models to determine if two questions are duplicates.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Suggestions](#suggestions)

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/MadanMohanBammidi/Duplicate-Question-Pairs.git
   cd your-repo-name
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the necessary datasets and models:
   - Download the dataset from [Quora Duplicate Questions](https://www.kaggle.com/c/quora-duplicate-questions/data) and place it in the appropriate directory.
   - The model and CountVectorizer will be saved as `model.pkl` and `cv.pkl` respectively after training.

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Open your web browser and navigate to `http://localhost:8501` to access the application.

3. Enter two questions in the input fields and click the "Find" button to check if they are duplicates.

## Files

- `app.py`: The main application file that runs the Streamlit web app.
- `helper.py`: Contains helper functions for text processing and feature extraction.
- `model.pkl`: The trained machine learning model for predicting duplicates.
- `cv.pkl`: The CountVectorizer used for converting text data into numerical format.
- `.ipynb_checkpoints/`: Contains Jupyter Notebook checkpoints for exploratory data analysis and model training.

## Suggestions

- Consider adding more advanced models (e.g., BERT) for better accuracy.
- Implement additional preprocessing steps to handle more complex text inputs.
- Add unit tests to ensure the reliability of your functions.
- Create a more detailed user guide or tutorial for users unfamiliar with the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.