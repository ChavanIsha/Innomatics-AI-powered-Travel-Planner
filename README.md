# 🚀 AI-Powered Travel Planner

## 📌 Overview
An AI-driven travel assistant using **LangChain** + **Google GenAI** to provide travel recommendations, including cabs, trains, buses, and flights.  

## ✨ Features
✔️ AI-generated travel options  
✔️ Multi-language support  
✔️ Special assistance (elderly, disability)  
✔️ Fast response with LangChain  

## 🏗️ Tech Stack
- **Python**  
- **Streamlit**  
- **LangChain**  
- **Google GenAI**

## 📂 File Structure

📂 ai-travel-planner
├── 📄 app.py                # Main Streamlit app
├── 📄 requirements.txt      # Required dependencies
├── 📄 README.md             # Project documentation
└── 📂 .streamlit
    ├── 📄 secrets.toml      # Stores API keys (Google API Key)


## 🚀 Installation & Setup

### 🔹 1. Clone the Repository
```bash
git clone https://github.com/AbhishekKantharia/AIPoweredTravelPlanner.git
cd AIPoweredTravelPlanner
```

### 🔹 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 3. Set Up API Key
1. Create a **`.streamlit/secrets.toml`** file.  
2. Add your **Google API Key** inside it:
   ```
   GOOGLE_API_KEY = "your_google_api_key_here"
   ```

## 🚀 How to Run  
```bash
pip install -r requirements.txt
streamlit run app.py
```

## 🛠️ Future Enhancements
- ✅ Integrate **real-time flight, train, and bus APIs**  
- ✅ Add **price comparison & estimated travel duration**  
- ✅ Deploy on **Streamlit Cloud or Docker**  

## 🤝 Contributing
Feel free to submit **issues, feature requests, or pull requests**! 🚀

## 📄 License
This project is licensed under the **MIT License**.
