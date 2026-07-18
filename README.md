# 🏨 Hotel Reservation System

A sleek, modern, and user-friendly desktop application built entirely in **Java** using **Swing** and **AWT** to streamline hotel room bookings and reservation management. The application features a custom-designed, dark-themed GUI (Graphical User Interface) that provides a smooth and intuitive experience for both guests and hotel administrators.

---

## ✨ Features

* **🔒 Secure User Authentication**: Custom Sign-In and Sign-Up screens with a secure password field and welcoming pop-up dialogue alerts (`JOptionPane`) upon successful login.
* <img width="959" height="563" alt="image" src="https://github.com/user-attachments/assets/af9a51e0-48c8-4215-b46a-5e3f39e296fb" />
* <img width="954" height="565" alt="image" src="https://github.com/user-attachments/assets/d0f7f420-e1e3-4b95-962e-6ef560678b29" />

**📊 Modern Navigation Dashboard**: A centralized hub featuring clean button controls to easily browse rooms, view reservation details, cancel bookings, or process refunds.
<img width="959" height="565" alt="image" src="https://github.com/user-attachments/assets/da76e655-ce5f-493f-8e11-1c48af8b4c7a" />


* **🛌 Dynamic Room Search & Booking**: 
    * Real-time tracking of room availability status (e.g., *Available*, *Booked*).
    * Dynamic display of room categories (Standard, Deluxe, etc.) and standard nightly rates.
      <img width="958" height="563" alt="image" src="https://github.com/user-attachments/assets/09433ce4-008d-45f0-9df4-86875057613e" />
      <img width="959" height="563" alt="image" src="https://github.com/user-attachments/assets/0906e728-9489-4da1-9fdf-bd9afb4be2ce" />
      

* **📅 Booking Ledger**: A clear table view displaying active reservations with essential details such as unique **Reservation IDs**, room numbers, check-in/check-out dates, and total booking costs.
* <img width="959" height="564" alt="image" src="https://github.com/user-attachments/assets/8b2e7255-6632-4392-96ec-76fe826c5542" />
* <br>

* **💸 Refund & Cancellation System**: 
    * Select active reservations from a list to cancel them instantly.
    * Features a **one-click 50% refund processing** pipeline, allowing administrators or users to easily trigger and process policy-compliant refunds.
      <img width="959" height="563" alt="image" src="https://github.com/user-attachments/assets/ef7f2eda-39d4-4bb8-a6da-12d4c6ed2910" />
      <img width="959" height="563" alt="image" src="https://github.com/user-attachments/assets/47fd8454-b22b-4919-8d74-5a0592127de4" />
      <img width="959" height="564" alt="image" src="https://github.com/user-attachments/assets/1845454b-39c1-4a4d-97d0-2b61e245bbdc" />
     




---

## 🛠️ Tech Stack & Libraries

* **Language**: Java (JDK 8 or higher)
* **GUI Framework**: Java Swing & AWT (Abstract Window Toolkit)
* **UI Theme**: Custom Dark Mode Styling

---

## 📂 Project Structure

```text
src/
├── controller/      # Handles business logic and UI event listeners
├── model/           # Data models (User, Room, Reservation classes)
├── view/            # Swing GUI frames and panels (Login, Dashboard, Booking, etc.)
└── database/        # Database connectivity and helper files
