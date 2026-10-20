# MeoCRM ERP Desktop (Java Swing)

An enterprise-style **CRM + ERP desktop application** built in **Java Swing** with a modern **Flamingo ribbon interface**. 

It brings CRM, sales, purchasing, inventory, finance, HR, manufacturing basics, and reporting together into a single, fast, keyboard-friendly desktop client.

> ⚠️ **Project Status:** This is an actively developed, working local build. The enterprise proposal is **not yet 100% complete**. We publish honest, detailed status reports rather than overclaiming completeness.

---

## 📸 Screenshots

<img width="1280" height="693" alt="image" src="https://github.com/user-attachments/assets/3a63dfa9-bf43-4c9f-8c0c-932d932206aa" />
<img width="1280" height="695" alt="image" src="https://github.com/user-attachments/assets/ecd90575-9147-4062-9150-18a3255632fe" />
<img width="1280" height="694" alt="image" src="https://github.com/user-attachments/assets/27a5bad7-56de-427b-b89b-b74ebf6e3845" />
<img width="1280" height="694" alt="image" src="https://github.com/user-attachments/assets/b40171cb-f8f6-4a0a-b4be-44a1a1a3cb6f" />
<img width="1280" height="694" alt="image" src="https://github.com/user-attachments/assets/7823f6d9-6d3a-470d-8fc0-165fd7afaf97" />
<img width="1280" height="693" alt="image" src="https://github.com/user-attachments/assets/91575ed8-d57b-4d06-a10b-74fdeed22568" />
<img width="1280" height="693" alt="image" src="https://github.com/user-attachments/assets/2847bd2a-7974-4fac-9c4a-9ea0ab2684b9" />
<img width="1280" height="694" alt="image" src="https://github.com/user-attachments/assets/489e6c03-8a69-4522-a70f-2612665f51ea" />
<img width="1280" height="695" alt="image" src="https://github.com/user-attachments/assets/afe8573d-e943-493e-9d9b-cff20b326571" />
<img width="1280" height="693" alt="image" src="https://github.com/user-attachments/assets/4e1749b7-813d-4727-938c-d63d97d1bbcc" />


Here is a look at the main interface:

*(If you named your image something else, change `screenshot-main.png` below to match your exact file name)*

![MeoCRM ERP Main Dashboard](screenshot-main.png)

*Add more screenshots here if you like! For example:*
<!-- ![Sales Pipeline Kanban](screenshot-kanban.png) -->
<!-- ![Finance Reports](screenshot-reports.png) -->

---

## 🌟 Features

* **CRM:** Leads, contacts, deals (Kanban & List), tasks, notes, and customer 360 view.
* **Sales:** Multi-line quotations, partial quote-to-order-to-invoice conversion, order holds, and pick/pack planning.
* **Purchasing:** Purchase orders, partial goods receipts, three-way matching (PO ↔ Receipt ↔ Invoice), and GRNI control.
* **Inventory:** Stock ledger, weighted-average costing, reservations, physical counts, and min/max reorder alerts.
* **Finance:** Chart of accounts, double-entry journals, credit limits, AR/AP, trial balance, and period close.
* **HR & Payroll:** Employee register, attendance, and monthly payroll/payslips.
* **Reporting:** Searchable catalog, JasperReports (PDF), protected CSV, and typed XLSX exports.
* **UI/UX:** Flamingo ribbon, saved grid layouts, global search, Ctrl+K command palette, and in-app notifications.
* **Security:** PBKDF2 password hashing, session expiry, role-based access, and optimistic concurrency checks.

## 🛠️ Technology Stack

* **Language:** Java (Targeting Java 11+)
* **User Interface:** Java Swing + Flamingo Ribbon
* **Database:** Local SQLite (Unencrypted local storage)
* **Reporting Engine:** JasperReports
* **Architecture:** Layered (Presentation separated from domain services and persistence adapters)

## 🚀 How to Run the App

1. **Install Java:** Ensure you have a Java 11 (or newer) Runtime Environment installed (tested on JRE 17).
2. **Download:** Download the latest `.jar` file from the **Releases** section on the right side of this page.
3. **Run:** Open your terminal or command prompt in the folder where you downloaded the file and run:
   ```bash
   java -jar MeoCRM-ERP.jar
