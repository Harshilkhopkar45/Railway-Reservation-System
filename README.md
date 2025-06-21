# Railway Reservation System  
==========================

This is a command-line-based Railway Reservation System built using Python and SQL connectivity. It allows users to register, book tickets, view or cancel reservations, and manage their account details. Designed as a core logic and backend-focused application, this project reflects an understanding of structured programming, database interaction, and real-world workflow simulation.

**Technologies Used**

• Python   
  - Controls program logic and user input/output  
  - Uses functions to organize the system into clear modules  
  - Handles validation, conditions, and flow control

• SQL Database (MySQL)  
  - Stores user credentials and ticket information  
  - Supports CRUD operations: create, read, update, delete  
  - Communicated via Python's SQL connector (e.g., `mysql.connector` or `sqlite3`)

• Terminal / Command Line Interface  
  - Text-based interface for all inputs and outputs  
  - No GUI elements used (deliberate for backend logic clarity)

---

**Main Functionalities**

• User Sign-Up  
• Secure Sign-In  
• Ticket Booking  
• Ticket Checking  
• Ticket Cancellation  
• View Account Details  
• Delete Account  
• Logout and Exit

Each function is modular and follows a menu-driven structure for clean user interaction.

---

**Database Details**

Two main tables are involved:

• `users` — stores name, gender, date of birth, contact number, username, and password  
• `bookings` — stores ticket details (such as passenger, journey info, booking ID, etc.)

The data flow between Python and SQL ensures persistence and reflects real-time user actions.

---

**Project Purpose**

• Demonstrates database-backed application logic in Python  
• Simulates core functions of a real railway reservation system  
• Builds backend skills in authentication, data validation, and modular design  
• Intended for academic and portfolio showcasing


**Legal & Licensing**

This project is shared publicly for learning and demonstration purposes only. Redistribution, copying, or modification for external use is not permitted without permission.

Refer to `COPYRIGHT.txt` for full usage terms.
