Energy Management System

Overview This project is an energy management system developed as a simulation of data logging and metadata management. The system manages log files for different energy sources (e.g., solar, wind, etc.) and charging stations, simulates data exchange, and provides user interaction to search and retrieve log data based on equipment name or date. The system is designed to support the creation, movement, deletion, and archiving of log files and includes metadata tracking of these operations.

Features

Log management for each day, charging station, and energy source
Simulation of data exchange using byte and character streams
User interaction for opening log files based on equipment name or date
Metadata management to track log operations (create, move, delete, archive)
Regular expression based search functionality
Task Distribution

Log Management (Mohammed) Responsible for creating, moving, deleting, and archiving log files. Simulated the creation of log files for each day, each charging station, and each energy source. Implemented file operation methods and metadata tracking.

Data Exchange Simulation (Onyedikachi): Focused on simulating the data exchange using byte and character streams. Handled reading and writing of energy data to log files. Ensured that the data streams could interact with the file system and logs created by Mohammed.

User Interaction and Search Functionality (Stevenson): Implemented functionality to allow users to search for log files based on equipment name or date. Utilized regular expressions to facilitate log file searches and display content. Managed the user interface and handled input/output interactions through the console.

Metadata and Project Integration (Junaid): Managed the metadata system to track file operations like creation, deletion, movement, and archiving. Integrated all components: log management, data exchange, and user search functionality. Handled the tracking of operations and ensured that metadata logs were correctly generated.

How to Run the Project

Clone the repository from GitHub.
Compile the project using Eclipse IDE.
Run the main class (Main.java) to simulate the energy management system.
Use the console interface to interact with the system and search for logs.
Requirements

Java 8 or higher
Access to a file system for log file creation
Basic knowledge of regular expressions and file I/O operations
