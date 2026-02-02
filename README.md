# Weather App 🌦️

A modern, feature-rich weather application built with React Native and Expo that provides real-time weather information for any city worldwide.

## Features ✨

- **🔐 User Authentication**: Secure sign-in/sign-up functionality powered by Clerk
- **🌍 Location Selection**: Browse and select from countries and cities worldwide
- **☀️ Real-time Weather Data**: Get current weather conditions using Open-Meteo API
- **📊 Detailed Forecasts**: View temperature, humidity, wind speed, pressure, and more
- **📅 7-Day Forecast**: Plan ahead with daily weather predictions
- **🌓 Day/Night Indicators**: Visual cues based on local time
- **👤 User Profile**: Manage your account and view user information
- **🎨 Modern UI**: Beautiful interface styled with NativeWind (TailwindCSS for React Native)
- **📱 Cross-Platform**: Runs on iOS, Android, and Web

## Tech Stack 🛠️

- **Framework**: React Native with Expo
- **Language**: TypeScript
- **Routing**: Expo Router (file-based routing)
- **Styling**: NativeWind (TailwindCSS)
- **Authentication**: Clerk
- **Location Data**: country-state-city package
- **Weather API**: Open-Meteo
- **State Management**: React Hooks

## Project Structure 📁

```
Weather_App/
├── src/
│   ├── app/
│   │   ├── _layout.tsx              # Root layout with Clerk provider
│   │   ├── (app)/
│   │   │   ├── _layout.tsx          # App-level layout
│   │   │   ├── sign-in.tsx          # Sign-in screen
│   │   │   ├── sign-up.tsx          # Sign-up screen
│   │   │   ├── weather.tsx          # Detailed weather view
│   │   │   └── (tabs)/
│   │   │       ├── _layout.tsx      # Tab navigation layout
│   │   │       ├── index.tsx        # Home screen (location picker)
│   │   │       └── profile.tsx      # User profile screen
│   ├── components/
│   │   ├── CountryPicker.tsx        # Country selection component
│   │   ├── CityPicker.tsx           # City selection component
│   │   └── WeatherModal.tsx         # Weather display modal
│   └── global.css                   # Global styles
└── package.json
```

## Getting Started 🚀

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Expo CLI
- iOS Simulator / Android Emulator / Physical device

### Installation

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   cd Weather_App
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a Clerk account at [clerk.com](https://clerk.com)
   - Add your Clerk publishable key to your environment

4. Start the development server:

   ```bash
   npx expo start
   ```

5. Run on your preferred platform:
   - Press `a` for Android
   - Press `i` for iOS
   - Press `w` for Web
   - Scan the QR code with Expo Go app on your phone

### Clear Cache (if needed)

If you encounter bundling issues:

```bash
npx expo start --clear
```

## Available Scripts 📝

- `npm start` - Start the Expo development server
- `npm run android` - Open on Android emulator
- `npm run ios` - Open on iOS simulator
- `npm run web` - Open in web browser
- `npm run lint` - Run ESLint



## Features in Detail 🔍

### Authentication

- Email/password sign-in
- Secure token management
- Protected routes
- User session handling

### Weather Information

- Current temperature (actual & feels-like)
- Humidity and pressure readings
- Wind speed and direction
- Cloud cover percentage
- 7-day forecast with min/max temperatures
- Sunrise and sunset times
- Weather condition icons

### Location Selection

- Search functionality for countries and cities
- Flag emojis for visual identification
- Hierarchical selection (Country → City)
- Coordinates-based weather lookup

## API Information 🌐

This app uses the **Open-Meteo API** which is:

- Free and open-source
- No API key required
- Provides accurate weather data
- Includes current weather and forecasts




---

