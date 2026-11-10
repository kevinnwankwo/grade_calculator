Student Academic Performance Analyzer:

A CLI-based Python utility designed to automate the collection, calculation, grading, and structural ranking of student academic performance metrics. The application processes data profiles for five students across four core subject metrics: Mathematics, English, Physics, and Chemistry.

Key System Features:

Robust Input Validation: Safely traps out-of-bounds metrics (less than 0 or greater than 100) and alphanumeric characters using try-except structural blocks.
Comprehensive Data Structuring: Packages information within composite nested dictionary datasets appended to an active data array.
Performance Metrics Calculations: Computes total scores, student averages, and global class average figures automatically.
Sub-Failure Isolation Tracker: Identifies and flags individuals who failed (scored under 45) in two or more courses.
Dynamic Leaderboard Generation: Organizes and formats student lists sorted down in clean descending order of individual grade-point averages.

Technical Requirements:

Python Target Version: Python 3.6 or later

Core Dependencies: Standard library modules only (no third-party dependencies required).


Setup & Running Guide:

Clone or save the source code into a local script named `analyzer.py`.

Open your standard command line terminal environment.

Move to the directory containing your file and run:
```bash
   python analyzer.py
   ```


System Rules Reference:

Grading Boundaries Map:

70 – 100: A

60 – 69: B

50 – 59: C

45 – 49: D

Below 45: F


Subject Scope:

Mathematics

English

Physics

Chemistry
