# 📊 Graph Degree Analysis using C

## 📌 Overview
This project was developed as part of the CSE106 – Discrete Mathematics course at East West University.

The program generates a random directed graph using an adjacency matrix and calculates the in-degree and out-degree for each vertex. It also measures computational time and verifies a fundamental property of directed graphs:

Sum of In-Degrees = Sum of Out-Degrees

This project demonstrates how theoretical concepts from graph theory can be implemented and analyzed using C programming.

---

## ⚙️ Features
- Random graph generation using adjacency matrix  
- In-degree calculation (incoming edges)  
- Out-degree calculation (outgoing edges)  
- Total degree verification  
- Execution time measurement using clock()  
- Dynamic memory allocation (malloc and free)  

---

## 🧠 Concepts Used
- Graph Theory  
- Directed Graphs  
- Adjacency Matrix Representation  
- In-Degree & Out-Degree  
- Time Complexity Analysis  
- Dynamic Memory Management in C  
- Performance Measurement  

---

## 🧮 Algorithm Explanation

1. Graph Generation  
A random adjacency matrix of size n × n is created:
- 1 → edge exists  
- 0 → no edge  

2. In-Degree Calculation  
For each vertex, count incoming edges (column-wise sum).

3. Out-Degree Calculation  
For each vertex, count outgoing edges (row-wise sum).

4. Verification  
Check if total in-degree equals total out-degree.

5. Time Measurement  
Execution time is calculated using clock() function.

---

## ⏱️ Time Complexity

The overall time complexity of this program is:

O(n^2)

Because:
- Graph generation → O(n^2)  
- In-degree calculation → O(n^2)  
- Out-degree calculation → O(n^2)  

As the number of vertices increases, execution time grows quadratically.

---

## 📈 Sample Results

Vertices (n)    Time (ms)
1000            29  
2000            115  
3000            288  
4000            499  
5000            780  

These results demonstrate O(n^2) growth.

---

## ▶️ How to Run

Step 1: Compile  
gcc graph.c -o graph  

Step 2: Run  
./graph  

Step 3: Enter the number of vertices when prompted.

---

## 📂 Project Structure

graph.c  
README.md  
report.docx  

---

## 👨‍💻 Author

Tasnim Ahmed Raisa
Md. Fahim Rahman  

---

## 🤝 Contributors
- Md. Bellal Mollah
  
---

## 📌 Instructor
Nishat Tasnim  
Department of Computer Science & Engineering  
East West University  

---

## 🚀 Future Improvements
- Add graph visualization  
- Optimize for large graphs  
- Use adjacency list instead of matrix  
- Improve performance for large inputs  

---

## 💡 Key Takeaway
This project shows how graph theory concepts and time complexity analysis can be applied in real programming to analyze computational performance.
