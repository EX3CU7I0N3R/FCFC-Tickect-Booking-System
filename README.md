# 🎟️ Concert Ticket Booking System

A modern and interactive ticket booking system built using **Python**, **CustomTkinter** for the GUI, **SQLite** for backend ticket management, and **multithreading** to manage user queues efficiently through a First-Come, First-Served (FCFS) scheduling system.

## 🌟 Features

- **Queue Management (FCFS):** Users are added to a queue, and tickets are assigned based on their position in the queue.
- **Seat Selection:** Once their turn arrives, users can select seats visually from a grid of available seats.
- **Multithreading:** The queue is processed in the background, ensuring that the UI remains responsive.
- **SQLite Database:** Handles ticket availability and booking status persistently.
- **Dark Themed UI:** A sleek, modern interface built with **CustomTkinter** in dark mode.

---

## 🚀 Getting Started

Follow these steps to get the project up and running on your local machine.

### Prerequisites

Ensure you have the following installed:

- **Python 3.8+** ([Download Python](https://www.python.org/downloads/))
- **Git** (optional, if you want to clone the repository) ([Download Git](https://git-scm.com/downloads))

### Installation

1. **Clone the repository** (optional):

```bash
git clone https://github.com/EX3CU7I0N3R/FCFC-Tickect-Booking-System.git
cd Concert-Ticket-Booking-System
```

## 🖥️ Usage

1. **Join the Queue**: Users can join the ticket booking queue by clicking the "Join Queue" button. They are assigned a random User ID and added to the queue.

2. **Queue Processing**: The system automatically books tickets for users in the queue based on the First-Come, First-Served policy.

3. **Seat Selection**: When it is a user’s turn, the seat selection window opens, allowing them to choose their seats. 

4. **Form Submission**: After selecting seats, users can fill in a simple form with their name and username before proceeding to book their tickets.

5. **Status Updates**: The system provides real-time feedback on ticket availability and booking status via a status bar.

---

## 📜 Future Enhancements

Some features that can be added in future iterations:

- **Payment Gateway Integration**: Enable online payment for tickets.
- **Email Notifications**: Send booking confirmations to users via email.
- **Admin Panel**: Implement an admin interface for managing tickets and users.

---

## 📄 License

This project is licensed under the MIT License, refer the License for more details.

---

## 🛠️ Built With

- **Python** - The core programming language.
- **CustomTkinter** - A modern, customizable GUI library for Python.
- **SQLite** - Lightweight, file-based database for managing tickets.
- **Multithreading** - To handle background tasks and keep the GUI responsive.
