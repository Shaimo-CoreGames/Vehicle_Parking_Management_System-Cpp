# Vehicle Management System - C++ Project

This is my first project **Vehicle Management System** implemented in **C++** that helps manage vehicle records, track earned money based on vehicle types, and handle complaints. It provides separate interfaces for **admin** and **customer** users with a console-based interactive menu.

---

## Features
    ### Admin Features
    - Add, search, update, and delete vehicle records
    - List all vehicles in the system
    - Track earned money by vehicle type
    - Register complaints related to vehicles
    - Admin authentication (password-protected)
    
    ### Customer Features
    - Park a vehicle (add vehicle)
    - Search for vehicle records
    - Register complaints
    - Logout functionality
    
    ### Vehicle and Earnings Tracking
    - Supports multiple vehicle types: Car, Bus, Truck, Bike, Cycle
    - Calculates total earnings based on vehicle type:
      - Car: 100 units
      - Bus: 200 units
      - Truck: 400 units
      - Bike: 50 units
      - Cycle: 20 units
    - Maintains a persistent record of total earnings (`EarnedMoney.txt`)
    
    ### Complaint Handling
    - Register complaints for any vehicle by its vehicle number
    - Track complaint count and descriptions
    - Persistent storage in vehicle records file (`VehicleData.txt`)

---

## Technology Stack
    - **Language:** C++  
    - **File Handling:** `fstream` for persistent storage  
    - **Date & Time:** `<chrono>` and `<ctime>` for timestamps  
    - **Console UI:** `iomanip` and colored output for enhanced UX  
