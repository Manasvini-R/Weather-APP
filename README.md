## 🌦️ Flask Weather App

A simple web application that displays real-time weather information for any city using the [OpenWeatherMap API](https://openweathermap.org/api). Built with **Flask**, **HTML**, **CSS**, and **JavaScript**.

---

### 🚀 Features

* 🌍 Get current weather for any city
* ☁️ Fetches data using OpenWeatherMap API
* ⚡ Fast and responsive interface
* 🔐 Secure API key handling with `.env` file

---

### 🌐 Live Website

🔗 [Click here to view the live app](https://weather-app-2-5091.onrender.com)


---

### 🛠️ Tech Stack

* **Frontend**: HTML, CSS, JavaScript
* **Backend**: Python (Flask)
* **API**: OpenWeatherMap
* **Deployment**: Render

---

### 🔧 Setup Instructions

#### 1. Clone the Repo

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

#### 2. Create and Activate Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

#### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

#### 4. Get API Key from OpenWeatherMap

* Sign up at [https://openweathermap.org/api](https://openweathermap.org/api)
* Copy your API key

#### 5. Create `.env` File

```
API_KEY=your_openweathermap_api_key
```

> ⚠️ **Do not commit `.env` to GitHub**. It's already ignored in `.gitignore`.

#### 6. Run the App

```bash
python app.py
```

Then open `http://localhost:10000` in your browser.

---

### 📁 Project Structure

```
weather-app/
├── app.py
├── requirements.txt
├── .env             # (keep this secret)
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── README.md
```

---

### 🙌 Acknowledgements

* [OpenWeatherMap API](https://openweathermap.org/api)
* [Flask](https://flask.palletsprojects.com/)
* [Render](https://render.com)

---

