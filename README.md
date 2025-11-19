# DAA-LAB-ASSIGNMENT-5
# Delivery Route Optimization – Multi-Algorithm Integration

## 📦 Project Overview
This project models and solves an E-commerce Delivery Route Optimization problem using:

- Recurrence-based cost modeling  
- Greedy selection for parcel packing  
- Dynamic Programming for time-window feasibility  
- Graph algorithms (Dijkstra, Prim/Kruskal) for navigation  
- TSP brute-force and DP for exact routing on small instances  

It demonstrates how multiple algorithmic paradigms combine to produce a working logistics optimization pipeline.

---

## 🚚 Problem Description
A vehicle starts at a warehouse and must deliver parcels to customer locations while:

- Minimizing total distance/time  
- Respecting weight capacity  
- Respecting delivery time windows  
- Maximizing parcel value  

Inputs include:

- Locations and a distance matrix  
- Parcel attributes (value, time window, weight)  
- Vehicle capacity  

---

## 🧠 Algorithms Used

### **Unit 1: Recurrence Relations**
Cost modeling function exploring next-location decisions.

### **Unit 2: Greedy + Dynamic Programming**
- Greedy knapsack (value/weight ratio) for parcel selection  
- DP to enforce valid time windows  

### **Unit 3: Graph Algorithms**
- **Dijkstra:** compute shortest paths  
- **MST (Prim/Kruskal):** approximate coverage  

### **Unit 4: Traveling Salesman Problem**
- Brute-force enumeration  
- Held-Karp DP for small n  
- Demonstrates intractability  

---

## 📊 Profiling & Visualization Outputs

### **Profiling**
- Execution time vs number of TSP nodes (3–6)  
- DP runtime growth vs number of parcels  
- Memory usage via `memory_profiler`  

### **Visualizations**
- Route network graph (NetworkX)  
- Profit vs weight scatter plot  
- Delivery time-window plot  
- TSP route map  

---

## 📂 Repository Structure
