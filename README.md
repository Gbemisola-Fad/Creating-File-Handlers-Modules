# Creating-File-Handlers-&-Modules
Creating File Handlers and Modules for Retrieving Information about Insulin

Description
This project involves creating a Python module to retrieve and analyze information about human insulin from a JSON file. 

The module loads the data, parses the JSON structure, and calculates the rough molecular weight of human insulin based on the provided sequence.

Technologies Used
Python - The primary programming language used for developing the module and handling data

JSON Module - A built-in Python module used to parse JSON data from files

File Handling - Techniques for opening, reading, and processing files in Python


Implementation Details
Module Creation - A custom Python module is created to encapsulate the functionality for loading and processing insulin data

File Handling - The module includes functions to open a JSON file, read its contents, and load the data into a Python dictionary using the json.load() method

Data Parsing - The JSON structure is parsed to extract relevant information about insulin, such as its amino acid sequence and other properties

Molecular Weight Calculation - A function is implemented to calculate the rough molecular weight of human insulin based on its amino acid sequence

This involves summing the weights of individual amino acids as defined in the project


Design Considerations
Error Handling - The module includes error handling to manage potential issues such as file not found errors and JSON parsing errors

Modularity - The code is organized into functions to promote reusability and clarity, making it easier to maintain and extend in the future

Data Validation - Basic validation checks are implemented to ensure that the amino acid sequence is valid before calculating the molecular weight

