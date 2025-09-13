Agri-app

Agri-app is a comprehensive, AI-powered progressive web application designed to be a farmer's essential companion. It provides real-time weather information, AI-driven farming insights, soil analysis, and a community job board, all accessible from a single, responsive dashboard.

✨ Features

    Responsive Dashboard: A clean, button-like UI that makes navigation simple and intuitive on any device.

    Live Weather & 5-Day Forecast: Uses your device's location to provide real-time weather data and a 5-day outlook to help with planning.

    AI-Powered Tips: Generates personalized farming tips and watering schedules based on local weather conditions using the Gemini API.

    Soil & Crop Insights: Analyzes the soil in your area and recommends suitable crops for planting. This feature uses the Gemini API with Google Search grounding for accurate, up-to-date information.

    Farming Assistant: A conversational chatbot that can answer farming-related questions and provide advice. The assistant uses the Gemini API's search grounding to ensure its knowledge is current.

    Job Board: A community feature that allows users to post and view local agricultural job opportunities. This data is saved to a public Firestore database.

    Saved Recommendations: A personal space to save important tips or crop ideas, with data stored securely in a private Firestore database.

    Voice Control: A hands-free way to interact with the app. Users can use voice commands to activate specific features like "Get tips" or "Get soil."

💻 Technologies Used

    HTML: The core structure of the single-page application.

    CSS & Tailwind CSS: Provides all the styling and ensures a fully responsive, mobile-first design.

    JavaScript: Manages all client-side logic, API calls, and dynamic content rendering.

    Firebase: Provides backend services, including:

        Firestore: A real-time, cloud-based NoSQL database for saving and retrieving user-specific and public data.

        Firebase Auth: Handles user authentication to manage data securely.

    Google Gemini API: The large language model (LLM) that powers all AI features, including tips, insights, and the conversational chatbot.

    OpenWeatherMap API: A third-party service used to fetch weather and forecast data.

    Web Speech API: A browser API that handles the voice recognition functionality.

    Font Awesome: A library providing all the icons used throughout the app.

🚀 How to Run the Application

This is a single-file application that requires a local web server and an API key to function correctly.

    Save the file: Save the index.html file to your computer.

    Get an API key: Go to the Google AI Studio and get a new API key for the Gemini API.

    Update the code: Open the index.html file and find the line const apiKey = 'YOUR_API_KEY';. Replace 'YOUR_API_KEY' with the key you just generated.

    Run a local server: Open your terminal or command prompt, navigate to the folder where you saved the file, and run one of the following commands to start a simple web server:

        For Python 3: python3 -m http.server

        For Python 2: python -m SimpleHTTPServer

    Open in browser: In your web browser, go to http://localhost:8000. The application will now be fully functional.

Note: The app requires a local server to access external APIs due to browser security restrictions. Opening the file directly from your computer (file://) will not work.
