# Chicago Weather Dashboard

A modern weather dashboard showing real-time Chicago weather conditions.

## Features
- Real-time weather data
- 3-day forecast
- Air quality index
- Precipitation probability
- Sunrise/sunset times
- Wind conditions

## Development
1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

## Production
For production deployment, the dashboard uses real API calls to:
- Open-Meteo for weather data
- Air quality data
- Precipitation forecasts

## Updates
- Weather data refreshes every 15 minutes
- All times in Chicago local time (CST/CDT)
- Temperatures include actual and 'feels like' values