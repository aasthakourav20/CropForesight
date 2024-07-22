# CropForesight 
CropForesight is an advanced website designed to assist farmers and agriculture enthusiasts in making smart choices about which crops to grow on their land. It achieves this by using special computer programs that can learn from data and environmental information. These programs take into account factors like soil nutrients, rainfall, pH levels, and weather conditions. With all this data, CropForesight can accurately predict the best crop to cultivate, helping farmers maximize their productivity and yield. It's like having a knowledgeable farming expert to guide you towards success!

## Features

- Intelligent crop recommendation based on soil composition, rainfall, pH, potassium, humidity, and temperature.
- User-friendly interface to input land and environmental parameters.
- Efficient machine learning model leveraging Gaussian Naïve Bayes algorithm.
- Responsive frontend developed using ReactJS for seamless user experience.
- Scalable backend powered by FastAPI for quick data processing.
- The platform can analyze historical agricultural data to identify trends and patterns, aiding in better decision-making for future crops.
- CropForesight can utilize its data analysis capabilities to predict and warn users about potential pest and disease outbreaks, allowing for timely preventive measures.
- By integrating real-time weather data, CropForesight can provide up-to-date recommendations, adapting to sudden changes in weather patterns for better accuracy.

By using various parameters like Nitrogen, Phosphorous, Potassium, rainfall, humidity, temperature and pH it predicts the most optimal crop for the land from among 22 crops ranging from rice or apples to cotton or lentils using a Gaussian Naive Bayes model

<br>

![Screenshot (339)](https://github.com/user-attachments/assets/7ff1e933-bea0-4bdf-a0e1-82a5f7d34ed2)

## Table of Contents
1. [Technologies Used](#technologies-used)
2. [Running the Project Locally](#runnning-the-project-locally)

## Technologies Used:

<h3 align="center">HTML, CSS, Javascript, ReactJS ,FastAPI , scikit-learn ,Pandas ,NumPy </h3>

 <h1 align="center">Usage</h1>

To experience the power of CropForesight, follow these simple steps:

✅ Visit the CropForesight website


✅ Enter the required details such as soil nitrogen value, phosphorus value, rainfall, pH, potassium, humidity, and temperature.

✅ Click on the "Recommend Crop" button to generate the optimal crop recommendation.

✅ Explore the recommended crop and gain insights into its suitability for your land.

## Running the Project Locally

If you want to  run it locally for development purposes, follow these steps:

1. Clone the frontend repository:

   ```sh
   git clone https://github.com/abhijeet141/CropForesight-FrontEnd.git
   ```

2. Change to the project directory:

   ```sh
   cd CropForesight-FrontEnd
   ```

3. Install the required dependencies:

   ```sh
   npm install
   ```

4. Run the frontend:

   ```sh
   npm start
   ```

5. Clone the backend repository:

   ```sh
   git clone https://github.com/abhijeet141/CropForesight_BackEnd.git
   ```

6. Change to the CropForesight_BackEnd directory:

   ```sh
   cd CropForesight_BackEnd
   ```

7. Install the required dependencies:

   ```sh
   pip install -r requirements.txt
   ```
8. Run the backend:

```sh
 uvicorn main:app --reload
````





