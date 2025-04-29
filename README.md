# MLT PowerStation

MLT PowerStation is a lightweight, standalone desktop application designed for small automotive shops, quick lube centers, and independent mechanics.  
It provides a simple and affordable way to manage customer records, vehicle specifications, service pricing, and repair orders — without needing expensive or complicated systems.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Future Plans](#future-plans)

---

## About the Project

MLT PowerStation was created to make it easy for smaller shops to track customers, check vehicle specs, look up service codes and prices, and generate simple repair orders.  
The system brings everything together into one place — customers, services, specs, resets — with no complicated setup or ongoing costs.  
It's designed to be simple, fast, and tailored to the real-world needs of everyday mechanics.

---

## Features

- **Customer Management**: Add, view, and manage customer information  
- **Service Pricing Lookup**: Check common service prices through a dedicated database  
- **OBD-II Code Lookup**: Reference common trouble codes and definitions  
- **Oil Light Reset Instructions**: Find basic reset instructions for servicing vehicles  
- **Vehicle Specification Reference**: Look up oil viscosity, capacity, and wheel torque specs  
- **Repair Order Generation**: Generate printable repair orders for customer records  
- **Standalone Executable**: Run directly as a `.exe` without needing Python installed

---

## Tech Stack

- **Backend**: Python (tkinter GUI)
- **Data Management**: CSV Files (customers, codes, prices, specs, reset info)
- **Packaging**: PyInstaller (for executable builds)

---

## Getting Started

You can either run the executable directly or set up from source:

### Option 1: Run the Executable
- Download `MLTPowerStation.exe` from the [Releases](https://github.com/Varioli/MLTPowerStation/releases) page (if available)
- Run it — no installation required

### Option 2: Run from Source

Clone the repository:

```bash
git clone https://github.com/Varioli/MLTPowerStation.git
cd MLTPowerStation
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Then run the application:

```bash
python MLTPowerStation.pyw
```

---

## Future Plans

- **Service History Tracking** per customer  
- **Printable Receipts** directly from the application  
- **Expanded Vehicle Database** (more makes/models)  
- **Data Backup Options** (cloud or external drives)  
- **Enhanced OBD-II Code Support** with deeper diagnosis recommendations

---
