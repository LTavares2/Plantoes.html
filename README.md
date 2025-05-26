# Plantoes.html
# Find Medical Shifts

A web platform designed to help hospitals register and doctors find available medical shifts.

## 📄 Current Pages

- `index.html`: Landing page with platform introduction and buttons for login and registration.
- `login.html`: Login page for doctors or hospitals.
- `cadastro.html`: Registration page for doctors.
- `cadastro-hospital.html`: Hospital registration page with dynamic state/city form (using IBGE API).
- `encontrarplantoes.html`: Interface for doctors to search for available shifts by state, city, and specialty.

## 🛠️ Technologies Used

- HTML5  
- CSS3 (inline styles within each page)  
- Vanilla JavaScript  
- IBGE API (for Brazilian states and cities dropdowns)

## 💡 Features

- Registration forms for doctors and hospitals (data stored locally using `localStorage`)  
- Responsive and user-friendly design  
- Basic form validation  
- Medical shift search functionality  
- Dynamic location selector via public API

## 📌 Next Steps

- Improve UI/UX (more modern and responsive design)  
- Set up a backend (Node.js + Express) for real data persistence  
- Integrate with a database (MongoDB or PostgreSQL)  
- Secure user authentication  
- Admin panel for hospitals to manage their available shifts  
- Dynamic filtering and rendering of search results in `encontrarplantoes.html`

## 👨‍💻 Developed by

Lucas Tavares Hauber  
2025 — Academic and personal project