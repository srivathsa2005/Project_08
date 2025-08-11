HealthCare Hospital Doctor Dashboard
A responsive web application dashboard for doctors at HealthCare Hospital, designed to help manage appointments and patient records efficiently.

Features
Doctor Login System: Only authenticated doctors can access the dashboard.

Statistics Cards: Displays:

Total Appointments

Today's Appointments

Upcoming Appointments

Appointments Overview:

List all scheduled appointments for the logged-in doctor.

Shows detailed info for each appointment: Patient Name, Problem, Date, and Time.

Logout Functionality: Secure logout button to end the session.

Responsive UI: Fully adapts to mobile and desktop screens.

Technologies Used
Frontend: HTML5, CSS3 (with Flexbox & CSS Grid), JavaScript (ES6)

Storage:

sessionStorage: Maintains doctor login state.

localStorage: Stores and loads appointment data for each doctor.

File Structure
text
/project-root
│-- index.html
│-- doctor-dashboard.html
│-- doctor-login.html
│-- style.css
│-- script.js
│-- README.md
Usage
Login: Open doctor-login.html and enter your credentials.

Dashboard Access: Upon successful login, you're redirected to the doctor dashboard.

Managing Appointments:

View all appointments and filter by date or upcoming.

Appointments are stored per doctor and retrieved from localStorage.

Logout: Click the “Logout” button, which securely clears the session and redirects to login.

Customization
To add or modify appointments, update the appointments_{doctor} entry in localStorage.

Customize the color schemes in the CSS as needed (see style blocks in the HTML).

Security
Session management: Only logged-in doctors can view their dashboard data.

Frontend validation: Ensures user sessions are maintained only for authenticated users.

License
This dashboard is meant for educational purposes and rapid prototyping inside healthcare/hospital management systems. Adapt as needed for production use.
