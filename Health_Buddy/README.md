# Health Buddy - AI-Powered Health Assistant

**Team Name:** Cypher Chasers  


**Category:** AI-Native Healthcare Experience

---

## 📌 Overview

Health Buddy is an intelligent health assistant designed to provide personalized health insights and guidance. In today's fast-paced world, people often struggle to understand their health metrics and make informed decisions about their well-being. Health Buddy bridges this gap by offering an AI-native experience that interprets health data and provides actionable, easy-to-understand insights.

Our solution transforms complex health information into clear, personalized recommendations, making health management more accessible and effective for everyone.

---

## ❓ Problem Statement

Current health applications often fall short because they:

* Present raw data without meaningful interpretation
* Lack personalized insights based on individual health profiles
* Have complex interfaces that are difficult to navigate
* Don't provide real-time, contextual health guidance
* Fail to maintain conversation context during health-related discussions

As a result, users are left with data but lack clear understanding of what it means for their health.

---

## 💡 Our Solution

Health Buddy is an AI-native web application that provides:

* Personalized health insights based on user data
* Natural language processing for health-related queries
* Context-aware health recommendations
* Secure and private health data handling
* Intuitive interface for tracking and understanding health metrics

---

## ✨ Key Features

* **AI-Powered Health Analysis**
  Advanced algorithms analyze health data to provide personalized insights.

* **Natural Language Interaction**
  Users can ask health-related questions in plain language.

* **Session-Based Context**
  The system maintains context during conversations for more relevant responses.

* **Secure Data Handling**
  User health data is processed with privacy and security as top priorities.

* **Responsive Design**
  Works seamlessly across desktop and mobile devices.

---

## 🏗️ System Architecture

### High-Level Architecture

```
┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│   Frontend   │ ◄──►│   Backend    │ ◄──►│   AI Service  │
│  - Web UI    │     │  - Express   │     │  - OpenAI API │
│  - User Input│     │  - Sessions  │     │  - Reasoning  │
└──────────────┘     └──────────────┘     └──────────────┘
```

### Technology Stack

**Frontend**
* HTML5, CSS3, JavaScript
* Responsive design for all devices
* Interactive UI components

**Backend**
* Node.js with Express
* Session management with node-cache
* RESTful API architecture

**AI Integration**
* OpenAI API for natural language processing
* Context-aware response generation
* Custom prompt engineering

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (included with Node.js)
- OpenAI API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/health-buddy.git
   cd health-buddy
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the backend directory with:
   ```
   OPENAI_API_KEY=your_openai_api_key
   PORT=3000
   ```

4. **Start the backend server**
   ```bash
   npm start
   ```

5. **Open the frontend**
   Open `frontend/index.html` in your web browser

---

## 📂 Project Structure

```
Health_Buddy/
├── backend/               # Backend server code
│   ├── aiService.js       # AI service integration
│   ├── app.js            # Express application setup
│   ├── server.js         # Server entry point
│   ├── sessionManager.js # Session management
│   └── responseGenerator.js # Response generation logic
└── frontend/             # Frontend files
    └── index.html        # Main application interface
```

---

## 👥 Team Cypher Chasers

* **Akansh** 
* **Ashish Rautela** 
* **Sahil Negi** 
* **Naitik Dhiman** 

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

## 📧 Contact

For any inquiries, please reach out to our team at team@cypherchasers.tech
