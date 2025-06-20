<h1 align="center">🚀 AI-Powered Career Guidance Platform</h1>

<p align="center">
An intelligent and interactive Streamlit-based career recommendation system that personalizes career suggestions, analyzes job markets, builds roadmaps, and offers live chat support — powered by OpenAI and SerpAPI.
</p>

---

## 📁 Project Structure


CARRER GUIDANCE AI AGENT/
│
├── .env # Environment variables (OpenAI & SerpAPI keys)

├── app.py # Main Streamlit app entrypoint

├── career_chatbot.py # Chat assistant logic with RAG capabilities

├── career_guidance_system.py # Core engine: analysis, search, roadmap generation

├── requirements.txt # Python dependencies

├── README.md # Project documentation

└── pycache/ # Python cache files


---

## 🎯 Features

| Feature | Description |
|--------|-------------|

| 🔍 Career Discovery | Explore trending careers with detailed overviews and insights |

| 📊 Market Analysis | Analyze job demand, regions, and industry growth |

| 📚 Personalized Learning Path | AI-generated roadmaps with skills, tools, and courses |

| 🧠 Skills Assessment | Interactive radar chart based on user ratings |

| 💬 Live Chat Assistant | GPT-powered assistant with RAG + SerpAPI |

| 📈 Real-time Data Fetching | Web search powered by SerpAPI |

| 🌐 Fully Responsive UI | Streamlit UI with beautiful dark mode |

---

## 🎥 Demo

> **Live interaction with the AI assistant recommending roles, paths, and trends.**

![Demo GIF](https://user-images.githubusercontent.com/demo-career-ai-guide.gif)

---

## 📊 Sample Visuals

### 🧠 Skills Radar Chart
![Radar Chart Placeholder](assets/radar_chart.png)

---

### 📍 Job Market Region Chart
![Market Region Graph Placeholder](assets/job_market_graph.png)

---

### 🗺️ Roadmap Example
![Learning Path Placeholder](assets/roadmap_example.png)

---

## 🛠️ Tech Stack

- **Frontend/UI:** Streamlit + HTML/CSS + Plotly

- **AI Backend:** OpenAI GPT (text generation, embeddings)
 
- **Search API:** SerpAPI (Google Search integration)
 
- **Vector Store:** FAISS for semantic document retrieval (RAG)
 
- **Data Viz:** Plotly Radar Charts, Bar Graphs  

---

## 🧪 How It Works

1. **User Inputs:**  
   Name, Education, Experience, Skill Ratings  

2. **Career Selection:**  
   Explore careers by categories (Tech, Healthcare, Creative, etc.)  

3. **Analysis Generation:**  
   Career overview, learning roadmap, job market insights  

4. **Live Chat Assistant:**  
   Ask “What does a Data Scientist do?” or “Best careers in AI?”


## ⚙️ Setup Instructions


### 🧾 Clone the Repository :

git clone https://github.com/your-username/ai-career-guidance-platform.git

cd ai-career-guidance-platform

**📦 Install Requirements: 

pip install -r requirements.txt:

🔐 Create .env File


OPENAI_API_KEY=your_openai_api_key
SERPAPI_KEY=your_serpapi_key
🚀 Run the App : 
streamlit run app.py


🔐 Environment Variables : 

Variable	Description

OPENAI_API_KEY	OpenAI GPT API key for responses & embeddings

SERPAPI_KEY	SerpAPI key for real-time job market analysis


📦 Requirements: 

streamlit

openai

faiss-cpu

python-dotenv

requests

plotly


💡 Future Enhancements : 

✅ Persistent login + profile saving

✅ Export PDF/CSV of career reports

🔜 Integration with LinkedIn data

🔜 Course recommendations (Coursera, Udemy, etc.)

🔜 Resume Analyzer & Job Fit Score

🤝 Contributing: 

Want to improve this?

💡 Open an issue

🛠️ Fork and submit a pull request

💬 Suggest new features via GitHub Discussions

📜 License: 
This project is licensed under the MIT License – use freely with proper attribution.

🙌 Acknowledgements:

OpenAI

SerpAPI

Streamlit

Plotly



