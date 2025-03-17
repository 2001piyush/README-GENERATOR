 

## 🚀 Introduction

README Genai is an AI-powered tool that simplifies the process of generating professional README files for your GitHub repositories. This application allows users to create comprehensive READMEs in three easy steps:

1. Authenticate with GitHub
2. Select your repository
3. Generate your README

With README Genai, you can streamline your documentation process and showcase your projects effectively.

## 🛠️ How We Built It

 

### Tech Stack

- **Frontend:**
  - React
  - TypeScript
  - Tailwind CSS
  - Vite (for build tooling)

- **Backend:**
  - Node.js
  - Express

- **AI Integration:**
  - Google Generative AI (Gemini Pro model)

- **Authentication:**
  - GitHub OAuth

- **Deployment:**
  - Vercel (frontend)
  - Render (backend)

## 🏃‍♂️ Running the Project Locally

To run README Genai on your local machine, follow these steps:

### Frontend Setup

1. Clone the frontend repository:
   ```
   git clone https://github.com/bhosalevivek04/readme_generator.git
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory with the following contents:
   ```
   VITE_GITHUB_API_URL=https://api.github.com
   VITE_GITHUB_CLIENT_ID=your_github_client_id
   VITE_GITHUB_REDIRECT_URI=http://localhost:3000/callback
   VITE_SERVER_URL=http://localhost:5000
   VITE_GOOGLE_API_KEY=your_google_api_key
   ```

4. Start the frontend development server:
   ```
   npm run dev
   ```

### Backend Setup

1. Clone the backend repository:
   ```
   git clone https://github.com/bhosalevivek04/readme_backend.git
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory with the following contents:
   ```
   GITHUB_CLIENT_ID=your_github_client_id
   GITHUB_CLIENT_SECRET=your_github_client_secret
   ```

4. Start the backend server:
   ```
   npm start
   ```

5. The backend server will run on `http://localhost:5000`.

## 🔑 API Keys Required

To run README Genai, you'll need the following API keys:

1. **GitHub OAuth App Credentials:**
   - Create a new OAuth App in your GitHub Developer Settings
   - Set the Authorization callback URL to `http://localhost:3000/callback` for local development
   - Use the provided Client ID and Client Secret in your environment variables

2. **Google AI API Key:**
   - Sign up for Google AI Platform and create a new project
   - Generate an API key for the Gemini Pro model
   - Use this key in your frontend environment variables

 

## 🤝 Contributing

README Genai is an open-source project, and we welcome contributions! If you'd like to contribute, please follow these steps:

1. Fork the repository (frontend or backend)
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


 
