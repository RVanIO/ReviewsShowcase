# ✨ Fairytale World Kiosk (Offline Feedback System)

A fully autonomous, offline-first Flutter application designed for retail kiosks to collect customer feedback. Features a glassmorphism UI, silent camera capture for security, and a robust data export system (Excel + Photos zipped).

<p align="center">
  <img src="https://github.com/user-attachments/assets/18632845-7d26-4c89-befd-fbdc5ce062c8" width="22%" alt="Main Screen" style="border-radius: 10px; margin: 10px;" />
  <img src="https://github.com/user-attachments/assets/dd6fb900-1990-4426-bb69-f03612b7f7d7" width="22%" alt="Success Screen" style="border-radius: 10px; margin: 10px;" />
  <img src="https://github.com/user-attachments/assets/7f7bd5dc-0244-4a97-98b6-d6fe4816204f" width="22%" alt="Admin Panel" style="border-radius: 10px; margin: 10px;" />
</p>
## 🚀 Key Features

* **Offline-First Architecture:** Uses **Hive (NoSQL)** to store data locally, ensuring 100% uptime regardless of internet connection.
* **Silent Photo Capture:** Automatically captures a selfie via the front camera upon submission for identity verification/security.
* **Data Export Engine:**
    * Generates formatted **Excel (.xlsx)** reports.
    * Bundles images and reports into a single **ZIP archive**.
    * Uses native sharing dialogs to export data.
* **Glassmorphism UI:** Modern, responsive design with custom animations, gradients, and **Google Fonts** integration.
* **Admin Panel:** hidden functionality (long-press access) to view logs, manage data, and perform exports.

## 🛠 Tech Stack

* **Framework:** Flutter (Dart)
* **Local Database:** Hive
* **Hardware:** Camera (`camera` package)
* **File System:** `path_provider`, `archive`, `excel`
* **UI:** Glassmorphism effects (`dart:ui`), Custom Animations, Google Fonts

## 📦 How to Build

1.  Clone the repository.
2.  Install dependencies:
    ```bash
    flutter pub get
    ```
3.  Run the app:
    ```bash
    flutter run
    ```

## 📱 Permissions

The app requires the following permissions to function correctly:
* Camera (for photo capture)
* Storage (for saving temporary reports)

---
## 👨‍💻 Author

**Rostyslav**

*Python Backend Engineer | Full-Stack Architect*

[LinkedIn](https://www.linkedin.com/in/rnykyforchyn/)
