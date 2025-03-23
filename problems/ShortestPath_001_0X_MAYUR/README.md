## Problem description:
You are given two coordinates start coord and end coord:
- For Level-1: You have to print a list of shortest path(any shortest path) coords we can take in order to reach start to end in 2D plane.
- For Level-2: You have to print a list of shortest path(any shortest path) coords we can take in order to reach start to end in 3D plane.
- For Level-3: You have to print a list of all the possible shortest paths for 2D coords.

## Input/output formats:
You have given two tuples that contain start and end coords in standard form
ex., (5,6) and (7,0) where the first coord is abssica and second one is ordinate.

## Sample cases:
INPUT: shortest_path_2D((5, 6), (7, 0)) here shortest_path_2D this func return the list of coords like


OUTPUT: path = [(5, 6), (6, 5), (7, 4), (7, 3), (7, 2), (7, 1), (7, 0)]


## Constraints & notes:
- One step at a time, you can't tavel more than one step at a time.
- You can move horizontally, vertically and digonally to the closest coord.
- All the coord are discrete interger values.
