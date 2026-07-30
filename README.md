# Restaurant Management System — Prolog
# CSEN/CSIS Concepts of Programming Languages

A Prolog-based restaurant reservation and supply management 
system built as part of the Concepts of Programming Languages 
course at GUC.

## Project Overview
A logic programming solution that manages restaurant reservations,
staff constraints, ingredient tracking, and CSV report generation.

## Features

### a) Staff Validation
- Checks if reservations violate staff count constraints
- Ensures tables reserved never exceed staff available per day/time

### b) Reservation Scheduling
- Automatically schedules all groups across available days
- Validates table capacity, group preferences, time slots, and staff limits
- Uses constraint satisfaction to find valid schedules

### c) Ingredient Tracking per Group
- Computes all ingredients required by a group's orders
- Handles repeated ingredients across multiple dishes

### d) Daily Ingredient Planning
- Aggregates all ingredients needed per day across all reservations
- Groups ingredients by date for supply planning

### e) CSV Export — Reservations
- Exports full reservation schedule to CSV
- Columns: Day, Month, Time, Group, Table

### f) CSV Export — Shopping List
- Exports daily ingredient lists to CSV
- Columns: Day, Month, Ingredients (semicolon-separated)

## Technologies
- Prolog
- Logic Programming
- Constraint Satisfaction
- File I/O (CSV generation)

## Course
Concepts of Programming Languages — Spring 2026
German University in Cairo (GUC)
Dr. Yomna Hassan & Dr. Mary Guindy
