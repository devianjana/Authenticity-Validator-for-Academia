Authenticity Validator for Academia

This platform helps you verify academic certificates quickly and securely. Built with the MERN stack and a smart AI-powered OCR, it checks certificates, spots fake documents, and gives instant results to employers, schools, and government agencies.

---

Project Overview

Let’s face it — fake degrees and forged certificates are everywhere these days. It’s a headache for anyone trying to trust a document. Our system takes the hassle out of verification. Here’s how it works:

- Pulls out text from certificates using OCR
- Cross-checks info against the database
- Detects fraud
- Ready to plug in blockchain for future upgrades

Tech Stack

Frontend
- React.js

Backend
- Node.js
- Express.js

Database
- MongoDB

AI / OCR Engine
- Python
- FastAPI
- Tesseract OCR
- OpenCV

User Roles

Verifier
- Upload a certificate
- Enter its ID
- See if it’s real or fake

Institution
- Upload lists of certificates
- Keep track of what you’ve issued

Admin
- Check verification logs
- Spot fraud trends
- Manage users and the whole system

Core Features

- Secure login and role-based access
- Certificate upload and ID check
- Fast data extraction with OCR
- Real-time authenticity checks
- Smart fraud detection
- Admin dashboard for monitoring (and more if you want)
- Ready for blockchain integration down the line

authenticity-validator/

│

├── backend/

│   ├── server.js

│   ├── package.json

│   ├── .env

│   ├── models/

│   │     ├── User.js

│   │     └── Certificate.js

│   └── routes/

│         ├── authRoutes.js

│         └── certificateRoutes.js

│

├── ai-ocr/

│   ├── main.py

│   └── requirements.txt

│

├── frontend/

│   ├── package.json

│   └── src/

│         └── App.js

│

└── README.md

Here’s the layout for the authenticity-validator project. Everything’s pretty organized, so you can find what you need without much hassle. The backend folder has all the Node.js stuff — server setup, environment variables, models for users and certificates, plus routes for authentication and certificates. There’s a separate ai-ocr folder with Python code and its requirements, which handles the OCR side of things. Up front, the frontend folder has the React setup, with its own package.json and the main App.js. And of course, there’s a README.md at the root to get you started.
