# Computational Geometry and Algorithms Project

This project implements and visualizes several algorithms in computational geometry and linear programming. It includes:

**Part 1: Convex Hull Algorithms**

* **Incremental Algorithm:** An algorithm that constructs the convex hull of a set of points by iteratively adding points and maintaining the convexity.
* **Gift Wrapping Algorithm:** Also known as the Jarvis march, this algorithm finds the convex hull by iteratively finding the next point on the hull by considering angles.
* **Divide and Conquer Algorithm:** This algorithm recursively divides the set of points, computes the convex hull of each subset, and merges the results.
* **Quickhull Algorithm:** A divide-and-conquer algorithm similar to quicksort, which partitions points based on their distance from a line.

**Part 2: Linear Programming**

* **Incremental Linear Programming:** Solves a linear programming problem by incrementally adding constraints and finding the optimal solution.

**Part 3: Voronoi Diagram and Delaunay Triangulation**

* **Voronoi Diagram:**  A partitioning of a plane into regions based on the distance to points in a specific subset of the plane.
* **Delaunay Triangulation:** A triangulation of a set of points where no point is inside the circumcircle of any triangle.

**Part 4: Range Tree**

* **2D Range Tree:** A data structure used for efficient range queries on a set of points in two dimensions.

**Libraries Used**

* SciPy
* NumPy
* Matplotlib
* NetworkX

**How to Run**

1. Make sure you have the necessary libraries installed (`scipy`, `numpy`, `matplotlib`, `networkx`).
2. Run the code in a Jupyter Notebook or Google Colab environment.

**Visualizations**

The project includes visualizations for the convex hull algorithms, Voronoi diagram, Delaunay triangulation, and range tree.