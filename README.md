
# Calorie Calculation with Machine Learning and Augmented Reality

This project consists of two repositories:

Android App: An application that uses augmented reality (AR) to scan food items and calculate their calorie content.
Backend (Machine Learning API): A Jupyter notebook that contains the machine learning model and serves an API for calorie predictions based on image input.
1. Android App
Description
The Android app leverages AR technology to scan food items and estimate their calorie content using machine learning. The app provides an intuitive interface, allowing users to visualize the food they are scanning while seamlessly interacting with the calorie prediction backend.

Features
AR Scanning: Uses the device's camera to scan food items in real-time.
Calorie Prediction: Integrates with the backend machine learning API to fetch calorie estimations based on the scanned food image.
User-Friendly UI: Easy-to-navigate interface with real-time feedback.
Screenshots
(Add your Android app screenshots here)

2. Backend (Machine Learning API)
Description
The backend is a Jupyter notebook that contains a machine learning model trained to predict calorie content from food images. The final cell of the notebook serves as the API endpoint, which the Android app communicates with to get calorie estimates.

How to Run the API
Clone the repository containing the Jupyter notebook.
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Open the Jupyter notebook and run all the cells. The final cell serves as the API, which listens for requests from the Android app.
The API returns a JSON response with calorie information based on the input image.
API Usage
Input: Image of food
Output: JSON response with predicted calories


Contact
For any issues or questions regarding the project, feel free to contact me at sumitbhamare007@gmail.com