# Automated Backup Tool (File Handling)

A simple command-line tool that backs up all files from a source directory into a timestamped backup folder and keeps a log of every backup.

## Features

- Creates a new backup folder with a timestamp (`backup_YYYY-MM-DD_HH-MM-SS`)
- Copies files while preserving metadata (`shutil.copy2`)
- Appends a log entry listing every backed-up file

## Usage

Run the script and follow the prompts:

```bash
python app.py
```

It will ask for:

1. **Source directory** - the folder to back up
2. **Base backup directory** - where timestamped backups are created
3. **Log file path** - where backup logs are appended

## Requirements

- Python 3.x
- No external packages (uses only the standard library)

## License

This project is provided for educational purposes.