🖥️ Computer Guardian
A Centralized E-commerce & Logistics Ecosystem for Egypt's PC Market
![alt text](https://img.shields.io/badge/Language-PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

![alt text](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

![alt text](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)
Computer Guardian is a full-stack platform engineered to solve the fragmented hardware market in Egypt. Instead of users manually tracking dozens of store inventories, this platform centralizes availability, news, and logistics into a single, high-performance web experience.
🎯 The Problem
The PC building market in Egypt is highly fragmented. Users previously had to:
Navigate 5+ different websites to find specific components (GPUs, CPUs).
Manually verify stock availability via phone or fragmented social media pages.
Coordinate their own delivery from specialized retail hubs.
💡 The Solution
Computer Guardian acts as a centralized "Control Tower." It uses a PHP-driven architecture to:
Aggregate Inventory: Syncs real-time data from 5 major Egyptian hardware retailers.
Streamline Logistics: Handles order confirmation and triggers a dedicated delivery workflow.
Educate Users: Provides integrated tech guides and real-time industry news feeds.
🛠️ Technical Stack
Backend: PHP (Core) for dynamic content management and API-style logic.
Database: MySQL (Relational schema for orders, users, and multi-store inventory).
Frontend: HTML5, CSS3, JavaScript (Responsive UI).
Integration: Real-time data synchronization between partner stores and the central hub.
🚀 Key Features
Centralized Marketplace: Search, filter, and compare components from multiple stores in one view.
Real-Time Availability: PHP backend logic that verifies stock before an order is placed.
Automated Delivery Routing: Integrated logic to coordinate part collection from specialized stores to any location in Egypt.
Dynamic News Hub: A custom-built CMS to manage and serve the latest tech advancements.
📸 Visual Documentation
<details>
<summary><b>🖼️ User Interface & Experience (Click to expand)</b></summary>
<br>
Landing Page	Part Discovery	News Hub
![alt text](https://github.com/user-attachments/assets/bf01fb9b-2d92-452f-9f4f-1b8bcae18b1d)
![alt text](https://github.com/user-attachments/assets/ca3a2b99-44dc-4dda-80c2-0919deb8e79b)
![alt text](https://github.com/user-attachments/assets/b6e73cd5-1701-45ba-b700-4ffb1a36c697)
Detailed Search	Component View	Store Integration
![alt text](https://github.com/user-attachments/assets/d5ed1771-22e9-465f-acd1-02f6a24162d9)
![alt text](https://github.com/user-attachments/assets/aa9bedd6-314f-4cae-a3e9-f21630c0a025)
![alt text](https://github.com/user-attachments/assets/e13aa564-e850-46fb-89dd-0e123392613f)
</details>
<details>
<summary><b>🔐 Authentication & Backend Management</b></summary>
<br>
Sign-Up Page	Database Logic (phpMyAdmin)	Admin Dashboard
![alt text](https://github.com/user-attachments/assets/f9caf1b7-26b4-4104-b621-4b6d83fe0aed)
![alt text](https://github.com/user-attachments/assets/3dc10fb7-323f-4316-a4f6-e9487a04625b)
![alt text](https://github.com/user-attachments/assets/85fd4e30-d5d6-4d3f-8aa2-9f963f4e93f3)
</details>
🏗️ Architecture & Flow
Request: User searches for a component (e.g., RTX 4070).
Verification: PHP script queries the centralized database linked to the 5 partner store inventories.
Transaction: SQL transaction handles the order, ensuring no double-booking of stock.
Logistics: System generates a delivery ticket for the Egyptian logistics team.
🤝 Contribution & License
This project was developed as a full-stack solution for the Egyptian tech market.
License: MIT
Author: Yehia Ibrahim
