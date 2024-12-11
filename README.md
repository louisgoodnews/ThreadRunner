# ThreadRunner

ThreadRunner is a Python utility for managing and executing concurrent operations using threads. It provides a simple and efficient way to handle multiple threads with built-in logging capabilities.

## Features

- Concurrent function execution in separate threads
- Built-in logging system
- Thread pool management
- Asynchronous operation support
- Custom logging levels

## Installation

1. Clone the repository:
```bash
git clone https://github.com/louisgoodnews/ThreadRunner.git
cd ThreadRunner
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

```python
from thread_runner import ThreadRunner
from logger import Logger

# Initialize ThreadRunner
runner = ThreadRunner()

# Example function to run in a thread
def example_task():
    # Your code here
    pass

# Run the task in a new thread
runner.run_in_thread(example_task)
```

## Project Structure

- `thread_runner.py`: Main thread management implementation
- `logger.py`: Logging functionality
- `level.py`: Logging level definitions

## Requirements

- Python 3.6+
- See `requirements.txt` for package dependencies

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
