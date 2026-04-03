# GUI-Based Multithreaded Port Scanner (Python)

A high-performance, graphical utility designed for network reconnaissance and Vulnerability Assessment and Penetration Testing (VAPT). This tool allows users to identify open TCP ports and their associated services through an intuitive interface, leveraging Python's concurrency model for maximum efficiency.

## 🚀 Key Features

* **Fast Scanning:** Implements multithreading with a configurable semaphore-controlled worker pool (500+ threads) for rapid results.
* **Real-Time Feedback:** Uses a thread-safe Queue to update the GUI console, progress bar, and elapsed timer without freezing the interface.
* **Service Mapping:** Automatically identifies common protocols (SSH, FTP, HTTP, etc.) using an internal service map.
* **Input Validation:** Robust error handling for IP addresses, hostnames, and logical port ranges (0–65535).
* **Data Persistence:** Built-in functionality to export and save scan results to a `.txt` file for documentation.

## 🛠️ Technology Stack

* **Language:** Python 3.x
* **GUI Framework:** Tkinter
* **Networking:** Socket Programming (TCP/IP)
* **Concurrency:** `threading` & `queue`
* **Synchronization:** Semaphores and Locks (for thread-safe operations)

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shobhith-srivastav/Network-scanner.git
   ```

2. **No external dependencies required:**
   This project uses Python's standard library. Ensure you have Python 3.6+ installed.

## 🖥️ Usage

1. Run the application:
   ```bash
   python port_scanner.py
   ```
2. Enter a **Target IP** (e.g., `127.0.0.1`) or **Hostname** (e.g., `google.com`).
3. Define the **Start Port** and **End Port** range.
4. Click **Start Scan** to begin.
5. Once complete, use **Save Results** to export the findings.

## ⚠️ Disclaimer
This tool is intended for **educational and authorized security testing purposes only**. Scanning targets without explicit permission is illegal and unethical. The developer is not responsible for misuse of this software.

## 👥 End Users
* Junior Network Administrators
* VAPT Analysts
* Cybersecurity Students
* IT Support Technicians
```

 
