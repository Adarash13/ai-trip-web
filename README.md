<h1 style="font-size: 2.5em;">🌐 Full-Stack AI Trip Planner Web App</h1>

A full-stack web application that helps users plan their trips by providing **AI-powered recommendations** for travel itineraries, places to visit, and hotels. This app integrates **Google Generative AI** for dynamic travel planning, **Firebase** for data storage and user authentication, and the **Google Places API** for fetching real-time place data.

[🚀 Live Demo](https://ai-trip-web-seven.vercel.app/)

---

 📌 Table of Contents

- [Technologies](#Technologies)
- [Features](#features)
- [Folder Structure](#folder-structure)
- [Prerequisites](#prerequisites)
- [Installation & Usage](#installation--usage)
- [Example Use Case](#example-use-case)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

 💻 Technologies

 Frontend

- **React.js** – For building UI components
- **Tailwind CSS** – For styling and responsive design
- **Axios** – For handling API requests

 Backend & Services

- **Google Generative AI API** – Generates travel recommendations and itineraries
- **Google Places API** – Fetches place/hotel details and images
- **Firebase Firestore** – Stores user trip data
- **Firebase Authentication** – Handles user authentication with Google OAuth

---

 🚀 Features

- ✨ **AI-Powered Travel Plans** – Personalized itineraries using Google Generative AI
- 🏨 **Hotel & Place Details** – Real-time info using Google Places API
- 🔐 **Secure Login** – Google OAuth via Firebase Authentication
- 📱 **Responsive UI** – Built using TailwindCSS
- 💾 **Persistent Data Storage** – Store user trips in Firestore
- 📅 **Day-wise Travel Itineraries** – Detailed plans with attractions, pricing, and duration

---

 📁 Folder Structure

```

ai-trip-planner/
├── public/
│   └── index.html
├── src/
│   ├── components/         # Reusable UI components
│   ├── pages/              # Home, Login, Dashboard, Planner, etc.
│   ├── services/           # Firebase and API configurations
│   ├── App.js              # Root app component
│   └── main.jsx            # Application entry point
├── .env.local              # API keys and configuration
├── tailwind.config.js      # Tailwind configuration
├── package.json            # Project metadata and dependencies
└── README.md               # Documentation

````

---

 🛠️ Prerequisites

To run this project locally, you’ll need:

- [Node.js & npm](https://nodejs.org)
- A [Firebase Project](https://firebase.google.com) with:
  - Firestore enabled
  - Authentication via Google OAuth
- [Google Cloud Console](https://console.cloud.google.com) API keys for:
  - Google Generative AI API
  - Google Places API

---

 ⚙️ Installation & Usage

1. **Clone the repository**

```bash
git clone https://github.com/your-username/ai-trip-planner.git
cd ai-trip-planner
````

2. **Install dependencies**

```bash
npm install
```

3. **Create a `.env.local` file**

```env
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
VITE_GENERATIVE_AI_API_KEY=your_generative_ai_key
VITE_GOOGLE_PLACES_API_KEY=your_places_api_key
```

> ⚠️ Do NOT commit this `.env.local` file to GitHub.

4. **Run the application**

```bash
npm run dev
```

5. **Build for production**

```bash
npm run build
```

---

 💡 Example Use Case

A user logs in via Google, selects a destination like **Tokyo** and a duration of **5 days**, and the app generates:

* A daily itinerary with activities, suggested times, and travel tips
* Hotel and attraction recommendations with photos and details
* Local insights and custom AI suggestions based on interests

---
 🤝 Contributing

Contributions are welcome and appreciated!

1. Fork the project
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add feature"`
4. Push to your branch: `git push origin feature-name`
5. Open a pull request on GitHub

---

 👤 Author

 Adarsh Sainath H

Developer of the Full-Stack Trip Planner Web App
[GitHub](https://github.com/Adarash13) | [LinkedIn](https://www.linkedin.com/in/adarsh-sainath-h-26baa5307/)

 Jayanthan B N

Developer of the Full-Stack Trip Planner Web App
[GitHub](https://github.com/Jayanthan23) | [LinkedIn](https://www.linkedin.com/in/jayanthan-b-n-792949276/)

---

 📄 License

This project is licensed under the [MIT License](LICENSE).

---

 🙏 Acknowledgements

* Google Cloud Platform – Generative AI & Places API
* Firebase – Firestore and Authentication
* Vercel – Hosting and deployment
* Tailwind CSS – Styling framework
* React Community & GitHub Contributors
