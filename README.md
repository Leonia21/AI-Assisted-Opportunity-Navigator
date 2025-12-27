# 🚀 AI-Assisted Opportunity Navigator

An AI-powered web application that helps students discover internships, fellowships, scholarships, and programs based on their skills, interests, and academic year, with explainable recommendations and an AI career assistant.

---

## 🧠 Problem Statement

Students often miss valuable opportunities due to:

- Information scattered across multiple platforms  
- Lack of personalized guidance  
- Confusion about eligibility and deadlines  

This project solves these issues by providing a centralized, personalized, and explainable opportunity navigator.

---

## ✨ Key Features

### 🎯 Personalized Recommendations
- Matches opportunities using skills, interests, academic year, and deadlines

### 📊 Explainable Scoring System
- Transparent, rule-based logic
- Clearly explains why an opportunity is recommended

### 💬 AI Career Assistant (Mistral)
- Provides natural-language guidance
- Helps when no exact matches are found

### 🔐 Privacy-Friendly & Offline AI
- Runs locally using Ollama
- No APIs
- No internet dependency

### 🎨 Modern UI
- Built with Streamlit
- Custom dark neon theme

---

## 🛠️ Tech Stack

- **Frontend / App Framework:** Streamlit  
- **Backend Logic:** Python  
- **AI Model:** Mistral (LLM)  
- **AI Runtime:** Ollama  
- **Data Handling:** Rule-based logic & Python dictionaries  

---

## 🤖 How AI Is Used

- AI is used only for conversational guidance  
- Opportunity recommendations are generated using rule-based logic  

This ensures:
- No hallucinations  
- Fair and explainable results  
- Responsible AI usage  

---

## 🦙 What is Ollama?

Ollama is a local AI runtime that allows the application to run the Mistral language model locally, without cloud APIs or API keys.

**Flow:**
User → Streamlit App → Ollama → Mistral → Streamlit → User

---

## 📂 Project Structure

├── app.py              
├── README.md          
└── requirements.txt  


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/your-repo-name.git

cd your-repo-name

### 2️⃣ Install Dependencies

pip install streamlit requests

### 3️⃣ Install & Run Ollama
Download from:

https://ollama.com

Pull the Mistral model:
ollama pull mistral

Start the Ollama server:
ollama serve

### 4️⃣ Run the Application

---

## 🧪 How It Works

1. User selects skills, interests, and academic year  
2. System calculates relevance score using rules  
3. Opportunities with ≥ 50% match are displayed  
4. AI assistant provides career guidance  

---

## 🎯 Use Cases

- College students searching for internships  
- Women in tech looking for scholarships and fellowships  
- Students exploring AI, research, or social impact roles  
- Hackathons and academic demonstrations  

---

## 🏆 Why This Project Stands Out

- Explainable AI  
- Open-source friendly  
- Privacy-first (local AI)  
- Solves a real-world student problem  
- Clean, demo-ready UI  

---

## 🚧 Future Enhancements

- Resume-based matching  
- Real-time opportunity scraping  
- User accounts and bookmarks  
- ML-based scoring alongside rules  

---

## 👩‍💻 Team & Hackathon

Built as part of the **Build With AI Hackathon**, focusing on responsible AI and real-world student impact.

---

## 📜 License

This project is for educational and hackathon purposes.
