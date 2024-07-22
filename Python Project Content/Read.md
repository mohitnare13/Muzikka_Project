# Muzikka - Python Music Player

Muzikka is a comprehensive music player application built using Python.
It provides a rich graphical user interface (GUI) for playing music, managing playlists, 
and controlling playback. This project utilizes various libraries and tools to offer a seamless music experience.

## Features

- Play, pause, and stop music
- Manage playlists
- Select favorite songs
- View song metadata
- SQLite for local database operations
- Oracle database integration for favorite songs using cx_Oracle
- Utilizes threading for managing playback time
- Rich GUI using Tkinter

## Libraries Used

### Tkinter

Tkinter is used for creating the graphical user interface (GUI) of the application. 
It provides various widgets to create windows, dialogs, buttons, labels, and more.

### cx_Oracle

cx_Oracle is a Python extension module that enables access to Oracle databases. In Muzikka, 
it is used to connect to an Oracle database for selecting and managing favorite songs.

### SQLite

SQLite is a C library that provides a lightweight, disk-based database. Muzikka uses SQLite for 
  managing local music data and playlists.

### Mutagen

Mutagen is a Python module to handle audio metadata. It supports various audio file formats
and is used in Muzikka to read and write metadata such as artist name, album title, and track number.

### Pygame

Pygame is a set of Python modules designed for writing video games. In Muzikka, 
it is used for playing music files. Pygame handles the playback of audio files,
providing controls for play, pause, and stop functionalities.

### Threading

Threading is used in Muzikka to manage playback time. By using threads,
the application can handle multiple tasks simultaneously, such as updating the playback time while playing music.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mohitnare13/Muzikka.git
Navigate to the project directory:

bash
Copy code
cd Muzikka
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Set up the Oracle database connection by configuring the necessary parameters in the code.

Run the application:

bash
Copy code
python main.py
Usage
Use the GUI to navigate through your music library.
Play, pause, or stop music using the control buttons.
Add or remove songs from your playlists.
Select your favorite songs and manage them using the Oracle database integration.
Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.


Acknowledgements

Tkinter for the GUI
cx_Oracle for Oracle database connectivity
SQLite for local database management
Mutagen for handling audio metadata
Pygame for music playback functionality
Happy coding!

