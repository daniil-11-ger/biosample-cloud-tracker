# biosample-cloud-tracker
Cloud-based Android application for real-time laboratory inventory and sample tracking. Developed using MIT App Inventor
# BioSample Cloud Tracker

A cloud-based Android application developed using MIT App Inventor for real-time laboratory inventory management.

## Key Features
* **Cloud Synchronization:** Uses `CloudDB` to sync lists across multiple devices (perfect for lab teams).
* **Dynamic Inventory:** Add and remove items (reagents, DNA samples, primers) on the go.
* **Persistent Storage:** Data is stored remotely and persists even after closing the app.

##  Tech Stack
* **Platform:** Android
* **Environment:** MIT App Inventor
* **Backend:** CloudDB (Redis-based)

## Logic Overview
The app utilizes event-driven programming blocks to handle data input, selection picking, and cloud storage triggers.
![App Logic](blocks.png)
![App Logic](blocks (1).png)
