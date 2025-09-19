# Marvellous Study Tracker App

The Student Tracker is a console-based C++ application designed to help students log, review, and analyze their daily study sessions efficiently. It serves as a digital study diary that enables better time management and productivity tracking.

Project Name: Student Tracker Using Java

## Overview :
The Student Tracker is a console-based Java application that allows students to efficiently log, monitor, and analyze their daily study sessions. Each study record contains the date, subject, duration, and description, stored in CSV file.


# Technologies Used : 
## O: Language: Java
## O: Packages & APIs:

    java.util.* → Data structures (ArrayList, TreeMap), user input via Scanner.  
    java.time.LocalDate → Auto-captures the current date for study logs.  
    java.io.File handling and CSV export.  

## O: The project provides :

### 1. Insert Study Log Management  

Users can insert new study records with the following details:  

        Date (fetched automatically from system)  
        Subject  
        Duration (in hours)  
        Description of the study activity  

### 2. Display Logs

Displays all study records in a structured manner.  
Each entry shows:  

        Date  
        Subject  
        Time spent  
        Description  

### 3. Summary Reports  

Summary by Date: Caluculates and displays total study hours per day.  
Summary by Subject : Displays Subject and time spent on it per day.  

### 4. Menu-Driven Interface  

User-friendly console menu with numbered options:  

        Insert Log  
        View Logs  
        Summaries  
        Export to CSV  
        Exit  

### 5. Key Benefits

Helps students identify and analyze study patterns.  
Improves time management and productivity.  
Provides structured data for academic tracking through CSV export.  

### 6. CSV Export Feature  

Exports all study logs into a CSV file (Study.csv).  
The file can be opened in Excel, Google Sheets, or any spreadsheet tool.  

### 7. Scope for Future Enhancements  

Retain previous data from .csv file.  
Update realtime data in csv for every log entry  
