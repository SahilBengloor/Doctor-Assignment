# Doctor-Assignment
The Online Appointment Management Portal is a lightweight web system that allows users to browse doctors, view specializations and fees, and easily book appointments with real-time slot validation. It includes login, dashboard, appointment management, and prevents double-booking.

# Online Appointment Management Portal

A simple web-based system built using **ASP.NET WebForms + SQL Server** for booking doctor appointments.  
This project was created as part of a technical assignment.

---

## 🚀 Features
- User Registration & Login  
- View Doctors (Name, Specialization, Fees)  
- Book Appointment (Doctor, Date, Time)  
- Live Slot Availability (Booked slots disabled)  
- View & Cancel My Appointments  
- Modern UI with Hospital Theme  
- Session-based Dashboard  

---

## 🛠️ Tech Used
- ASP.NET WebForms (C#)
- SQL Server
- HTML + CSS
- Visual Studio 2022

---

## 📌 Pages Included
- Login / Register  
- Dashboard  
- Doctors  
- Book Appointment  
- My Appointments  
- Logout  

---

## 🔧 How to Run
1. Clone the project  
2. Open in Visual Studio  
3. Ensure SQL connection string is correct in **Web.config**  
4. Run using IIS Express  

Database Tables:
- `Users`
- `DoctorSlots`
- `Appointments`

---

## 📂 Database Setup
Create these tables:

Users(UserID, FullName, Email, PasswordHash)
DoctorSlots(SlotID, DoctorName, TimeSlot)
Appointments(AppointmentID, PatientName, PatientEmail, DoctorName, AppointmentDate, TimeSlot, ConsultationFee)


---

## 👨‍💻 Developer  
**Sahil B**

---

This README is intentionally simple for hosting/demo purposes.  
If you want a **shorter**, **one-line**, or **more professional** version — tell me!
