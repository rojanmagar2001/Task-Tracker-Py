# Task Tracer

A simple command-line task tracking application built with Python, Typer, and Rich.

## Features

- Add tasks with categories
- Delete tasks
- Update existing tasks
- Mark tasks as complete
- Display all tasks in a formatted table

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/task-tracer.git
   cd task-tracer
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

### Add a task
```
python main.py add "Learn Python" "Study"
```

### Delete a task
```
python main.py delete 1
```

### Update a task
```
python main.py update 1 "Learn Python deeply" "Study"
```

### Mark a task as complete
```
python main.py complete 1
```

### Show all tasks
```
python main.py show
```

## Requirements

- Python 3.10+
- typer
- rich

## Project Structure

- `main.py` - Main application file with CLI commands
- `database.py` - Database operations
- `model.py` - Todo data model
- `requirements.txt` - Required dependencies

## License

MIT
