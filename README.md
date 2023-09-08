# Audit Tool 

## Overview
This README provides information about the Audit Tool, a Node.js-based code analysis utility designed to analyze JavaScript code within a specified directory. The tool provides various metrics and insights into your codebase.
## Getting Started
Follow these steps to set up and use the Audit Tool:
1. Clone this repository to your local machine: git clone https://github.com/yourusername/audit-tool.git
2. Install Node.js if you haven't already. You can download it from [nodejs.org](https://nodejs.org/).
3. Navigate to the tool's directory:
cd audit-tool
4. Install the required dependencies:
npm install
## Usage
The Audit Tool offers several options to analyze your JavaScript code. Here's how to use them:

### 1. Count Files in Directory
Set the directory path to analyze, and this option will count the total number of files in that directory.
Example:
node audit-tool.js 1

### 2. Count Methods in File
Specify a JavaScript file within the directory, and this option will count the number of methods in that file.
Example:
node audit-tool.js 2

### 3. Count Lines Inside Methods (Directory)
This option calculates the total number of lines inside methods across all JavaScript files in the specified directory.
Example:
node audit-tool.js 3

### 4. Find Methods Without Comments
Identify and list methods in the codebase that lack comments.
Example:
node audit-tool.js 4

### 5. Find Improperly Named Methods
List methods in the codebase that do not follow proper naming conventions (methods should start with a capital letter).
Example:
node audit-tool.js 5

### 6. Find Global Variables
List global-scoped variables in the codebase and provide the total count of such variables.
Example:
node audit-tool.js 6

### 7. Count Callback Functions
Count the number of callback functions in a specific JavaScript file within the specified directory.
Example:
node audit-tool.js 7

### 8. Count Lines in Specific File
Count the total number of lines in a specific JavaScript file within the specified directory.
Example:
node audit-tool.js 8

### 9. Exit
Choose this option to exit the program.
Example:
node audit-tool.js 9
Before using options 2 to 8, ensure you set the directory path by choosing option 1.
