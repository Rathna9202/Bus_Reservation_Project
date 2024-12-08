The Bus Reservation Console Project is a console-based application developed using Java for backend logic and MySQL for database management. 
This project aims to provide a seamless system for booking, managing, and viewing bus reservations. 
It is suitable for learning and implementing the integration of Java with relational databases.

Key Features:

Bus Information Display:

Displays bus details including:
    Bus Number
    AC Availability (Yes/No)
    Seating Capacity

Interactive Booking Process:
    Name: For personalized ticket reservation.
    Bus Number: To select the desired bus.
    Travel Date (dd-mm-yyyy): Ensures flexibility for planning trips.
    Verifies availability and provides real-time seat booking updates.

Displays a booking summary:
    User Name
    Bus Number
    Date of Travel
    Stores booking details in the MySQL database.

AC and Non-AC Differentiation:
    Highlights whether a bus is AC or non-AC, helping users make comfort-based choices.

Database Management:
  MySQL database tables to store:
    Bus Details (bus_id, AC availability, capacity).
    Bookings (name, bus_id, date).
    Implements relational database design for efficiency.

Error and Validation Handling:
    Ensures valid inputs for date, bus number, and user details.
    Prevents duplicate bookings and manages database integrity.

Technical Details:
  Technologies Used:
    Frontend: Java Console Application (with ASCII-style logo design).
    Backend: Java (OOP principles, JDBC for database integration).
    Database: MySQL for relational data management.
    Key Libraries: JDBC, SimpleDateFormat for date parsing and validation.

Output Shows in Console:
![Screenshot 2024-12-08 130838](https://github.com/user-attachments/assets/b47d245f-5f57-4b5f-8403-17557bb000dd)


Database(MySQL):
![Screenshot 2024-12-08 132917](https://github.com/user-attachments/assets/6ca741cd-9f91-4b7e-a6e6-1143018402a9)
