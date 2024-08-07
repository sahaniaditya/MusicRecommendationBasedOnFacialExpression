# Music Recommendation System based on Facial Emotion

## Team Members

- Aditya Sahani (B22CS003)
- Aditya Jaiswal (B22CS025)
- Gaurav Manish (B22CS079)

## Description

This project is a web application that recommends music based on the facial emotion of the user. It utilizes ReactJS for the frontend, Node.js and Express for the backend, and MongoDB for the database. Additionally, it integrates PyTorch and TensorFlow for facial emotion recognition.

The application allows users to register and authenticate securely. Once authenticated, users can upload their images, and the system will analyze their facial expressions to recommend suitable music tracks.

## Features

- User authentication: Secure registration and login system.
- Facial emotion recognition: Analyzes user's facial expressions to determine mood.
- Music recommendation: Recommends music tracks based on the detected emotion.
- Database integration: Stores user data and music preferences in MongoDB.
- Responsive design: Frontend is built using ReactJS, ensuring a seamless experience across devices.

![Home](https://github.com/sahaniaditya/MusicRecommendationBasedOnFacialExpression/blob/90f761a571b2ada63fc915a31c0e46785c60db50/Screenshot%202024-07-11%20092948.png)

![Recommendation](https://github.com/sahaniaditya/MusicRecommendationBasedOnFacialExpression/blob/d43073dcae17a170216e6dd008d0406f113c1145/Screenshot%202024-07-11%20093403.png)

## Installation

1. Clone the repository:<br>

- git clone https://github.com/username/MusicRecommendationBasedOnFacialExpression
.git<br>

2. Install dependencies for frontend and backend:<br>
- cd MusicRecommendationBasedOnFacialExpression
/frontend <br>
- npm install<br>

- cd ../backend <br>
- npm install


3. Configure environment variables:

   - Create a `.env` file in the `backend` directory.
   - Define the following variables:
     ```
     PORT=3001
     MONGODB_URI=your_mongodb_uri
     SECRET_KEY=your_secret_key
     ```

4. Start the frontend and backend servers:

cd ../frontend<br/>
npm run dev

cd ../backend<br/>
node index.js

## Usage

1. Register or log in to the application.
2. Upload an image containing your face.
3. Wait for the system to analyze your facial expression.
4. Receive music recommendations based on your mood.

## Technologies Used

- ReactJS
- Node.js
- Express
- MongoDB
- PyTorch
- TensorFlow

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes we are happy to accept your contributions.

## Contact

For any inquiries or support, please contact [Aditya Sahani](mailto:b22cs003@iitj.ac.in),[Aditya Jaiswal](mailto:b22cs025@iitj.ac.in), [Gaurav Manish](mailto:b22cs079@iitj.ac.in).



