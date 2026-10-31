# ✈️ SkyControl – Air Traffic Management System

An interactive, browser-based **Air Traffic Management System** developed as a Data Structures and Algorithms course project at **SRM Institute of Science and Technology, Ramapuram**.

SkyControl simulates an air traffic control tower where aircraft movements, landing priorities, runway availability, flight conflicts, and airport routes are managed using fundamental data structures and algorithms.

## 🌐 Live Demo

**[Launch SkyControl Live Demo](https://av-akshayprasanna.github.io/Air-Traffic-Management-System/)**

Access the interactive air traffic control simulation directly in your browser.

## 📌 About the Project

SkyControl demonstrates how data structures and algorithms can be applied to an air traffic management environment. The system simulates aircraft moving through airspace, detects potential separation conflicts, prioritizes incoming flights, manages runway availability, and calculates shortest routes between airports.

All core interactions run directly in the browser.

## 🚀 Key Features

- **Airspace Radar:** Simulates aircraft movement and displays positions, headings, and altitude information.
- **Conflict Detection:** Checks aircraft pairs for potential separation conflicts based on distance and altitude.
- **Auto-Resolve:** Simulates conflict resolution by adjusting an aircraft's target altitude.
- **Landing Priority Queue:** Prioritizes emergency, medical, low-fuel, and routine flights.
- **Runway Management:** Manages three runways and simulates aircraft landing and runway clearance.
- **Route Planner:** Finds shortest airport routes using Dijkstra's algorithm.
- **Interactive Network Globe:** Displays the airport network on a rotatable globe, with route visualization and airport closure controls.

## 🧠 Data Structures & Algorithms

| Structure / Algorithm | Application |
|---|---|
| Binary Min-Heap | Landing priority queue and Dijkstra's algorithm frontier |
| Graph (Adjacency List) | Airports as vertices and route legs as weighted edges |
| Dijkstra's Algorithm | Shortest-path calculation between airports |
| Array | Aircraft tracking and pairwise conflict detection |
| Hash Set | Unique callsign validation and conflict-pair tracking |
| Sorting | Generating the landing order |

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript
- SVG and HTML Canvas
- Google Fonts

## ▶️ Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/AV-AkshayPrasanna/Air-Traffic-Management-System.git
   ```
2. Open the project folder.
3. Open **index.html** in Google Chrome or another modern browser.

The application runs in the browser. No backend server or package installation is required for its core functionality.

## 👨‍💻 Project Team

**SRM Institute of Science and Technology — Department of Computer Science and Engineering**

| Team Member | Register Number |
|---|---|
| M. Dev Aryan | RA2511003020467 |
| S. Kaushik | RA2511003020472 |
| A.V. AkshayPrasanna | RA2511003020473 |

## 🎓 Course Details

- **Course:** Data Structures and Algorithms
- **Course Code:** 21CSC201J
- **Institution:** SRM Institute of Science and Technology, Ramapuram

## 📚 Project Objective

To demonstrate practical applications of data structures and algorithms through an interactive air traffic management simulation.

---

**SkyControl — Smarter Routes. Safer Skies.** ✈️
