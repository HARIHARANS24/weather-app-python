# 🌦 Weather App — Python GUI + Web + Auto Location

A versatile Python Weather App that works in multiple modes:

- 🖥 Desktop GUI app built with **Tkinter**
- 🌐 Web app using **Flask**
- 📍 Auto-detects user location via IP address

It fetches live weather data from **OpenWeatherMap API** and displays it in a clean, user-friendly format.

---

## ⚡ Features

- 🔍 Search weather by **city name**
- 🌍 Auto-detect user location (via IP)
- 🖼 Tkinter GUI app
- 🌐 Flask Web App
- 🔧 Clean modular structure

---

## 🗂 Project Structure

```
📁 weather-app/
├── 📄 main.py                 # CLI mode entry point
├── 📄 gui_app.py             # Tkinter GUI application
├── 📄 web_app.py             # Flask web application
├── 📄 requirements.txt       # Project dependencies
├── 📄 README.md             # Project documentation
│
├── 📁 weather/              # Weather-related modules
│   ├── 📄 __init__.py
│   ├── 📄 fetcher.py       # API request handling
│   ├── 📄 config.py        # Configuration and API keys
│   └── 📄 location.py      # IP-based location detection
│
└── 📁 utils/               # Utility modules
    └── 📄 formatter.py     # Weather data formatting
```

---

## 🚀 Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/HARIHARANS24/weather-app-python.git
cd weather-app-python
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Configure API Key
- Get your API key from [OpenWeatherMap](https://openweathermap.org/api)
- Add your API key to `weather/config.py`

### 4. Run the application
Choose one of the following modes:

#### GUI Mode
```bash
python gui_app.py
```

#### Web Mode
```bash
python web_app.py
```

#### CLI Mode
```bash
python main.py
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👥 Authors

- **HARIHARANS24** - *Initial work* - [GitHub Profile](https://github.com/HARIHARANS24)

---

## 🙏 Acknowledgments

- OpenWeatherMap API for weather data
- Flask for web framework
- Tkinter for GUI development

