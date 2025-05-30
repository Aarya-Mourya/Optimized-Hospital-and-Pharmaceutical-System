# Optimized-Hospital-and-Pharmaceutical-System

An integrated software and teleoperation solution designed to streamline hospital logistics and pharmaceutical delivery. This project combines robotic teleoperation with smart dashboards to ensure timely medicine dispatch, efficient inventory tracking, and seamless human-machine collaboration in a medical environment.

## 🚀 Project Overview

This system simulates an optimized hospital environment where medicines and medical supplies are delivered using teleoperated robotic platforms. Alongside, a dashboard manages pharmaceutical logistics, order tracking, and delivery history to assist hospital staff with minimal error and maximum efficiency.

## 🔧 Core Features

### 🤖 Robotics & Teleoperation

- **Remote Robot Control**: Operators can control the robot using a teleoperation interface, ideal for environments where autonomous navigation is risky.
- **ROS2 Integration**: Built on ROS2 middleware for real-time communication, control, and future scalability to autonomous tasks.
- **Delivery Simulation**: The robot is designed to carry out virtual delivery tasks within a simulated hospital or pharmacy layout.
- **Feedback Loop**: Status of delivery, including success/failure, is sent back to the operator interface.

### 📊 Software Dashboard (Pharma Pulse)

- **Order Management**: Track prescription fulfillment, dispatch timing, and real-time status of medicine orders.
- **Medicine Database**: Store and search medicines, with details such as expiry date, dosage, and quantity.
- **User Roles**: Doctor, pharmacist, and admin access with tailored functionalities.
- **Delivery History Logs**: Full audit trail of previous deliveries, handled orders, and dispatched medications.
- **Alerts and Notifications**: Automated alerts for low inventory and expired drugs.

## 🧠 Tech Stack

- **Frontend**: ReactJS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Robotics**: ROS2 Humble, Python3
- **Simulation & Control**: Custom teleop script (Python-based) with real-time robot command publishing

## 🛠 Setup Instructions

### Prerequisites

- ROS2 Humble Fitzroy installed
- Node.js and MongoDB installed locally
- Python3 (with required packages listed in `requirements.txt`)
