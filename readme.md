[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://genaisqlchatapp-x5b7appuqscpmxy6epm8r5k.streamlit.app/)

# GenAI SQL Chat App

An AI-powered chatbot that allows users to interact with a database using natural language. This app uses the **Groq API** to convert natural language queries into SQL, which are then executed against a sample SQLite database (`student.db`) by default. Users also have the flexibility to connect the chatbot to their **own MySQL database** by entering their connection details directly in the **Streamlit app UI**.

---

## 🔍 Features

- 🧠 Natural Language to SQL query generation using Groq's LLM API
- 🗃️ SQLite database integration out of the box
- 🌐 Optional support for custom MySQL databases
- 💬 Interactive Streamlit UI for chat and configuration
- ⚙️ Modular and extensible Python codebase

---

## 🔌 Connect to Your Own MySQL Database

To use your own MySQL database instead of the default SQLite setup, simply fill in the following details on the **Streamlit app interface**:

- **MySQL Host** – e.g., `localhost` or `your-db-host.com`
- **MySQL User** – e.g., `root`
- **MySQL Password** – your database password
- **MySQL Database Name** – the name of the database you want to connect to
- **Groq API Key** – your valid Groq key for query generation

> Once entered, the chatbot will query your own MySQL database based on natural language inputs.

---

## 🛠️ Tech Stack

- Python 3
- Groq API
- SQLite3 / MySQL
- Streamlit

---

## 🚀 Getting Started (Local Use)

### Prerequisites

- Python 3.7+
- Groq API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/asimucd/GenAI_SQL_Chat_App.git
   cd GenAI_SQL_Chat_App

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt

3. **Set up your .env file Create a .env file in the root directory:**
    ```bash
    GROQ_API_KEY=your_groq_api_key_here

4. **Run the application locally**
    ```bash
    streamlit run app.py

