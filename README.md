# AirBnB Clone — Console and File Storage

An educational Python project from the ALX / Holberton Software Engineering curriculum. This stage focuses on a command-line interface for managing application objects and persisting them between sessions.

## Overview

The console provides commands for creating, viewing, updating, and deleting model instances. A JSON-based file-storage layer serializes objects to disk and reloads them when the application starts.

## Core concepts

- Python classes, inheritance, and object modelling
- Command-line interfaces with Python's `cmd` module
- JSON serialization and deserialization
- File-based persistence
- Unit testing and code organization

## Console commands

The command interpreter supports the main object-management operations:

| Command | Purpose |
|---|---|
| `create` | Create an instance of a supported model |
| `show` | Display an instance by class and ID |
| `all` | Display stored instances |
| `update` | Update an instance's attributes |
| `destroy` | Delete an instance |
| `quit` / `EOF` | Exit the console |

## Run locally

```bash
git clone https://github.com/Famous3262/AirBnB_clone_v2.git
cd AirBnB_clone_v2
./console.py
```

If the script is not executable in your environment, run it with Python:

```bash
python3 console.py
```

At the console prompt, try commands such as:

```text
(hbnb) all
(hbnb) quit
```

## Status

Academic project / learning-stage implementation. This repository documents work on the console and persistence layer; it is not a deployed accommodation-booking service.
