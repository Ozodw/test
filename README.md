# test
OpenTrack Management Script
Overview

OpenTrack Management Script is a Python-based tool designed for managing contributors in open-source projects, tracking software issues, and generating automated project reports.

The system helps organize project data efficiently using core Python data structures and demonstrates practical file handling, data processing, and reporting techniques.

Developed by Norkobilov Ozodbek Turgun Ugli.

Features
1. Project Metadata and Contributor Tracking

The script manages basic project and contributor information.

Project metadata includes project name, version, and project lead, stored using tuples.
Contributor information is stored in a list of dictionaries, including name, role, programming languages, and commit counts.
Contributors are sorted alphabetically.
A set is used to store unique programming languages and generate a tech stack overview.
2. Issue Management System

The script includes a simple issue tracking system.

Stores 5 issues with details such as ID, title, priority, reporter, and status.
Counts the number of open issues.
Identifies urgent issues based on priority levels such as High and Critical.
Performs basic analytics on issue priorities.
Determines the top reporter based on the number of submitted issues.
3. Automated File Operations

The script automates file creation and report generation.

Creates a folder named open_track to store project files.
Exports issue data into a CSV file named issues.csv for external use.
Generates a project_report.txt file containing a full summary of the project, including contributors and issue statistics.
Appends an additional section for urgent issues at the end of the report.
Technical Implementation

The project demonstrates the use of core Python concepts:

Tuples for storing immutable project metadata.
Lists for storing contributors and issues.
Dictionaries for structured data representation.
Sets for maintaining unique programming languages.

Error handling is implemented using try-except blocks to ensure safe file operations.

File handling techniques include:

read() for reading entire files
readline() for reading line by line
readlines() for reading file content into a list

The script also demonstrates file writing, appending, and CSV export functionality.

Purpose

The purpose of this project is to simulate a basic project management system. It helps demonstrate how contributors, issues, and project data can be structured and processed using Python.

It also shows how automation can simplify reporting and data management tasks in software projects.

Possible Improvements

Future improvements may include:

Integration with a database system such as SQLite or PostgreSQL
Development of a web interface using Flask or Django
Real-time issue tracking and updates
User authentication system for contributors
Data visualization using charts and graphs
