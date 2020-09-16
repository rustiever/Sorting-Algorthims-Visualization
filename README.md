# Sorting Algorthim Visualizer
Visualisation(internal working) of some popular sorting algorithms using openGL framework. 

# ABOUT SORTING
Sorting a sequence of items is one of the pillar of Computer Science.
A sorting algorithm is an algorithm that organizes elements of a sequence in a certain order. Since the early days of computing, the sorting problem has been one of the main battlefields for researchers. The reason behind this is not only the need of solving a very common task but also the challenge of solving a complex problem in the most efficient way.

This project is an attempt to visualize and help to understand how some of the most famous sorting algorithms work. This project provides two standpoints to look at algorithms, one is more artistic (apologies to any real artist out there), the other is more analytical aiming at explaining algorithm step by step.

This project does not want to teach the theory of sorting algorithms, there are amazing resources, books and courses for this purpose. Sorting Visualizer program is for the ones who want to see these algorithms under a different ligth and hopefully appreciate the processing and brain power behind these piece of genius that in many ways have changed the way we live.

## Features
- Dynamic coloring and theme
- Two modes for interaction
- Friendly interface

## usage
- will be updated shortly

## Algorithms 
- Bubble Sort

- Selection Sort

- Insertion Srot

- Ripple Sort (Another version of Bubble sort)

- Comb Sort (Another version of Bubble sort)

## How To Use
```bash
# Clone this repository
$ git clone https://github.com/rustiever/SortingAlgorthimsVisualizer.git

# Go into the repository
$ cd SortingAlgorthimsVisualizer

# Run application
## Mac Os
$ g++ -framework OpenGL -framework GLUT visualizer.cpp -o visualizer -Wno-deprecated
## Linux/Debian/Ubuntu
$ g++ visualizer.cpp -lGL -lGLU -lglut

```
Built and Tested on Mac OS ✅👍🏻

Note: currently the cpp file is mix of c and c++. So need to seperate them. 
Current goal is to make the code more readable and maintainable.