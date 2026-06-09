# 📊 WhatsApp Chat Analysis

An interactive data analytics web application that analyzes exported WhatsApp chat files and generates meaningful insights using Python, Pandas, and Streamlit.

---

## 🚀 Project Overview

12 hour WhatsApp Chat Analysis is a data visualization and analytics project that allows users to upload exported WhatsApp chat files and explore communication patterns through interactive charts and statistics.

The application preprocesses raw chat data, extracts useful information, and presents insights such as message statistics, user activity, timelines, word clouds, emoji usage, and chat trends through a user-friendly Streamlit dashboard.

---

## ✨ Features

### 📈 Chat Statistics

* Total messages sent
* Total words used
* Media shared count
* Links shared count

### 👥 User Analysis

* Most active users in group chats
* User contribution percentages
* User-wise message statistics

### 📅 Timeline Analysis

* Monthly message trends
* Daily activity trends
* Year-wise chat activity

### 🗓 Activity Analysis

* Most active days of the week
* Most active months
* Activity heatmaps
* Hourly message distribution


### 🔤 Common Words Analysis

* Most frequently used words
* Word frequency visualization

### 😀 Emoji Analysis

* Most used emojis
* Emoji frequency distribution
* Emoji usage statistics

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn
* WordCloud

### Web Application Framework

* Streamlit


### Additional Libraries
* Emoji
* URLExtract
* Regular Expressions (re)

---

## 📂 Project Structure

```text
Whatsapp_Chat_Analysis/
│
├── app.py                 # Main Streamlit application
├── helper.py              # Analysis and visualization functions
├── preprocessor.py        # Chat preprocessing logic
├── stop_hinglish.txt      # Stop words list
├── requirements.txt       # Project dependencies
├── README.md              # Project documentation
├── .gitignore             # Git ignored files
│__
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/AnuskaDey07/Whatsapp_Chat_Analysis.git
```

### Navigate to Project Directory

```bash
cd Whatsapp_Chat_Analysis
```

### Create Virtual Environment (Optional)

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux / macOS:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

## 📱 How to Use

1. Export a WhatsApp chat as a `.txt` file.
2. Choose **Export Chat → Without Media**.
3. Upload the exported chat file in the application.
4. Select a specific user or analyze the entire chat.
5. Explore generated statistics, charts, word clouds, and emoji insights.

---

## 📊 Sample Insights Generated

* Total Messages
* Total Words
* Shared Media Count
* Shared Links
* Most Active Users
* Monthly Timeline
* Daily Timeline
* Activity Heatmaps
* Word Clouds
* Most Common Words
* Emoji Usage Statistics

---

## 🔮 Future Enhancements

* Sentiment Analysis using NLP
* AI-powered conversation insights
* Multi-chat comparison
* PDF report generation
* Advanced keyword trend analysis
* Interactive dashboard improvements

---

## 🎯 Learning Outcomes

This project demonstrates:

* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Text Analytics
* Data Visualization
* Streamlit Application Development
* Python Project Deployment

---

## 🤝 Acknowledgements

This project is based on the WhatsApp Chat Analysis concept popularized by CampusX and has been customized for learning and portfolio purposes.

---


