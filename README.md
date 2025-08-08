# 🌿 EcoMate – Agentic AI for Climate Action

EcoMate is an agentic AI application designed to help users make environmentally conscious travel decisions by providing:

- 🌦️ Real-time weather updates  
- 🌫️ Air Quality Index (AQI)  
- 🌱 Carbon footprint estimation  
- 🚲 Smart transport mode suggestions  
- ✅ Daily eco-action tracking  

> ⚡ Powered by **LangChain**, **OpenAI**, **Gradio**, and **OpenWeatherMap API**

---

## 🔍 Features

- ✅ Uses LangChain Tools + LLM to answer user queries  
- 📡 Fetches live weather and AQI data using OpenWeatherMap  
- 🧮 Calculates CO₂ emissions based on distance and transport mode  
- 💬 Smart transport suggestions based on distance and conditions  
- 🧠 Agent reasoning using zero-shot-react description  
- 🌍 Tracks whether you completed your daily climate-friendly action  

---

## 🛠️ Tech Stack

- Python (Google Colab or local)
- LangChain + LangChain-OpenAI
- OpenAI GPT models
- Gradio (for web UI)
- OpenWeatherMap API
- Requests, Faiss

---

## 🚀 How to Use

### 🔧 Option 1: Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/EcoMate-Agentic-AI.git
   cd EcoMate-Agentic-AI
   ```

2. **Install the Required Packages**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Your API Keys**
   Create a `.env` file or set environment variables:
   ```
   OPENWEATHER_API_KEY=your_openweathermap_key
   OPENAI_API_KEY=your_openai_key
   ```

4. **Run the App**
   ```bash
   python app.py
   ```

5. **Interact with EcoMate**
   - Get weather and AQI by entering your city
   - Estimate carbon emissions based on travel mode and distance
   - Ask for eco-smart travel suggestions
   - Mark your daily climate action as complete

---

### 🧪 Option 2: Run on Google Colab

1. Open the provided `.ipynb` file in Google Colab  
2. Install necessary packages in the first cell:
   ```python
   !pip install -r requirements.txt
   ```

3. Enter your API keys in a new cell:
   ```python
   import os
   os.environ["OPENAI_API_KEY"] = "your_openai_key"
   os.environ["OPENWEATHER_API_KEY"] = "your_openweather_key"
   ```

4. Run all cells to launch the Gradio UI inside Colab

---

## 📂 Folder Structure (Optional)

```
EcoMate-Agentic-AI/
│
├── app.py                  # Main Gradio app
├── requirements.txt        # Dependencies
├── utils.py                # Helper functions (weather, AQI, carbon)
├── .env                    # (Optional) API Keys
└── README.md               # This file




