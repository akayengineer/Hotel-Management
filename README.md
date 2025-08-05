# Hotel Management System 🏨

This is a Python-based Hotel Management System that allows hotel staff to manage customers, bookings, and generate reports efficiently.

## 📁 Project Structure


**HotelManagementSystem/**

├── main.py

├── login.py

├── dashboard.py

├── customer.py

├── room_booking.py

├── report.py

├── about.py

├── config.py

├── db_config.sql

├── Report/

│   ├── Customer_Report_.pdf

│   └── Room_Report_.pdf

├── images/

│   ├── banner.jpg

│   └── icons/

└── README.md



💡 **Description:**

This Hotel Management System is a desktop-based application developed using Python (Tkinter) for the GUI and MySQL for the database backend. It automates hotel operations such as customer management, room booking, billing (with GST), and report generation in PDF format.

The system includes login authentication and a clean user interface. This project is ideal for beginners in Python and database integration who want to learn CRUD operations, data fetching, PDF generation, and more.

🖥️ **Project Features:**

🔐 1. **Login System**

Secure login interface.

Redirects to the main dashboard after successful authentication.

Includes options: Forgot Password and Login with OTP (future upgrade placeholder).

🏨 2. **Dashboard/Main Window**

Menu-driven interface with following buttons:

Customer

Room Booking

Report

About

Logout

👤 3. **Customer Management**

Add new customer records (name, contact, gender, ID proof, etc.).

Update, Delete, Reset options available.

Connected to MySQL database; data reflects instantly.

Search functionality by Contact Number.

Table displays all customers with real-time MySQL sync.

🛏️ 4. **Room Booking System**

Fetch customer data using contact number.

Enter booking details: Check-in/out date, room type, meal (Breakfast/Lunch/Dinner), days of stay, etc.

Generate room bill with GST included.

Add, Update, Delete, Reset booking data.

Search and view past bookings.

📄 5. **Reports**

Generate customer and booking reports in PDF format.

Automatically stores PDFs in a report folder.

ℹ️ 6. **About**

Displays project title and developer name.

🚪 7. **Logout**

Logs out user and returns to login screen.

📷 **Screenshots:**

**Login Page**

<img width="1366" height="768" alt="Screenshot (105)" src="https://github.com/user-attachments/assets/722b9976-0dca-4e33-8396-131a11e5427f" />


**Main Dashboard**

<img width="1366" height="768" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/da42d3cc-aa2a-4121-96a9-04db7f5f67cd" />


**Customer Management**

<img width="1366" height="768" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/8e4f18f2-0bbb-4033-b83b-e0d11f94f1ce" />


**Room Booking**

<img width="1366" height="768" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/bdd12af0-44b3-4813-873b-961d860ea96b" />


**Report**

<img width="1366" height="768" alt="Screenshot (115)" src="https://github.com/user-attachments/assets/070cf7c7-e9c5-48e4-a108-be704e9c6bee" />

**About Section**

<img width="1366" height="768" alt="Screenshot (124)" src="https://github.com/user-attachments/assets/18c245c8-6cf1-4546-8acb-d26852ebcd63" />

**PDF Report**

<img width="1366" height="768" alt="Screenshot (118)" src="https://github.com/user-attachments/assets/c1e6e64c-7166-4513-b01d-9b9d799a7ce4" />

**📌 Future Improvements:**

OTP-based login

Admin/User role management

Email integration for invoice/report delivery


🙋‍♂️ **Developer:**

Er. Amit Kumar

Built with 💻 using Python + MySQL



