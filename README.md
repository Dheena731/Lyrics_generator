 # 🎶 Lyrics Generator Web App

 A web application that generates song lyrics based on a selected genre, language, and user-provided description. This project uses Flutter for the frontend and interacts with an API for generating lyrics.

# 🌟 Features
Select from various genres (e.g., Pop, Rock, etc.)
Supports different languages
Input custom descriptions to generate personalized song lyrics
Loading animation while lyrics are being generated
Responsive design and hosted on Vercel for easy access

# 🚀 Demo
Live App Demo
You can access the live version of the app hosted on Vercel at this link: [https://your-app-url.vercel.app](https://lyrics-generator-qeb75c95k-dheena731s-projects.vercel.app/)


# 🛠️ Tech Stack
Frontend: Flutter

Backend API: Python (REST API)
Hosting: Vercel (Frontend), Render (Backend)

# 📋 Installation
To run this project locally, follow these steps:

## Prerequisites
Flutter SDK
Node.js and npm (required for Firebase or Vercel deployments)

## Steps
Clone the repository:

<pre/>git clone https://github.com/Dheena731/lyrics-generator-app.git
 cd lyrics-generator-app </pre>

# Install dependencies:

<pre/>flutter pub get </pre>

## Run the app:

<pre/>flutter run </pre>

For deployment, ensure you have set up your environment variables or configurations as per Vercel or Firebase requirements.

# 🔗 API Integration
The web app interacts with the Lyrics Generation API, which allows you to generate song lyrics based on genre, language, and description.

## Example API Call
Here’s how the API is structured:

<pre/>
GET /?genre=pop&lang=english&description=man%20in%20sorrow </pre>

### The API requires three parameters:

genre – The genre of the song (e.g., pop, rock, etc.)
lang – The language of the lyrics (e.g., English)
description – A custom description that guides the lyrical content

# 👥 Collaborators

This project was developed collaboratively. Special thanks to:

(Elango)[https://github.com/elango-ela] – Created the Lyrics Generation API that powers the backend.

(Dhinakaran)[https://github.com/Dheena731] – Developed the frontend in Flutter and handled the deployment on Vercel.

## ⚠️ Common Issues

### CORS Issues
You might encounter CORS-related issues when trying to access the API from other networks. If this happens, ensure you’re using a CORS proxy or contact the API provider for adjustments.

### Error 403 (Forbidden)
If you're seeing a 403 error on certain networks but it works fine on your local network, check if there are any IP restrictions on the API server, or verify CORS policies.
