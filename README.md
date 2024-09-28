This Bash script is designed to monitor the CPU utilization of multiple servers remotely using SSH. It reads the list of servers from a text file and retrieves the top 5 non-root processes consuming the most CPU on each server. The output is displayed in a formatted table with the columns: PID, USER, CPU(%), and COMMAND.

Features:

Accepts a list of server hostnames from a text file.
Connects to each server via SSH and retrieves CPU utilization information.
Displays the top 5 CPU-consuming non-root processes in a structured table format.
Provides error handling for missing or invalid input files.
