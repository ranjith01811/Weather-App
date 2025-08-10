# Weather App

A modern, responsive weather application built with React that provides real-time weather information for any city worldwide.

## Features

- 🌤️ Real-time weather data
- 🔍 Search any city worldwide
- 📱 Responsive design for all devices
- 🌡️ Temperature in Celsius
- 💧 Humidity information
- 💨 Wind speed details
- 🎨 Beautiful weather icons
- ⚡ Fast and lightweight

## Technologies Used

- React.js
- CSS3
- OpenWeatherMap API
- Vite (Build tool)

## Installation & Setup

1. Clone the repository
   ```bash
   git clone <your-repo-url>
   cd Weather-App
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory
   ```bash
   VITE_APP_ID=your_openweathermap_api_key
   ```

4. Start the development server
   ```bash
   npm run dev
   ```

## API Setup

This app uses the OpenWeatherMap API. To get your API key:

1. Visit [OpenWeatherMap](https://openweathermap.org/)
2. Sign up for a free account
3. Get your API key from your dashboard
4. Add it to your `.env` file as `VITE_APP_ID`

## Usage

1. Enter a city name in the search bar
2. Click the search button or press Enter
3. View current weather information including:
   - Temperature
   - Humidity
   - Wind speed
   - Weather condition with appropriate icon

## Screenshots

[Add screenshots of your app here]

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

---

# React + Vite Setup Information

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
