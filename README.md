# Lanka Ice Management System (ERP) 🧊🚚

A comprehensive, production-grade Enterprise Resource Planning (ERP) and Point of Sale (POS) platform custom-built for **Lanka Ice** to streamline ice manufacturing, cool-room inventory tracking, automated shift attendance, and fleet supply chain distribution. 

Developed as the **1st Semester Final Project** for the Graduate Diploma in Software Engineering (GDSE).

---

## 🚀 Key Features

- **Production & Batch Management:** Track ice production cycles, batches, and real-time cool-room stock levels.
- **Supply Chain & Fleet Distribution:** Manage delivery schedules, customer invoicing, and fleet management.
- **Biometric Shift Attendance:** Integrated fingerprint and ID-scanning simulation to automate employee attendance across dual shifts.
- **Fleet GPS Tracking:** Integrated GPS tracking module/simulation for real-time delivery vehicle monitoring and route optimization.
- **Business Intelligence & Reporting:** Real-time generation of sales receipts, delivery orders, and daily production analytics using Jasper Reports.

---

## 🛠️ Tech Stack & Architecture

- **Language:** Java (JDK 11+)
- **UI Framework:** JavaFX (with Scene Builder)
- **Database:** MySQL
- **Architecture Pattern:** Strict Layered Architecture (Controller, Service, Repository patterns)
- **Reporting Engine:** Jasper Reports
- **Build Tools / Libraries:** MySQL Connector, FontAwesome/Icons, Biometric API SDKs

### 🏗️ Architecture Overview
The system follows a strict separation of concerns to ensure scalability and high maintainability:
`UI (JavaFX) ➡️ Controller Layer ➡️ Service (Business Logic) Layer ➡️ Repository (Data Access) Layer ➡️ MySQL Database`

---

## 📸 Screenshots
*(Tip: Add your system screenshots inside a `/screenshots` folder in your repo and link them here)*
| Dashboard | Inventory Management |
|---|---|
| ![Dashboard](https://via.placeholder.com/400x250?text=Dashboard+Screenshot) | ![Inventory](https://via.placeholder.com/400x250?text=Inventory+Screenshot) |

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Kalana-methsara/LankaIce-ERP.git](https://github.com/Kalana-methsara/LankaIce-ERP.git)
