AI-Powered Code Reviewer

This project is an AI-powered code reviewer built with React and Node.js. Users can write code on the left side of the page, and the AI's response is displayed on the right side.

---

Setup Instructions:

1. Clone the repository:
   git clone https://github.com/Yash251203/CodeReviewer.git

2. Navigate to the project directory:
   Ex:- cd ai-powered-code-reviewer

3. Install dependencies:
   - For npm:
     npm install

4. Set up environment variables:
   - Create a .env file in the root of the project using the provided .env.example file.
     cp .env.example .env
   - Open the .env file and replace the placeholder values with your actual credentials.

   Example:
   GOOGLE_GEMINI_KEY=your_google_gemini_key_here

5. Run the project:
   - For development mode:
     npm run dev

---

Dependencies:

- Node.js (required version)
- google-auth-library (for handling authentication with Google services)
- express (for the web server)
- dotenv (for loading environment variables)
