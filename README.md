# Biomechanical Analysis of Hammer Throw Stereo Data

This repository provides tools for the biomechanical analysis of hammer throw using stereo motion capture data in C3D format. The program processes raw C3D files into cached files for faster analysis, applies data cuts based on hammer speed, and computes key biomechanical variables such as tangential velocity, angular velocity, and more.

It also detects critical instants of the throw, including:

 - Hammer positions at 0, 180, and 270 degrees. Where 0 is at the middle right corner of the ring.

 - Foot lift events

 - Lowest hammer position

Finally, the program generates plots for visualization of the results.
