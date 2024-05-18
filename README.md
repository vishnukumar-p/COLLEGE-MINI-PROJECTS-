Introduction
The Bellman Algorithm Visualizer is a tool designed to help users understand the Bellman-Ford algorithm through visual representation. The Bellman-Ford algorithm is used to find the shortest paths from a single source vertex to all other vertices in a weighted graph. Unlike Dijkstra's algorithm, it can handle graphs with negative weights.

Features
Interactive Graph Creation: Add and remove vertices and edges.
Visualization of Algorithm Steps: Watch each step of the Bellman-Ford algorithm in action.
Path Highlighting: See the shortest path from the source to any vertex.
Error Handling: Detects and alerts about negative weight cycles.
Installation
To run the Bellman Algorithm Visualizer locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/vishnukumar-p/bellman-algorithm-visualizer.git
cd bellman-algorithm-visualizer
Install dependencies:
If you're using Node.js, you might have a package.json file. Install the dependencies with:

bash
Copy code
npm install
For Python, if you're using pip and have a requirements.txt file:

bash
Copy code
pip install -r requirements.txt
Start the application:
For a Node.js application:

bash
Copy code
npm start
For a Python application:

bash
Copy code
python app.py
Usage
Add Vertices: Click on the canvas to add vertices.
Add Edges: Click on one vertex and drag to another to create an edge. Set the weight of the edge.
Run Algorithm: Select the source vertex and click "Run Bellman-Ford".
View Steps: Use the controls to step through the algorithm's execution.
