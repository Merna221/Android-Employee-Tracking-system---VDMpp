# Android-Employee-Tracking-system---VDMpp
Fieldwork-based employee tracking system using Android and Web applications with GPS, image logging, salary management, and attendance monitoring — formally specified in VDM++ using Overture.
# Android Employee Tracker (VDM++ Specification)

This project is a formally specified system using **VDM++ (vdmpp)** in the **Overture** tool. It outlines an employee tracking system built for fieldwork-based organizations using both Android and web platforms.

## 📱 Project Overview

The **Android Employee Tracker** is designed to monitor and manage employee activities, attendance, and salary based on GPS tracking and login/logout image verification. 

- **Employees** use the Android app for login/logout, GPS tracking, and image capture.
- **Admins** and **HR** use the web interface for monitoring, salary processing, and attendance management.

## ✨ Features

- Image capture on login/logout
- Automatic GPS tracking every 5 minutes
- Admin/HR dashboard for:
  - Viewing employee location by ID and date
  - Checking attendance and salary
  - Changing employee passwords
- Unique credentials for employee login
- Prevents proxy attendance

## 📂 VDM++ Modules

This project is specified in **VDM++** with the following core files:

| File Name             | Description |
|-----------------------|-------------|
| `AdminSystem.vdmpp`   | Handles employee creation, credentials, and admin-side operations. |
| `AttendanceManager.vdmpp` | Manages check-ins, check-outs, and attendance records. |
| `Employee.vdmpp`      | Defines employee attributes and behaviors. |
| `EmployeeSystem.vdmpp`| Coordinates employee system behavior including login/logout. |
| `HRSystem.vdmpp`      | Manages HR-side functions such as salary and attendance checks. |
| `Location Tracker.vdmpp` | Tracks and records GPS location periodically. |
| `SalaryManager.vdmpp` | Computes and tracks employee salary. |

## 🛠️ Requirements

- [Overture Tool](https://overturetool.org/) (VDM++ IDE)
- Windows/macOS/Linux
- No external libraries or SDKs required

## 🚀 Getting Started

1. **Download and install the [Overture IDE](https://overturetool.org/download.html).**
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Android-Employee-Tracker-VDMpp.git
