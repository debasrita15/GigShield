# GigShield

### Safety Intelligence Platform for Gig Workers

GigShield is a full-stack MERN application designed to enhance **safety, transparency, and support** for gig workers. The platform enables real-time incident reporting, geospatial risk visualization, earnings tracking, and intelligent insights to help workers make safer and more informed decisions.


##  Overview

With the rapid growth of the gig economy, workers often operate in unpredictable and high-risk environments. GigShield addresses this gap by providing a **data-driven safety ecosystem** where users can report incidents, visualize risks, and access critical support tools.


##  Key Features

### Safety Heatmap Visualization

* Interactive map built using **Leaflet.js**
* Displays incident data using **category-based markers**
* Automatic viewport adjustment based on reported incidents
* Reverse geocoding for readable location insights

### Incident Reporting System

* Supports categorized reports:

  * Theft
  * Harassment
  * Accident
  * Road Hazard
  * Other
* Anonymous reporting capability
* Timestamped entries with descriptive context


### Location Intelligence

* Reverse geocoding via:

  * OpenStreetMap (Nominatim)
  * BigDataCloud API
* Optimized with caching to reduce API calls and rate limits
* Fallback handling for unavailable location data

### Environmental Context Integration

* Integrated with **OpenWeather API**
* Provides contextual insights (e.g., weather-related risks)
* Enhances situational awareness for workers

### Dynamic Filtering & Analytics

* Filter incidents by category
* Real-time count aggregation
* Interactive legend for quick insights

### User Interface & Experience

* Clean, responsive UI with structured report cards
* Visual category badges and icons
* Smooth animations and intuitive layout


##  System Workflow

1. User submits an incident report
2. Backend stores data with GeoJSON coordinates
3. Frontend fetches data via API endpoints
4. Map renders incidents dynamically
5. Reverse geocoding converts coordinates into readable locations
6. Users interact with both map and detailed report feed


##  Tech Stack

### Frontend

* React.js (Hooks & Functional Components)
* Leaflet.js (Geospatial Visualization)
* CSS / Custom Styling

### Backend

* Node.js
* Express.js

### Database

* MongoDB (with GeoJSON support)

### External APIs

* OpenStreetMap (Map tiles & geocoding)
* BigDataCloud (Reverse geocoding)
* OpenWeather API (Weather data)


##  Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/gigshield.git

# Navigate to project directory
cd gigshield

# Install dependencies
npm install

# Start backend server
cd backend
npm run dev

# Start frontend
cd frontend
npm start
```

---

##  Project Structure

```
gigshield/
│── frontend/
│   ├── components/
│   ├── api/
│   └── styles/
│
│── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── services/
```


##  Future Enhancements

* AI-based predictive risk alerts
* Personalized safety recommendations
* Mobile application support
* Voice-enabled incident reporting
* Real-time tracking and alert system


##  Contribution Guidelines

Contributions are welcome. Please follow standard Git workflow:

```bash
git checkout -b feature/your-feature-name
git commit -m "Add your feature"
git push origin feature/your-feature-name
```


##  License

This project is licensed under the MIT License.


##  Vision

GigShield aims to become a **comprehensive safety infrastructure for the gig economy**, enabling workers to operate with greater confidence through **real-time insights, community reporting, and intelligent systems**.


##  Authors

Developed by a collaborative team as part of a MERN stack project.


##  Acknowledgements

* OpenStreetMap
* BigDataCloud
* OpenWeather


 a **LinkedIn / portfolio version of this** 🚀
