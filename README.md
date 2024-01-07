Desktop File Organizer
Description

This Desktop File Organizer script automatically sorts files on your desktop into designated folders based on their file extensions. It simplifies desktop management and keeps your workspace clean and organized.
Features

    Automatic Sorting: Moves files from the desktop into categorized folders.
    Customizable Mappings: Define your own file extension to folder mappings through a JSON configuration file.
    Logging: Records operations and errors in a log file for review.
    Skips Running Script: The script skips itself to avoid moving while it's running.

Requirements

    Python 3.x
    Windows Operating System (The script uses Windows path formats)

Setup and Configuration

    Clone/Download the Repository
        Clone this repository to your local machine or simply download the script and configuration files.

    JSON Configuration
        config.json: This file contains mappings of file extensions to folder names. Customize it according to your needs.
        Sample format:

        json

        {
            "Images": [".jpg", ".png"],
            "Documents": [".pdf", ".docx"],
            ...
        }

        Add or modify the file extensions and folder names as per your preference.

    Script File
        Place the script file (file_organizer.py or similar) on your desktop or a preferred location.

    Log File
        Logs.txt will be created in the same directory as the script to log operations and errors.

Usage

    Run the Script
        Execute the script. You can double-click it or run it from a command line/terminal.
        Files on the desktop will be moved to the folders specified in config.json.
        If a folder does not exist, it will be created.

    Check Logs
        Open Logs.txt to review operations and error messages.

Customization

    Edit config.json to change how files are sorted.
    Ensure that file paths in the script match your system configuration (especially if you're not using Windows).

Limitations

    The script is designed for Windows paths and might need adjustments for other operating systems.
    It does not handle duplicate files; if a file with the same name exists in the destination, an error will be logged.

Contributing

    Contributions to improve the script or add new features are welcome. Please submit a pull request or open an issue to discuss your ideas.

License

    Add your licensing information here (if applicable).
