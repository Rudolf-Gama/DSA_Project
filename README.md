# Hyderabad Metro Stations - DSA Project

## Project Overview

This Data Structures and Algorithms (DSA) project focuses on the Hyderabad Metro system. It utilizes various algorithms to manage and analyze routes between metro stations, including finding shortest paths, calculating travel costs, and listing all stations. The project demonstrates the application of graph theory, particularly Dijkstra's algorithm, to address real-world transit system challenges.

## Features

- **Metro Stations List**: Display a comprehensive list of all metro stations in Hyderabad.
- **Single Source to Single Destination**: Determine the shortest path and distance between a specific source station and a destination station.
- **Single Source to Multiple Destinations**: Compute the shortest paths from a single source to multiple destination stations.
- **Number of Stations Between Source and Destination**: Calculate the number of stations between a given source and destination.
- **Number of Stations Between Source and All Stations**: Compute the number of stations between a given source and all other stations.
- **Cost Calculation**: Estimate the travel cost based on the distance between stations.

## Files

- **`main.c`**: Contains the main function and the interactive menu for user interactions.
- **`functions.c`**: Implements various functions for calculating routes, distances, and costs.
- **`functions.h`**: Header file containing function prototypes and constants used in `functions.c`.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- A C compiler (e.g., GCC)
- Make (optional, if using a Makefile)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/DSA_CourseProject.git
   cd DSA_CourseProject

## Compile and Run the Code

Use the following command to compile and run the project with a C compiler:

```bash
gcc -o metro_project main.c functions.c
./metro_project
