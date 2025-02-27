# Stroke-Prediction

This is a **Flask-based web application** that uses machine learning models to predict the likelihood of a stroke based on various health factors. The app provides a simple, interactive interface for users to input health data and receive predictions about their stroke risk.

## Features

- **Input Form**: Users can input health-related features like age, hypertension, heart disease, smoking habits, and more.
- **Model**: The application uses a **Voting Classifier** ensemble method to make predictions based on a trained model.
- **Real-time Predictions**: Based on the user inputs, the app will display real-time stroke risk predictions.

## Tech Stack

- **Backend**: Python, Flask
- **Machine Learning**: scikit-learn (Voting Classifier)
- **Web**: HTML, CSS, JavaScript

## Installation

### Prerequisites
- Python 3.x
- pip (Python's package installer)

### Steps to Run Locally

1. **Clone the Repository**:
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/stroke-prediction-flask.git
   cd stroke-prediction-flask
   ```

2. **Create and Activate Virtual Environment**:
   It's recommended to use a virtual environment to manage dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```

3. **Install Dependencies**:
   Install the required dependencies from `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   Start the Flask development server:
   ```bash
   python app.py
   ```

   The app will be running locally at `http://127.0.0.1:5000/`.

## How It Works

1. The user enters their health information (e.g., age, hypertension status, heart disease status, etc.) through the web form.
2. When the user submits the form, the Flask app uses the trained **Voting Classifier** model to predict the likelihood of the user having a stroke.
3. The app returns the prediction result, providing the user with feedback on their stroke risk.

## Contributing

Feel free to fork the repository, open issues, or submit pull requests if you'd like to contribute improvements or bug fixes.

## License

This project is open-source and available under the [MIT License](LICENSE).
