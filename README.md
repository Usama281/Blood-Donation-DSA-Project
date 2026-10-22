# 🩸 Blood Donation System

A desktop-based **Blood Donation and Inventory Management System** developed in **Java (Swing)** with a **MySQL** database backend. Built as a **Data Structures & Algorithms (DSA)** project, this application streamlines blood bank operations by managing donor profiles, blood purchasers/recipients, and available blood packet inventory.

---

## ✨ Key Features

* **User Authentication & Dashboard:** Secure login interface (`Login.java`) and central navigation dashboard (`start_page.java`).
* **Donor Management:** Register new donors (`Donor_reg.java`), manage donor profiles (`Donor_account.java`), and remove outdated records (`deleteform.java`).
* **Purchaser / Recipient Management:** Register blood purchasers (`Purchaser_reg.java`), manage accounts (`Purchaser_account.java`), view buyer records (`buyer_detail.java`), and delete buyer entries (`delete_buyer_details.java`).
* **Search Functionality:** Quickly search and filter blood donors (`search_donor.java`) based on blood group and details.
* **Blood Inventory Tracking:** Monitor available blood packets in stock (`Available_packets.java`).
* **Database Integration:** Persistent storage and retrieval using JDBC and MySQL (`DBConnect.java`).

---

## 🛠️ Tech Stack

* **Language:** Java
* **GUI Framework:** Java Swing / AWT (`.form` & `.java` via NetBeans GUI Builder)
* **Database:** MySQL
* **Database Driver:** MySQL Connector/J (`mysql-connector-j-8.4.0.jar`)
* **IDE & Build Tool:** Apache NetBeans (Ant `build.xml`)

---

## 📂 Project Structure

```text
Blood_Donation_System/
├── src/blood_donation_system/
│   ├── Blood_Donation_System.java   # Main application entry point
│   ├── start_page.java              # Home dashboard screen
│   ├── Login.java                   # User authentication module
│   ├── DBConnect.java               # MySQL JDBC connection handler
│   ├── Donor_reg.java               # New donor registration form
│   ├── Donor_account.java           # Donor profile & account view
│   ├── search_donor.java            # Donor search module
│   ├── Purchaser_reg.java           # Purchaser/recipient registration form
│   ├── Purchaser_account.java       # Purchaser profile & account view
│   ├── buyer_detail.java            # Buyer transaction & record details
│   ├── Available_packets.java       # Blood packet inventory tracker
│   ├── deleteform.java              # Donor record deletion utility
│   └── delete_buyer_details.java    # Buyer record deletion utility
├── mysql-connector-j-8.4.0.jar      # MySQL JDBC Driver
├── nbproject/                       # NetBeans project configuration
└── build.xml                        # Ant build script
