# House Price Prediction System

A web application that predicts house prices in Bangalore using a machine learning model. Users can input area, BHK, bathrooms, and location to get an estimated price.

## Features

- Predicts house prices based on user input
- Interactive web interface
- Built with Python (Flask), HTML, CSS, and JavaScript
- Pre-trained machine learning model

## Project Structure

```
BHP/
  client/         # Frontend files (HTML, CSS, JS, images)
  model/          # Jupyter notebook, model pickle, and columns info
  server/         # Flask backend, static and template files
```

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction/BHP
```

### 2. Install Dependencies

Navigate to the `server` directory and install required Python packages:

```bash
cd server
pip install flask numpy pandas scikit-learn
```

### 3. Run the Flask Server

```bash
python server.py
```

The server will start at `http://127.0.0.1:5000/`.

### 4. Access the Web App

Open `client/app.html` in your browser, or set up the Flask server to serve the frontend.

## Usage

1. Enter the area in square feet.
2. Select the number of BHK and bathrooms.
3. Choose a location.
4. Click "Estimate Price" to get the predicted house price.

## Model

- Trained using data from Bangalore real estate listings.
- Model and columns are stored in the `model/` and `server/artifacts/` directories.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Developed by 
Shrikant Wadkar
📧 shrikantwadkar100@gmail.com
🔗 https://github.com/ShrikantWadkar14

## Screenshots
![Screenshot 2025-06-19 173414](https://github.com/user-attachments/assets/a21258af-f74e-4736-816c-cdb930a6d788)
![Screenshot 2025-06-19 173515](https://github.com/user-attachments/assets/e911d221-d95c-4dfd-b9f5-56428a27b049)
![Screenshot 2025-06-19 173442](https://github.com/user-attachments/assets/193a87f6-8feb-46c5-b520-eab33c6bc1cc)




