# Calories_Advisor_App

Gen AI Project

This project leverages Google Generative AI to create an application that calculates the total calories in food items from an uploaded image. Users can upload an image of their meal, and the app will provide a breakdown of the calories for each item, along with the total calorie count.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [License](#license)

## Features
- Upload an image of a meal
- Generate a detailed breakdown of calories for each food item in the image using Google Generative AI
- Display the total calorie count of the meal
- Simple and intuitive Streamlit interface

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Calories_Advisor_App.git
    cd Calories_Advisor_App
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up your Google API key:
    - Create a `.env` file in the project directory.
    - Add your Google API key to the `.env` file:
      ```
      GOOGLE_API_KEY=your_google_api_key
      ```

## Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. In the Streamlit interface:
    - Upload an image of your meal using the file uploader.
    - Click on "Tell me the total calories" to get a detailed breakdown and total calorie count for the meal.

## Requirements

- Python 3.x
- streamlit
- google-generativeai
- python-dotenv
- Pillow (PIL)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
