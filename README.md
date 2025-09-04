# Frontend Test Submission - URL Shortener

This folder contains the React frontend for the URL Shortener project used for evaluation.

## Quick start

1. Install dependencies:
```bash
cd "Frontend Test Submission"
npm install
```

2. Start the dev server:
```bash
npm start
```

3. App runs on http://localhost:3000
- Pages: `/` (Shortener), `/stats` (Statistics), `/logs` (Logs), `/:code` (Redirector)

## Logging behavior
- All logs are sent to `http://20.244.56.144/evaluation-service/logs` via `src/utils/logger.js`
- Logs are also stored locally (localStorage key `appLogs`) and displayed on `/logs` for demo.

## Notes
- This is a client-side demo (no real backend). shorten action simulates a response.
- Preloaded sample logs are injected into `public/index.html` for demo purposes.
# React URL Shortener

## Screenshots

## 📸 Screenshots

### 🏠 Homepage
![Homepage](./Screenshots/image1.png)

### 🔗 Shortened URL Created
![URL Created](./Screenshots/image2.png)

### 📊 Statistics Page
![Statistics](./Screenshots/image3.png)

### 👆 Click Details
![Click Details](./Screenshots/image4.png)

### 📝 Logs
![Logs](./Screenshots/image5.png)
