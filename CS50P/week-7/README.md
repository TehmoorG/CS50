# Week 7: File I/O

## Overview
Week 7 introduces the concept of File Input/Output operations in Python. This week's tasks involve reading, processing, and writing various file formats, including text, CSV, and image files.

## Task 1:  Lines of Code
- **Description**: A program that counts the number of lines of code in a Python file, excluding comments and blank lines.
- **Usage**: 
  - Run `python lines.py [filename.py]`
  - The program will output the number of lines of code in the specified Python file.

## Task 2: Pizza Py
- **Description**: A program that reads a CSV file containing Pinocchio’s pizza menu and outputs a table formatted as ASCII art.
- **Usage**: 
  - Run `python pizza.py [menu.csv]`
  - The program will display the menu in a user-friendly table format.

## Task 3: Scourgify
- **Description**: A program that reformats a CSV file of student names and houses, splitting the combined name column into separate first and last name columns.
- **Usage**: 
  - Run `python scourgify.py [input.csv] [output.csv]`
  - The program will create a new CSV file with the reformatted data.

## Task 4: CS50 P-Shirt
- **Description**: A program that overlays a virtual CS50 t-shirt onto an input image, giving the illusion that the person in the image is wearing the CS50 t-shirt.
- **Usage**: 
  - Run `python shirt.py [input_image] [output_image]`
  - The program will create a new image with the virtual t-shirt overlaid on the input image.

## Reflection

Week 7's focus on File I/O provided a deep dive into the intricacies of file operations in Python. The tasks ranged from simple file reading and writing operations to more complex tasks like image manipulation.

### Key Takeaways:

1. **File Operations**: Understanding how to read and write files is fundamental. The tasks reinforced the importance of handling files correctly, ensuring that they are opened, processed, and closed properly to prevent data corruption or loss.

2. **Data Transformation**: The `Scourgify` task highlighted the importance of data transformation and cleaning, a crucial step in many real-world data processing applications. Ensuring data is in a consistent and usable format is often a significant portion of a data scientist or developer's workflow.

3. **Image Manipulation**: The `CS50 P-Shirt` task introduced image processing, a powerful tool in Python. This task was a fun way to see how programming can interact with other file types beyond text and data, showcasing the versatility of Python.

4. **Error Handling**: Proper error handling, especially when dealing with files, is crucial. Ensuring that the program can handle incorrect inputs or missing files gracefully improves the user experience and prevents potential data loss or corruption.

5. **Documentation**: This week reinforced the importance of clear documentation. Whether it's commenting within the code or maintaining an external README, clear documentation ensures that the code's purpose and usage are understandable to others (and to oneself in the future).

Looking forward, the skills acquired this week will be invaluable. File operations are a cornerstone of many programming tasks, and the ability to manipulate, transform, and process different file types is a skill that will undoubtedly come in handy in future projects.