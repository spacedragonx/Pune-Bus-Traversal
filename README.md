# 🚍 Pune City Bus Route Navigator

**A C++ terminal-based application to explore and calculate shortest bus routes, distances, and fare estimates across Pune city.**

![C++](https://img.shields.io/badge/Language-C%2B%2B-blue)
![Graph Algorithms](https://img.shields.io/badge/Algorithms-Dijkstra%2C%20DFS%2C%20Stack-green)
![Status](https://img.shields.io/badge/Interface-CLI-orange)

---

## 🧭 Overview

This project implements a **graph-based routing system for Pune's bus stops**. Using a graph traversal engine powered by Dijkstra’s algorithm and custom stack-based DFS, it allows users to:

- Explore all bus stops
- View the full map of direct connections
- Find the **shortest distance or time**
- View optimal paths with **interchanges and total fare**
- Use flexible input options: by name, code, or serial number

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 📍 List All Stops | Displays all the known bus stops in Pune |
| 🗺️ Map View | Prints a textual map showing all connections and distances |
| 🧮 Shortest Distance | Calculates the shortest distance (km) using Dijkstra’s algorithm |
| ⏱️ Shortest Time | Estimates travel time with halt + travel logic |
| 🔀 Optimal Route | Lists path taken and interchange count |
| 🔤 Input Modes | Choose stops via serial number, name, or generated code |


---

## 🧠 Internals

### 🚏 Graph Representation

- **Bus Stops** → Nodes  
- **Routes between Stops** → Weighted Edges  
- **Weights** → Distance (km)

### ⚙️ Algorithms Used

- ✅ **Dijkstra's Algorithm** – for shortest distance/time path
- ✅ **Custom Stack-Based DFS** – to find minimal path/time
- ✅ **Interchange Detection** – for smart multi-line navigation

### 🧮 Time Calculation Formula



Total Time = 120 sec (fixed halt) + 40 sec * distance

Displayed as: ceil(Total Time / 60) in minutes


Result is converted to minutes and shown in output.




---

## 🖥️ User Menu

- WELCOME TO THE PUNE SMART PATH*

- LIST OF ACTIONS

    **1.** LIST ALL THE STATIONS IN THE MAP

    **2.** SHOW THE BUS STOP MAP

    **3.** GET SHORTEST DISTANCE FROM A 'SOURCE' TO 'DESTINATION'

    **4.** GET SHORTEST TIME TO REACH FROM 'SOURCE' TO 'DESTINATION'

    **5.** GET SHORTEST PATH (DISTANCE WISE)

    **6.** GET SHORTEST PATH (TIME WISE)

    **7.** EXIT THE MENU


---


## Screenshots


###  Application Menu (CLI)
![Menu](https://github.com/spacedragonx/Pune-Bus-Traversal/blob/main/Screenshots/Menu.png?raw=true)

###  Sample Map Output
![Map](https://github.com/spacedragonx/Pune-Bus-Traversal/blob/main/Screenshots/Map.png?raw=true)

### Shortest distance between source and destination Stations.
![Distance](https://github.com/spacedragonx/Pune-Bus-Traversal/blob/main/Screenshots/Distance.png?raw=true)

### Shortest time to reach destination station 
![Time](https://github.com/spacedragonx/Pune-Bus-Traversal/blob/main/Screenshots/Time.png?raw=true)

### Example Route Output
![Route](https://github.com/spacedragonx/Pune-Bus-Traversal/blob/main/Screenshots/Route.png?raw=true)


---

## 🛠️ How to Compile and Run

> Make sure you have a C++ compiler (e.g., `g++`) installed.

```bash
g++ Pune_Bus_Routes.cpp -o bus
./bus
```

---

## 🧭 Future Enhancements

- 🖥️ GUI using SFML/Qt

- 📱 Mobile app (Android/iOS)

- 🗣️ Multi-language support

---
## 🙌 Author
Onkar Patil

📧 onkarpatil729@gmail.com

🔗 www.linkedin.com/in/onkar-patil-6862b22a5


