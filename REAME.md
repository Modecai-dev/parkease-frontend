# ParkEase Frontend

## Project Description
ParkEase is a parking management system designed to help parking attendants and administrators manage vehicle entry, parking duration, and exit operations efficiently.

The frontend of this system was built using HTML, Bootstrap 5, and CSS. It provides interfaces for attendants to register arriving vehicles, process vehicle sign-outs, and for administrators to monitor parking activity and revenue through reports.

The system simulates a real parking facility workflow where vehicles are registered on arrival, tracked while parked, and charged a calculated fee upon exit.


## Pages
index.html -> Login page that allows attendants or admins to access the system.
**dashboard.html -> Attendant dashboard showing parking statistics, available slots, and recent arrivals.
register.html -> Vehicle registration page where attendants record driver and vehicle details when a vehicle enters the parking lot.
signout.html -> Vehicle sign-out page used to calculate parking duration and final parking fee before a vehicle exits.
reports.html ->Admin reports page showing parking revenue metrics and a table of signed-out vehicles.


## How to Run
1. Clone the repository

git clone https://github.com/Modecai-dev/parkease-frontend/tree/main

2. Open the project folder.

3. Open `index.html` in any web browser (no server required).

4. Login using the prototype credentials:

Admin
username: admin
password: admin123

Attendant
username: attendant
password: park2026


## Features Implemented
Login page with prototype credentials
Attendant Dashboard with parking statistics
Vehicle Registration form for new arrivals
Receipt preview with QR code generation
Vehicle Sign-out page with fee display
Admin Daily Reports page
Revenue overview cards
Table of signed-out vehicles
Search bar for filtering report data
Pagination layout for report tables
Responsive UI built with Bootstrap 5
Use of Bootstrap Icons for UI elements


## Validation Rules Applied
The system uses HTML form validation and structured inputs to ensure correct data entry.

Examples include:
Driver name field requires text input.
Phone number fields use `type="tel"` formatting.
Required fields must be filled before submitting forms.
Vehicle type and category must be selected from dropdown menus.
NIN number must follow a structured alphanumeric format.
Form reset button clears all inputs instantly.


## Known Issues / Assumptions
The project is a frontend prototype only and does not connect to a backend database.
Login authentication is simulated and does not validate credentials dynamically.
Parking fee calculations are displayed as static values for demonstration.
Report search and pagination are UI placeholders and are not yet connected to real data filtering logic.
Some links such as settings, history, and export buttons are placeholders for future implementation.
Did not add authentication cause am a python student and i dont kn javascript


## Technologies Used
HTML5
CSS3
Bootstrap 5
Bootstrap Icons


## Author
Conrad Opio Modecai — Refactory CSE 2026
