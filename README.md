# 🔍 AI-Powered Data Analytics Chatbot

An intelligent, interactive chatbot that enables users to perform **data analytics**, **visualization**, and **machine learning** tasks using **natural language queries**—powered by Google’s **Gemini 1.5 Flash** and integrated with tools like Pandas, Seaborn, Scikit-learn, and Streamlit.

---

## 📌 Table of Contents

* [Project Description](#project-description)
* [Key Features](#key-features)
* [Tech Stack](#tech-stack)
* [Installation](#installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Future Enhancements](#future-enhancements)
* [References](#references)

---

## 📖 Project Description

This AI-powered chatbot aims to assist students, data enthusiasts, and analysts in exploring data, performing EDA, building ML models, and generating insights **instantly** from natural prompts. It simplifies data science workflows by integrating **Generative AI** and robust Python libraries for automated, conversational analysis.

---

## 🚀 Key Features

* 📂 **Upload & Preview Datasets**: Upload data and instantly preview rows and columns.
* 📊 **EDA Capabilities**: Perform statistical summaries, correlation checks, and detect outliers.
* 📈 **Interactive & Static Visualizations**: Supports violin plots, scatterplots, boxplots, and more via Plotly, Matplotlib, and Seaborn.
* 📉 **Statistical Analysis**: Includes descriptive stats, hypothesis testing, and distribution analysis.
* 🧠 **ML Model Assistance**: Build supervised/unsupervised models with evaluation metrics like accuracy and classification reports.
* 🗣️ **Gemini AI Integration**: Use natural queries to get human-like, intelligent responses powered by Google’s Gemini 1.5 Flash.
* 🧾 **Regex-based Query Parsing**: Understands structured queries using regex.
* 🖼️ **PIL & Base64 Plot Rendering**: Renders charts within Streamlit with format compatibility.

---

## 🛠️ Tech Stack

* **Languages**: Python
* **Libraries**: `numpy`, `pandas`, `seaborn`, `matplotlib`, `plotly`, `scikit-learn`, `scipy`, `regex`, `base64`, `io`, `PIL`
* **AI Model**: Google Gemini 1.5 Flash
* **Framework**: Streamlit
* **IDE**: Visual Studio Code / PyCharm

---

## ⚙️ Installation

### Prerequisites:

* Python 3.9+
* pip

### Steps:

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/ai-data-analytics-chatbot.git
cd ai-data-analytics-chatbot

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py
```

---

## 🧪 Usage

1. Upload your dataset (CSV format).
2. Ask a question like:

   * *"Show me a correlation matrix"*
   * *"Build a decision tree classifier"*
   * *"Give me a boxplot of age vs income"*
3. Let the bot process the request and provide analytics or visual outputs.

---

## 🗂️ Project Structure

```
Data Analytics Chatbot/
├── streamlit/
│   └── secrets.toml
├── assets/
├── static_plots/
├── venv/
├── app.py
├── chatbot_logic.py
├── gemini_handler.py
├── utils.py
└── requirements.txt
```

---

## 🚧 Future Enhancements

* 💾 Local memory persistence (e.g., JSON/SQLite)
* 🔐 User authentication & role-based access
* 🧠 Semantic query understanding (LangChain)
* 📊 Autosuggest visualizations from data patterns
* 📤 Export chats as PDF/Excel
* 🧠 Voice command prompts
* 🤖 Integration of advanced ML/DL models

---

## 📚 References

* [Python Docs](https://docs.python.org/3/)
* [Streamlit Docs](https://docs.streamlit.io/)
* [Pandas Docs](https://pandas.pydata.org/docs/)
* [Plotly Docs](https://plotly.com/python/)
* [Google AI Studio](https://makersuite.google.com/)
* [Gemini AI](https://gemini.google.com/)

---

## ✨ Contribute & Support

If you find this helpful, feel free to star ⭐ the repository and fork 🍴 it to enhance further. Pull requests are welcome!

