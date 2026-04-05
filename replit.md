# Performance Management System (PMS)

## Project Overview
A Web3-based Performance Management System for tracking and evaluating employee productivity, aligning individual efforts with company objectives, and managing talent using Web3-native tools (USDT earnings and wallet integrations).

## Tech Stack
- **Frontend:** React 17 (Create React App)
- **Styling:** SCSS/Sass, Material UI, Mantine, Bootstrap
- **State Management:** React Context API
- **Routing:** React Router DOM v6
- **Backend/Auth:** Firebase
- **Web3:** Ethers.js + MetaMask integration
- **Data Viz:** Recharts
- **HTTP:** Axios (proxied to `https://pms-jq9o.onrender.com/`)

## Project Structure
```
src/
  assets/         # Global styles and images
  components/     # Shared admin-focused components
  config/         # Firebase configuration
  context/        # React Contexts (DarkMode)
  data/           # Mock/static data
  empdashboard/   # Employee Dashboard (pages, components, context)
  pages/          # Admin/General pages (Login, Dashboard, etc.)
  style/          # Global SCSS themes (dark mode)
  App.js          # Main routing
  index.js        # Entry point
```

## Running the App
- **Workflow:** `Start application` — runs `npm start` on port 5000
- **Environment Variables:** `PORT=5000`, `HOST=0.0.0.0`, `DANGEROUSLY_DISABLE_HOST_CHECK=true`

## Key Features
- Multi-role access (Admin, HR/Employer, PM, Staff)
- Performance tracking (goals, appraisals, 360-degree reviews)
- Web3 wallet integration (MetaMask, USDT compensation)
- Dark mode support
- Responsive design

## Deployment
- Static React app deployed via Replit
- API requests proxied to `https://pms-jq9o.onrender.com/`
