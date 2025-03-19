# Career-Mentor-Agent
# 💼 Virtual Career Mentor Agent

A **Streamlit-based web app** that helps users **search for jobs** and **get career advice** using Wikipedia.

---

## 🚀 Features

- 🔍 **Job Search**: Fetches job listings using the JSearch API.
- 🤖 **AI Career Advice**: Provides career guidance using Wikipedia data.
- 📊 **User-Friendly Interface**: Built with Streamlit for easy navigation.

---

## 📦 Project Structure

```
career-mentor-agent/
│── app.py        # Streamlit UI
│── backend.py    # Backend logic (API requests & Wikipedia search)
│── README.md     # Project documentation
```

---

## 🛠️ Installation & Setup

### **1️⃣ Clone the Repository**

```sh
git clone https://github.com/lasya-14/Career-Mentor-Agent.git
cd career-mentor-agent
```

### **2️⃣ Set Up a Virtual Environment (Optional but Recommended)**

```sh
conda create --name career-mentor python=3.10 -y
conda activate career-mentor
```

### **3️⃣ Install Dependencies**

```sh
pip install -r requirements.txt
```

*If ******`requirements.txt`****** is missing, manually install:*

```sh
pip install streamlit requests wikipedia-api
```

### **4️⃣ Set Your API Key**

- Open **backend.py**
- Replace `"your-jsearch-api-key"` with your actual API key.

### **5️⃣ Run the App**

```sh
streamlit run app.py
```

---

## 🎯 Usage

1. **Search for Jobs**: Enter a job title and location to fetch listings.
2. **Get Career Advice**: Ask career-related questions for AI-powered guidance.

---

## 📜 License

This project is **open-source** and free to use.

---

## 👨‍💻 Created by

CHAVVAKULA LASYAVALLI

---

## 🔗 Hosted App Link

[Career Mentor Agent](https://career-mentor-agent-hbgugvwap3amp2vvmjnsfp.streamlit.app/)

---

## 🚀 Next Steps

Want to contribute? Follow these steps:

```sh
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/sambasivagudala369/career-mentor-agent.git
git push -u origin main
```

Feel free to **fork, modify, and improve** the project! 🎉

