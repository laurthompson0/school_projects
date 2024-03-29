# School Projects

A repository of interesting projects I created or contributed to while completing my Bachelor of Science in Computer Science.

## Project List

- smart_home
- agriculture_drone
- systems_programming
- pulsar_candidate_selection
- static_program_analysis

## smart_home

**Course:** CS 499, Capstone

**Languages/Frameworks:** Python (Flask), Javascript (React), SQL (PostgreSQL)

**Project Description:**  
This project is a web application using the React framework frontend, Flask backend, and PostgreSQL database.
It is meant to simulate a smart-home application interface.
The simulation runs 2 months of pre-generated events, as well as handling user-generated events in real time.
The user can alter the state of lights, faucets, doors and windows, as well as view power and water usage data.
This was my final project submission for my capstone course, completed with a team of six members.

## agriculture_drone

**Course:** CS 420, Software Engineering

**Languages/Frameworks:** Java8, JavaFX

**Project Description:**  
This project is an interface for a simulated farm and agriculture drone built using JavaFX with Java8.
The interface allows the user to add, delete, edit, and view items and containers on a simulated farm.
The user can also control a drone to visit items on the farm and scan the entire farm.
This project was completed with a partner as my final project for my software engineering course.

WARNING: This project contains a dependency to interface with a real DJI Tello drone, but attempting
to utilize this feature ('Launch Drone' button) will cause the program to time out if no drone is connected.

## systems_programming

**Course:** CS 332, Systems Programming

**Languages/Frameworks**: C

**Project Description**:  
This consists of five smaller projects written for my Systems Programming course
in which I learned how to utilize various aspects of the Linux operating system
programmatically including searching a filesystem,
creating and synchronizing threads,
signal handling,
communicating between processes using pipes, and
scheduling jobs

## pulsar_candidate_selection

**Course:** CS 463, Data Mining

**Languages/Frameworks:** Python, scikit-learn, Jupyter notebooks

**Project Description:**  
This project utlizes the [HTRU2 dataset](https://archive.ics.uci.edu/ml/datasets/HTRU2) for pulsar candidate classification.
The purpose of the dataset is to show that the set of 8 features are effective for classifying potential pulsar candidates.
For this project, I worked on a team of four to confirm the classification results of the paper
'Fifty Years of Pulsar Candidate Selection: From simple filters to a new principled real-time classification approach', R. J. Lyon et al.
as well as determine if we could get better classification results using several different classification methods.
Additionally, we did an analysis of feature importance as well as performing principal component analysis of the features
to determine if we could effectively further reduce the set of features.

Note: This project is assosciated with the paper [Pulsar_candidate_result_replication.pdf](https://github.com/laurthompson0/papers/blob/main/Pulsar_candidate_result_replication.pdf)

## static_program_analysis

**Course:** CS 399, Directed Readings

**Languages/Frameworks:** Datalog, Racket

**Project Description:**  
This project contains some of the code and documentation that I created during an
independent study and research course in which I learned about using the logic
programming language Datalog for use with static program analysis. This research
was conducted under the mentorship of Thomas Gilray, Ph. D. from the HARP lab
at the University of Alabama at Birmingham. This repo contains a parser
for a simple functional programming language, written in Racket, and
some basic program analysis of the reachability of data for programs
in this simple language, written in Datalog.

Note: This project is assosciated with the paper [Datalog_for_static_program_analysis.pdf](https://github.com/laurthompson0/papers/blob/main/Datalog_for_static_program_analysis.pdf)
