<h1 align="center">🛡️ GigShield: Safety Intelligence Platform for Gig Workers</h1>

<p align="center">
  <img src="https://img.shields.io/badge/React-Frontend-61DAFB?logo=react"/>
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?logo=nodedotjs"/>
  <img src="https://img.shields.io/badge/Express.js-Framework-000000?logo=express"/>
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?logo=mongodb"/>
  <img src="https://img.shields.io/badge/Leaflet.js-Maps-199900?logo=leaflet"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg"/>
</p>

<p align="center">
  🔥 A real-time safety intelligence platform empowering gig workers with incident reporting, geospatial risk visualization, and community-driven insights
</p>

<hr/>

<h2>✨ Overview</h2>

<p>
<b>GigShield</b> is a full-stack MERN application designed to enhance <b>safety, transparency, and support</b> for gig workers. The platform enables real-time incident reporting, geospatial risk visualization, and intelligent insights to help workers make safer and more informed decisions.
</p>

<p>
With the rapid growth of the gig economy, workers often operate in unpredictable and high-risk environments. GigShield addresses this gap by providing a <b>data-driven safety ecosystem</b> where users can report incidents, visualize risks, and access critical support tools.
</p>

<hr/>

<h2>💡 Why GigShield?</h2>

<p>
This project demonstrates how modern full-stack web development, geospatial visualization, and external API integrations can be combined to build a scalable, real-world safety platform — reflecting practical knowledge of production-level MERN stack development and clean architecture design.
</p>

<hr/>

<h2>🎯 Problem Statement</h2>

<p>
Gig workers lack access to real-time safety data, community-driven incident reports, and intelligent risk insights while operating in unpredictable environments.
</p>

<p><b>GigShield solves this by:</b></p>

<ul>
  <li>Providing a platform to report and visualize safety incidents in real time</li>
  <li>Displaying geospatial risk data on an interactive map with category-based markers</li>
  <li>Integrating weather and location intelligence for enhanced situational awareness</li>
  <li>Enabling anonymous incident reporting to encourage community participation</li>
</ul>

<hr/>

<h2>✨ Key Features</h2>

<ul>
  <li>🗺️ <b>Safety Heatmap Visualization</b> — Interactive map built with Leaflet.js, category-based markers, automatic viewport adjustment</li>
  <li>📋 <b>Incident Reporting System</b> — Categorized reports (Theft, Harassment, Accident, Road Hazard), anonymous reporting, timestamped entries</li>
  <li>📍 <b>Location Intelligence</b> — Reverse geocoding via OpenStreetMap and BigDataCloud, optimized with caching, fallback handling</li>
  <li>🌤️ <b>Environmental Context</b> — OpenWeather API integration for weather-related risk insights and situational awareness</li>
  <li>📊 <b>Dynamic Filtering & Analytics</b> — Filter incidents by category, real-time count aggregation, interactive legend</li>
  <li>🔐 <b>Admin System</b> — Admin login, registration, and dashboard for managing incidents and SOS alerts</li>
  <li>🆘 <b>SOS Alert Tracking</b> — Real-time SOS alert system for workers in distress</li>
  <li>📱 <b>Responsive UI</b> — Clean, structured report cards with visual category badges and smooth animations</li>
</ul>

<hr/>

<h2>📊 Impact</h2>

<ul>
  <li>🗺️ Built <b>geospatial incident visualization</b> using Leaflet.js with GeoJSON data from MongoDB</li>
  <li>📍 Implemented <b>reverse geocoding with caching</b> to reduce API calls and handle rate limits efficiently</li>
  <li>🌤️ Integrated <b>OpenWeather API</b> to provide contextual weather-based risk insights for workers</li>
  <li>🆘 Developed <b>real-time SOS alert tracking</b> system for immediate worker safety response</li>
  <li>🔐 Built <b>admin authentication system</b> with dashboard for centralized incident and alert management</li>
  <li>📊 Enabled <b>dynamic filtering and analytics</b> for real-time incident category aggregation and visualization</li>
</ul>

<hr/>

<h2>🔥 Key Takeaway</h2>

<p>
GigShield demonstrates how modern full-stack development, geospatial APIs, and community-driven data can be combined to build a scalable safety platform that addresses real-world challenges faced by gig economy workers.
</p>

<hr/>

<h2>🏗️ Architecture</h2>

<p><b>MERN Stack</b> with clean separation of concerns:</p>

<ul>
  <li><b>Frontend</b> → React.js (Hooks & Functional Components) + Leaflet.js for geospatial visualization</li>
  <li><b>Backend</b> → Node.js + Express.js REST API</li>
  <li><b>Database</b> → MongoDB with GeoJSON support for spatial data</li>
  <li><b>External APIs</b> → OpenStreetMap, BigDataCloud, OpenWeather API</li>
</ul>

<hr/>

<h2>🔄 Application Flow</h2>

<ol>
  <li>User submits a categorized incident report with location</li>
  <li>Backend stores data with GeoJSON coordinates in MongoDB</li>
  <li>Frontend fetches incident data via REST API endpoints</li>
  <li>Leaflet.js map renders incidents dynamically with category markers</li>
  <li>Reverse geocoding converts coordinates into readable location names</li>
  <li>OpenWeather API enriches reports with contextual weather data</li>
  <li>Admin dashboard tracks SOS alerts and manages reported incidents</li>
</ol>

<hr/>

<h2>🛠 Tech Stack</h2>

<ul>
  <li>React.js (Hooks & Functional Components)</li>
  <li>Node.js + Express.js</li>
  <li>MongoDB (GeoJSON support)</li>
  <li>Leaflet.js (Geospatial Visualization)</li>
  <li>OpenStreetMap + BigDataCloud (Reverse Geocoding)</li>
  <li>OpenWeather API (Weather Context)</li>
  <li>REST API Architecture</li>
</ul>

<hr/>

<h2>📦 Setup Instructions</h2>

<p><b>Prerequisites:</b></p>
<ul>
  <li>Node.js 18+</li>
  <li>MongoDB Atlas account — <a href="https://cloud.mongodb.com">cloud.mongodb.com</a></li>
  <li>OpenWeather API key — <a href="https://openweathermap.org/api">openweathermap.org</a></li>
</ul>

<p><b>Installation:</b></p>

<pre>
git clone https://github.com/debasrita15/GigShield.git
cd GigShield
</pre>

<p><b>Backend:</b></p>
<pre>
cd backend
npm install
npm run dev
</pre>

<p><b>Frontend:</b></p>
<pre>
cd frontend
npm install
npm start
</pre>

<p>Add environment variables in <code>backend/.env</code>:</p>
<pre>
MONGODB_URI=your_mongodb_connection_string
PORT=5000
OPENWEATHER_API_KEY=your_openweather_api_key
</pre>

<hr/>

<h2>🗄️ Database Structure</h2>

<pre>
incidents/
  {incidentId}/
    category, description, location (GeoJSON),
    anonymous, timestamp, weatherContext

users/
  {userId}/
    name, email, password, role

sosAlerts/
  {alertId}/
    workerId, location, status, createdAt
</pre>

<hr/>

<h2>📁 Project Structure</h2>

<pre>
gigshield/
├── frontend/
│   ├── components/
│   ├── api/
│   └── styles/
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── services/
</pre>

<hr/>

<h2>📚 Learnings</h2>

<ul>
  <li>Built a scalable <b>MERN stack application</b> with clean layer separation</li>
  <li>Integrated <b>Leaflet.js with GeoJSON data</b> for geospatial incident visualization</li>
  <li>Implemented <b>reverse geocoding with caching</b> to optimize API usage and rate limits</li>
  <li>Worked with <b>multiple external APIs</b> (OpenStreetMap, BigDataCloud, OpenWeather)</li>
  <li>Built <b>REST API endpoints</b> with Express.js for full CRUD operations</li>
  <li>Managed <b>collaborative development</b> with Git branching and pull requests</li>
</ul>

<hr/>

<h2>🚀 Future Enhancements</h2>

<ul>
  <li>🤖 AI-based predictive risk alerts</li>
  <li>📱 Mobile application support</li>
  <li>🎙️ Voice-enabled incident reporting</li>
  <li>🔔 Real-time push notifications</li>
  <li>📊 Personalized safety recommendations</li>
  <li>🗺️ Real-time worker tracking and alert system</li>
</ul>

<hr/>

<h2>👩‍💻 Authors</h2>

<p>
<b>Debasrita Das</b> — <a href="https://github.com/debasrita15">GitHub</a><br/>
<b>Esha Agarwal</b> — <a href="https://github.com/eshaagarwal1805-hash">GitHub</a><br/>
<b>Sreshtha Mukherjee</b> — <a href="https://github.com/Sres-htha">GitHub</a>
</p>

<hr/>

<h2>📜 License</h2>

<p>This project is licensed under the MIT License — see the <a href="LICENSE">LICENSE</a> file for details.</p>

<hr/>

<h2>⭐ Support</h2>

<p>If you find this project useful, give it a ⭐ on GitHub!</p>
