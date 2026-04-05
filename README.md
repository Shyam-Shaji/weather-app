# ClimateCast - Modern Weather Dashboard

ClimateCast is a sleek, responsive, and feature-rich weather dashboard built with React 19, TypeScript, and Tailwind CSS 4. It provides real-time weather data, forecasts, and city management with a premium user experience.

![Weather Dashboard Preview](https://images.unsplash.com/photo-1592210633464-a7db0536f947?q=80&w=1470&auto=format&fit=crop)

## ✨ Features

- 📍 **Real-time Local Weather**: Automatically detects and displays weather for your current location.
- 🔍 **City Search**: Search for any city worldwide with intelligent autocomplete suggestions.
- 📊 **Interactive Charts**: Visualize hourly temperature fluctuations using Recharts.
- 📅 **7-Day Forecast**: Get detailed daily forecasts including temperature highs/lows and conditions.
- 🌡️ **Detailed Metrics**: View humidity, wind speed, air pressure, UV index, and more.
- ⭐ **Favorites Management**: Save your most-visited cities for quick access.
- 🌓 **Dark Mode Support**: Seamlessly switch between light and dark themes.
- ⚡ **Performance Optimized**: Built with Vite and TanStack Query for blazing fast performance and efficient data caching.

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **Components**: [Radix UI](https://www.radix-ui.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Data Fetching**: [TanStack React Query v5](https://tanstack.com/query/latest)
- **Charts**: [Recharts](https://recharts.org/)
- **State Management**: React Hooks & Context API
- **Theming**: [next-themes](https://github.com/pacocoursey/next-themes)
- **Routing**: [React Router 7](https://reactrouter.com/)
- **API**: [OpenWeatherMap API](https://openweathermap.org/api)

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or later)
- npm or yarn
- An API key from [OpenWeatherMap](https://home.openweathermap.org/api_keys)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Shyam-Shaji/weather-app.git
   cd weather-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add your OpenWeather API key:
   ```env
   VITE_OPENWEATHER_API_KEY=your_api_key_here
   ```

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. **Open the app:**
   Navigate to `http://localhost:5173` in your browser.

## 📖 Project Structure

```bash
src/
├── api/          # API services and configurations
├── components/   # Reusable UI components
├── context/      # React Context providers (Themes, etc.)
├── hooks/        # Custom React hooks (Data fetching, Favorites)
├── lib/          # Helper functions and utilities
├── pages/        # Main application pages (Dashboard, City view)
└── main.tsx      # Application entry point
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Developed with ❤️ by [Shyam Shaji](https://github.com/Shyam-Shaji)
