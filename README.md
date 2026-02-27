<div align="center">

# 🌦️ WeatherPulse

**Real-time weather at your fingertips — beautifully crafted, lightning fast.**

[![Live Demo](https://img.shields.io/badge/▶_Live_Demo-Vercel-000?style=for-the-badge&logo=vercel)](https://weather-pulse.vercel.app)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-7-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vite.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

</div>

---

## ✨ Features

| Feature | Description |
| --- | --- |
| 🔍 **Smart City Search** | Autocomplete suggestions powered by OpenWeatherMap Geocoding API |
| 🌡️ **Unit Toggle** | Seamlessly switch between Celsius and Fahrenheit |
| 🎬 **Dynamic Backgrounds** | Animated weather-based backgrounds (clear, rain, snow, fog, thunderstorm & more) |
| 🌅 **Sunrise & Sunset** | Localized sunrise and sunset times for any city |
| 💧 **Detailed Metrics** | Humidity, wind speed & direction, visibility, pressure, and feels-like temperature |
| 🎨 **Glassmorphism UI** | Frosted-glass card design with smooth animations and micro-interactions |
| 📱 **Fully Responsive** | Optimized for mobile, tablet, and desktop viewports |

---

## 🖼️ Preview

<div align="center">

> _Search any city worldwide and get instant, visually immersive weather data._

</div>

---

## 🚀 Quick Start

### Prerequisites

- [Node.js](https://nodejs.org/) ≥ 18
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

```bash
# Clone the repository
git clone https://github.com/Atanu562/weather-app.git
cd weather-app

# Install dependencies
npm install

# Start the development server
npm run dev
```

The app will be available at `http://localhost:5173`.

---

## 🛠️ Tech Stack

| Layer | Technology |
| --- | --- |
| **Framework** | React 19 |
| **Build Tool** | Vite 7 |
| **Styling** | Tailwind CSS 4 |
| **API** | [OpenWeatherMap](https://openweathermap.org/api) |
| **Deployment** | Vercel |

---

## 📁 Project Structure

```
weather-app/
├── public/
├── src/
│   ├── assets/              # Weather GIFs, icons & media
│   ├── components/
│   │   ├── Helper.jsx       # Utility functions (temp conversion, wind direction, etc.)
│   │   ├── Icons.jsx        # Reusable weather icon components
│   │   └── WeatherBackground.jsx  # Dynamic animated backgrounds
│   ├── App.jsx              # Main application component
│   ├── main.jsx             # App entry point
│   └── index.css            # Global styles
├── index.html
├── vite.config.js
├── package.json
└── README.md
```

---

## ⚙️ Configuration

WeatherPulse uses the [OpenWeatherMap API](https://openweathermap.org/api). The API key is currently embedded in the source code. For production use, consider moving it to an environment variable:

```bash
# Create a .env file in the project root
VITE_API_KEY=your_openweathermap_api_key
```

Then reference it in your code as `import.meta.env.VITE_API_KEY`.

---

## 📦 Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start development server with HMR |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint checks |

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

---

<div align="center">
  <p>Built with ❤️ by <a href="https://github.com/Atanu562">Atanu Maity</a></p>
</div>
