# File Organiser

**File Organiser** is a Python-based tool designed to help users easily manage and organise their files. The program moves files into folders named after their file extensions. For example, `.png` files are moved into a "png" folder, `.jpg` into a "jpg" folder, `.pdf` into a "pdf" folder, and so on.

### Features:
- Automatically moves files into folders based on their extensions (e.g., `.png` into a "PNG" folder, `.exe` into an "EXE" folder, etc.)
- Simple and intuitive graphical user interface (GUI)
- Two Python files for easy separation of concerns: GUI and backend
- Cross-platform compatibility

> Starting Application
<img width="452" height="332" alt="image" src="https://github.com/user-attachments/assets/d0529532-bb82-4fa1-92f1-22a08d6bd322" />

> Time Taken to Organise
<img width="452" height="332" alt="image" src="https://github.com/user-attachments/assets/d18c7e53-3f0c-4253-a280-4d65f32f2b37" />


### How it works:
The program scans a specified directory, identifies file extensions, and moves the files into corresponding folders based on their extensions. The program categorises various types of files such as `.png`, `.jpg`, `.pdf`, `.exe`, and more, making file organisation simple and efficient.

### Project Structure:
1. **gui.py**: This file handles the graphical user interface, designed using `customtkinter` and `tkinter` libraries.
2. **Source.py**: This file contains the backend code, handling the file operations such as scanning directories and moving files using the `os` module.

### Requirements:
- Python 3.x
- Required Python packages: 
  - `os`
  - `customtkinter`
  - `tkinter`
  
### How to Use:
1. Clone or download the repository.
2. Run the `gui.py` file to launch the graphical user interface.
3. Specify the directory you want to organise, and the program will automatically categorise and move files into folders based on their extensions.

   
