# E-CycleAI
AI-powered electronic waste cycle for efficient E-Waste management (SDG 12)  
EcycleAI/  
│── frontend/        # React.js + Tailwind CSS (Web App)  
│   ├── src/  
│   │   ├── components/  # Reusable UI components  
│   │   ├── pages/       # Different pages/screens  
│   │   ├── assets/      # Images, logos, icons  
│   │   ├── utils/       # Helper functions  
│   │   ├── App.js       # Main app component
│   │   ├── index.js     # Entry point
│   ├── public/          # Static files
│   ├── package.json     # Dependencies & scripts
│── backend/         # Node.js + Express.js API
│   ├── src/
│   │   ├── models/      # Database models (e.g., users, e-waste items)
│   │   ├── routes/      # API endpoints
│   │   ├── controllers/ # Business logic
│   │   ├── middleware/  # Authentication & security
│   │   ├── config/      # Firebase & database configuration
│   │   ├── app.js       # Main Express app
│   │   ├── index.js     # Entry point
│   ├── .env             # Environment variables
│   ├── package.json     # Backend dependencies
│── ai-model/        # AI-based e-waste recognition
│   ├── dataset/     # Training dataset
│   ├── model/       # Trained AI model (TensorFlow / Vertex AI)
│   ├── scripts/     # Python scripts for training & testing
│   ├── main.py      # Main AI processing script
│── cloud/           # Google Cloud & Firebase Integration
│── README.md
│── .gitignore
│── .env             # Secrets & API keys
│── package.json
