# Bike Rental System Simulation

A simulation-based bike rental system implemented in Python, featuring user interaction, bike reservations, repairs, and final reports.

## 📌 Project Overview

This project models a city bike rental service using object-oriented programming. It simulates real-world behaviors such as:

- Renting and returning bikes
- Reserving bikes in advance
- Reporting and processing bike repairs
- Managing station capacities and availability
- Tracking system activity through statistics

All logic is handled in a simulation loop through a command-line interface.

## 🧱 System Components

The system is structured into the following core classes:

- `Bike` – represents an individual bike
- `Station` – manages bike storage and availability
- `User` – can rent, return, reserve, and report bikes
- `Rental` – tracks rental sessions
- `Reservation` – allows booking bikes for a limited time
- `Repair` – handles reported issues and repair duration
- `Simulation` – runs the main system loop
- `Report` – generates a summary of the simulation

## ✅ Features

- Command-line interface for interactive simulation
- Reservation expiration logic
- Automatic repair completion
- Data loading from JSON files
- Final statistical report generation
- UML class diagram (`diagram.png`)
- Unit tests using `unittest`


## 🛠️ Technologies

- Python 3.x
- `datetime`, `unittest`, `random`
- RMarkdown (for PDF documentation)
- Jupyter Notebook 

