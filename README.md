# Face Recognition Brain

![](/client/demo.gif)

Welcome to the Face Recognition Brain! This full-stack application utilizes React and Express to implement an intelligent face recognition system. Users can detect faces within images, and their entry count increases every time a face is successfully identified.

## Description

The Face Recognition Brain is an innovative and cutting-edge application designed to detect faces within images using the power of face recognition technology. By providing the URL of an image, this intelligent system can accurately pinpoint and highlight faces present in the picture, revealing the individuals captured in the photograph.

## Key Features

- **Advanced Face Detection**: Utilizes state-of-the-art face recognition algorithms to analyze images and identify faces with remarkable precision. It can detect multiple faces within a single image and mark their positions for easy identification.

- **URL-Based Image Input**: Instead of uploading images directly, users can provide a URL to the image they want to analyze. This feature offers convenience and flexibility in processing images from various sources, such as social media platforms or cloud storage.

- **Real-Time Results**: The application processes images swiftly, providing real-time results on face detection. Users receive instant feedback on the presence and location of faces, enhancing the overall user experience.

- **Intuitive User Interface**: With a user-friendly interface, the Face Recognition Brain makes it easy for individuals of all skill levels to interact with the application effortlessly. The intuitive design ensures seamless navigation and a pleasant user journey.

## How to Use

1. **Provide Image URL**: To get started, simply enter the URL of the image you want to analyze for face detection.

2. **Start Face Recognition**: Click the "Detect" or "Recognize" button to initiate the face recognition process.

3. **Analyze the Results**: The application will swiftly process the image and identify faces within it. The detected faces will be highlighted or marked, enabling easy identification.

4. **User Entry Count**: Every time you successfully detect faces in an image, your entry count will be increased, adding a fun element to your experience with the Face Recognition Brain.

## Libraries Used (React)

| Library Name   | Description                           |
| -------------- | ------------------------------------- |
| React Js       | Frontend Framework                    |
| react-tilt     | Parallax tilt effect for images       |
| particles-bg   | Particle animation for background     |
| react-toastify | Toast notifications for user feedback |

## Libraries Used (Express)

| Library Name       | Description                                         |
| ------------------ | --------------------------------------------------- |
| Express            | Backend Framework                                   |
| bcrypt-nodejs      | Hashing passwords for user authentication           |
| body-parser        | Parse incoming request bodies                       |
| clarifai           | Face recognition API library                        |
| cors               | Enable Cross-Origin Resource Sharing                |
| express-rate-limit | Limit requests to the server                        |
| helmet             | Secure Express apps by setting various HTTP headers |
| mongoose           | MongoDB object modeling for Node.js                 |

## Tools Used:

| Tool Name | Description          |
| --------- | -------------------- |
| npm       | Package Manager tool |

# Installation and Usage Guide

## Fork the Repository

Click the "Fork" button at the top right corner of the page. This will create a copy of the repository under your GitHub account.

### Installation (Client)

1. **Clone the Client Repository**

   ```bash
   git clone https://github.com/your-username/smart-brain
   ```

2. **Navigate to the client directory**

   ```bash
   cd client
   ```

3. **Install the client dependencies using npm**

   ```bash
   npm install
   ```

4. **Start the client development server**

   ```bash
   npm start
   ```

This will start the client application on your computer's local development server, accessible at `http://localhost:3000`

### Installation (Server)

1. **Navigate to the server directory**

   ```bash
   cd server
   ```

2. **Create a `.env` file in the root directory** and add the following configurations:

   ```env
   MONGO_URI='YOUR_MONGO_URI'
   API_KEY='YOUR_CLARIFAI_API_KEY'
   ```

Replace the placeholder values `<YOUR_MONGO_URI>` and `<YOUR_CLARIFAI_API_KEY>` with your actual MongoDB URI and Clarifai API key. You can obtain these keys from

- [MongoDB URI](https://www.mongodb.com/)
- [Clarifai API Key](https://docs.clarifai.com/clarifai-basics/authentication/app-specific-api-keys/)

3. **Install the server dependencies using npm**

   ```bash
   npm install
   ```

4. **Start the server**

   ```bash
   npm start
   ```

This will start the server on your computer's local development server, accessible at `http://localhost:8080`

## ScreenShots

# Home Page:

![App Screenshot](/client/src/Screenshots/Home.png)

# Face Recognition Page:

![App Screenshot](/client/src/Screenshots/FaceRecognition.png)
