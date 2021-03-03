# Sorting Algorthim Visualization
Visualisation of some popular sorting algorithms using openGL framework. 

# ABOUT SORTING
Sorting a sequence of items is one of the pillar of Computer Science.
A sorting algorithm is an algorithm that organizes elements of a sequence in a certain order. Since the early days of computing, the sorting problem has been one of the main battlefields for researchers. The reason behind this is not only the need of solving a very common task but also the challenge of solving a complex problem in the most efficient way.

This project is an attempt to visualize and help to understand how some of the most famous sorting algorithms work. This project provides two standpoints to look at algorithms, one is more artistic (apologies to any real artist out there), the other is more analytical aiming at explaining algorithm step by step.

This project does not want to teach the theory of sorting algorithms, there are amazing resources, books and courses for this purpose. Sorting Visualizer program is for the ones who want to see these algorithms under a different light and theme and hopefully appreciate the processing and brain power behind these piece of genius that in many ways have changed the way we live.

## Features
- Provides random theme for every run
- Two modes for interaction
- Keyboard interface

## About Mode
### Interactive Mode
Using this mode you can watch each swap of variables with interaction. 
Press `s` to go to next swap.

### Outstanding Mode
This mode will run the selected algorithm with predefined constant speed.

## Menu
- To start the sorting press `s`
- To pause the soritng press `p`
- To randamize the inputs press `r`
- To change\select the algorithm press `c`
- To set interactive mode press `i`
- To set outstanding mode press `o`
- To set new random color press`z` which also randomize the inputs
- Press `<ESC>` key to terminate the application

## Algorithms 
- Bubble Sort

- Selection Sort

- Insertion Srot

- Ripple Sort (Another version of Bubble sort)

- Comb Sort (Another version of Bubble sort)

## ScreenShots
![bublesort](https://user-images.githubusercontent.com/60929919/97009257-80b09800-1561-11eb-9dd9-ddb24da965f0.png)
![ripple-sort](https://user-images.githubusercontent.com/60929919/97009411-b190cd00-1561-11eb-9664-42d591652e97.gif)
#### OutStanding Mode:
![outstandig-mode](https://user-images.githubusercontent.com/60929919/97009270-84dcb580-1561-11eb-9fd2-4da52191da03.gif)
#### Interactive Mode:
![interactive-mode](https://user-images.githubusercontent.com/60929919/97009445-b9507180-1561-11eb-8645-a9673339f620.gif)

## Installation 
```bash
# Clone this repository
$ git clone https://github.com/rustiever/SortingAlgorthimsVisualizer.git

# Go into the repository
$ cd SortingAlgorthimsVisualizer
```

## Build/Compile Application
### Mac Os
```bash
$ g++ -framework OpenGL -framework GLUT visualizer.cpp -o visualizer -Wno-deprecated
```
### Linux/Debian/Ubuntu
```bash 
$ g++ visualizer.cpp -lGL -lGLU -lglut
```
## Run Application
```bash
$ ./visualizer
```
Built and Tested on Mac OS ✅👍🏻


Made with :heart: and C++.
