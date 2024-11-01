# Mapper Public
**_Source Code Available upon Demand_**
## Overview
<img width="696" alt="image" src="https://github.com/WilliamJWen/Mapper_Public/assets/103137385/7bb3757c-e781-4286-af2a-e126d1f11e71">

This is a Google Maps-like software implemented from scratch using C++ for backend and GTK3 for frontend framework. Geographical Data is from OpenStreetMap.

**Contributors:**
- William Wen (Me!) \
**Contact Info:** \
https://github.com/WilliamJWen \
https://www.linkedin.com/in/jwilliamwen/ \
jwilliam.wen@mail.utoronto.com
- Alissa Xiang \
**Contact Info:**\

- Holly Han \
**Contact Info:**\

## Key UI Features

### Drop Down Menu for City Selection

### Intelligent Search Bar

### Interactive Navigation Mode


## Algorithms

### Fastest Path between two intersections
We integrated **A* Algorithm** on top of **Dijkstra Algorithm** and increased calculating speed by 3 times without any scarification of accuracy through applying well-thought-out heuristics.
### Variation of Travelling Salesman Problem(TSP)
- Our solution integrates Multi-Start, probability Greedy algorithm, 2-opt perturbation, and simulated annealing.

## How This Project Was Divided

This project was divided into four milestones over four months:

1. **Milestone 1: Data Organization and API Extension**
   - The first milestone focused on organizing large amounts of data into structured formats. Additionally, it involved extending an existing API by implementing useful functions to support later milestones.

2. **Milestone 2: Map Drawing with EZGL**
   - The second milestone utilized a graphics library called EZGL, which is a wrapper around the GTK library. EZGL depends on GTK 3 and Cairo (full details available [here](https://github.com/mariobadr/ezgl)). The objective of this milestone was to draw the map using this library, leveraging the functions implemented during the first milestone.

3. **Milestone 3: Pathfinding and Directions**
   - The third milestone aimed to implement pathfinding between two intersection points on the graph representing the map. Additionally, it included designing and creating directions that accompany the path found.

4. **Milestone 4: Multi-Stop Pathfinding**
   The final milestone focused on finding an optimised path with multiple stops. Specifically, it involved finding an optimal path for multiple deliveries and drop-offs. For example, given four pickups labelled A, B, C, and D and four drop-offs labelled A, B, C, and D, the goal was to determine the shortest possible path, ensuring that by the time the delivery driver reaches drop-off C, they have the package from pickup C. Moreover, the delivery driver must start and end at a depot.
     
Let me know if you need any further adjustments or additional details!

## What were some challenges I faced
### Map Display disrupted with lines connected different cities
Reason:
Used vector.resize() with vector.push_back()

### GTK search bar 
Solution:
- global flag

### GTK Pop-up window slide bar
Problem: 
- A small portion on the pop-up window seems to be blocking mouse click
Result:
- Unsolved 

## What I learned from this project 
- Collaboration using source control tools such as git
- Work Management using Wiki and Markdown
- Communication and Presentation
- User Interface Design and User Experience
- The world 🌍 is just nodes and edges !!!
## What I would do differently if I were to restart this project.
- Object Oriented Programming
- Less Global Variable
- Cache the map (Split the map into multiple sections
- Unit test every function

## What I would refine in the existing code if I had more time
- 
## The Potential Future of this Project
- Wheelchair
- Bikeshare Saftey
- Food delivery
- GPS Drawing
